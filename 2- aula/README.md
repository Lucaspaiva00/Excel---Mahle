## Aula 02
#### Correção da AV - Diagnóstica

#### Conhecimentos:
- 1.2.  Estatísticas 
- 1.2.1.  Contases 
- 1.2.2.  Médiases 

### Exercícios práticos para explorar as funções estatísticas CONT.SES e MÉDIASES no Excel:

##### - Exercício 1: CONT.SES — Contagem Condicional Múltipla
Descrição: Contar quantos pedidos foram realizados em janeiro por vendedores específicos.


![alt text](image.png)

=CONT.SES(A:A; ">=01/01/2025"; A:A; "<=31/01/2026"; B:B; "Maria")

##### - Exercício 2: MÉDIASES — Média Condicional Múltipla
Descrição: Calcular a média dos valores de vendas de João realizadas na região Sul.

```
=MÉDIASES(C:C; B:B; "João"; D:D; "Sul")
```

##### - Exercício 3: CONT.SES com múltiplos critérios personalizados
Descrição: Contar quantos pedidos foram feitos em regiões diferentes de "Sul" e com valores superiores a R$ 1.500,00.

```
=CONT.SES(D:D; "<>Sul"; C:C; ">1500")
```

#### - Exercício 4: MÉDIASES com faixa de datas
Descrição: Calcular a média das vendas realizadas em janeiro.

```
=MÉDIASES(C:C; A:A; ">=01/01/2025"; A:A; "<=31/01/2025")

```

## Conhecimentos - Tabelas e gráficos dinâmicos:
- 6.1. Criação de tabelas dinâmicas
- 6.1.1. Manipulação de campos
- 6.1.2. Campos calculados
- 6.1.3. Segmentos de dados
- 6.2. Gráficos Dinâmicos