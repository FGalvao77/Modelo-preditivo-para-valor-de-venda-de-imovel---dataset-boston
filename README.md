# Modelo preditivo para valor de venda de imóvel  - dataset boston

**Contextualizando**

> O desafio é criar um modelo preditivo para valor de venda de imóveis.
<br><br>
O conjunto de dados utilizados é o famoso _dataset boston_.<br>Existem 14 atributos em cada caso do conjunto de dados. Eles são:
1. `crim` - taxa de criminalidade per capita por cidade;
2. `zn` - proporção de terrenos residenciais zoneados para lotes com mais de 25.000 pés quadrados;
3. `indus` - proporção de acres de negócios não varejistas por cidade;
4. `chas` - variável dummy de Charles River (1 se a área limita o rio; 0 caso contrário);
5. `nox` - concentração de óxidos nítricos (partes por 10 milhões);
6. `rm` - número médio de cômodos por habitação;
7. `age` - proporção de unidades ocupadas pelo proprietário construídas antes de 1940;
8. `dis` - distâncias ponderadas até cinco centros de empregos de Boston;
9. `rad` - índice de acessibilidade a rodovias radiais;
10. `tax` - valor total da taxa de imposto sobre a propriedade por _10.000  dólares americanos_;
11. `ptratio` - proporção professor-aluno por cidade;
12. `black` - 1000 (black - 0,63) ^ 2 onde black é a proporção de negros por cidade;
13. `lstat` - % status inferior da população;
14. `medv` - valor médio de casas ocupadas pelo proprietário em _1.000 dólares americanos_.

- O dataste original se encontra no site:
  - https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

**Detalhes**

> Porém o conjunto de dados que iremos utilizar ele se encontra embutido na biblioteca do `PyCaret`.
<br><br>O desafio é descobrir quais **features** tem maior influência com a variável alvo - `medv`.

**Vamos para o desafio!**

Segue o link do [notebook](https://bit.ly/3qADulh).
