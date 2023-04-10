# Medicina_no_Brasil

No Brasil, os cursos de medicina são extremamente concorridos e exigentes, com uma carga horária intensa e duração média de seis anos. As faculdades de medicina no país oferecem formação em diversas áreas, como cirurgia, pediatria, ginecologia e obstetrícia, entre outras especialidades médicas.

Existem opções de bolsas para estudantes que desejam cursar medicina no país. Uma das principais opções é o Programa Universidade para Todos (PROUNI), que oferece bolsas de estudos parciais e integrais em universidades particulares para estudantes de baixa renda que tenham obtido boas notas no Enem.

Além disso, há também a possibilidade de ingressar em universidades públicas, que são gratuitas e oferecem um ensino de qualidade reconhecido mundialmente. No entanto, o processo seletivo para ingresso em universidades públicas é bastante concorrido e exige um alto desempenho dos candidatos.

Nas próximas seções, iremos disponibilizar alguns resultados com base em dados modificados do PROUNI e de universidades públicas, a fim de fornecer informações mais detalhadas sobre as opções de bolsas e ingresso nessas instituições de ensino.

Esse conjunto de dados apresenta informações sobre cursos de graduação na área de saúde em universidades brasileiras. As colunas incluem informações sobre o grau do curso, turno, mensalidade, tipos de bolsa integral e parcial (cotas e ampla concorrência), cidade e universidade. Além disso, há informações sobre as notas de corte para acesso às vagas com bolsa e sem bolsa.

Algumas informações que podem ser interessantes avaliar nesse conjunto de dados são: quais universidades oferecem bolsas de estudos e qual é a porcentagem de bolsas concedidas para cada curso; quais são as notas de corte para acesso às vagas com bolsa e sem bolsa; quais são as universidades e cidades com os cursos mais caros e mais baratos em relação à mensalidade; quais são as opções de cursos em diferentes cidades e estados do país.

| curso_id        | grau        | turno     | mensalidade | bolsa_integral_cotas | bolsa_integral_ampla | bolsa_parcial_cotas | bolsa_parcial_ampla | curso_busca | cidade_busca | uf_busca | cidade_filtro                        | universidade_nome                                     | campus_nome                                     | campus_id | nome      | nota_integral_ampla | nota_integral_cotas | nota_parcial_ampla | nota_parcial_cotas |
|----------------|-------------|-----------|-------------|----------------------|-----------------------|---------------------|----------------------|-------------|--------------|----------|--------------------------------------|-------------------------------------------------------|------------------------------------------------|-----------|-----------|---------------------|----------------------|---------------------|----------------------|
| 706710394154   | Bacharelado | Integral  | 9999.99     | 15                   | 14.0                  | NaN                 | NaN                  | Medicina    | Campo Grande | MS       | NTAwMjAwNDAyNzA0                    | Universidade Anhanguera - UNIDERP                      | CAMPO GRANDE - SEDE - Miguel Couto             | 706710    | Medicina  | 740.22              | 726.46               | NaN                 | NaN                  |
| 104191210567043 | Bacharelado | Noturno   | 9836.40     | 1                    | NaN                   | NaN                 | NaN                  | Enfermagem  | Crateus      | CE       | MjMwNDAxODA0MTAz                    | Faculdade Princesa do Oeste - FPO                       | UNIDADE SEDE - São Vicente                    | 1041912   | Enfermagem | 663.36              | NaN                  | NaN                 | NaN                  |
| 1002328574024  | Bacharelado | Integral  | 9715.61     | 2                    | 5.0                   | 6.0                 | 10.0                 | Medicina    | Sao Paulo   | SP       | MzUxNTA2MTUwMzA4                    | Universidade Cidade de São Paulo - UNICID              | UNIVERSIDADE CIDADE DE SÃO PAULO - UNICID - SE... | 1002328   | Medicina  | 739.62              | 738.08               | 738.96              | 718.64               |
| 104191212798093 | Bacharelado | Noturno   | 9689.34     | 3                    | 2.0                   | NaN                 | NaN                  | Psicologia  | Crateus      | CE       | MjMwNDAxODA0MTAz                    | Faculdade Princesa do Oeste - FPO                       | UNIDADE SEDE - São Vicente                    | 1041912   | Psicologia | 651.00              | 652.22               | NaN                 | NaN                  |
| 65899611932754  | Bacharelado | Integral  | 9674.34     | 4                    | 1.0                   | 5.0                 | 2.0                  | Medicina    | Rio Branco  | AC       | MTIwMjAwNDAwNDAx                    | Faculdade Barão do Rio Branco - FAB                     | CAMPUS - RIO BRANCO - JARDIM EUROPA II - Jard... | 658996    | Medicina


## Qual o total de cursos de medicina?

Ao todo temos 124 cursos de medicina no dataset do Prouni.

A partir dessa tabela, podemos inferir algumas informações sobre as bolsas de estudo oferecidas nos cursos de graduação do conjunto de dados. A média de bolsas integrais concedidas por curso por meio de cotas é de 2.80, enquanto a média de bolsas integrais concedidas por ampla concorrência é de 2.27. Já a média de bolsas parciais concedidas por cotas é de 4.47, enquanto a média de bolsas parciais concedidas por ampla concorrência é de 3.87.

Além disso, podemos observar a variação desses números, representados pelo desvio padrão, e verificar que há uma grande variabilidade nas concessões de bolsas pelos cursos. Podemos também observar os valores mínimo e máximo e verificar que o número de bolsas concedidas pode variar de 1 a 8 para bolsas integrais por cotas, de 1 a 5 para bolsas integrais por ampla concorrência, de 1 a 9 para bolsas parciais por cotas e de 1 a 10 para bolsas parciais por ampla concorrência.

![image](https://user-images.githubusercontent.com/7840963/230946131-1a7efe39-bc90-4868-94a8-98b84db6ecc0.png)

## Qual é a média da mensalidade dos cursos de medicina por estado?

Podemos ver que o Estado com maior média de mensalidades é o Acre e o menor é o Espírito Santo.

![image](https://user-images.githubusercontent.com/7840963/230946283-0ae2f26c-c9da-4b46-b966-f45026e881a4.png)

## Quais estados possuem um número maior de cotas?

![image](https://user-images.githubusercontent.com/7840963/230946344-e287946c-d624-4a65-b868-3a846cbe7744.png)


Já para quem prefere estudar nas grandes capitais temos 10 cursos em capitais de estados.

![image](https://user-images.githubusercontent.com/7840963/230946403-cbef0562-7a77-49e9-9171-e9d053490f62.png)

É fundamental entender como a mensalidade de um curso se relaciona com a quantidade de bolsas oferecidas, pois isso pode influenciar significativamente a acessibilidade e a viabilidade financeira da educação superior para muitos estudantes. Então vamos responder a pergunta.

![image](https://user-images.githubusercontent.com/7840963/230946482-c4f699e0-7c57-4be1-898d-f6128497c413.png)

Existem outras relações que podem ser obversadas como a notas de quem tem cotas e de quem não possui.

![image](https://user-images.githubusercontent.com/7840963/230946537-6f07f30a-1096-4681-8c5b-97cca903d25e.png)



## Como o período do curso afeta a mensalidade?

Cursos em perído integral possuem uma mensalidade mais alta e com uma variação muito maior.

![image](https://user-images.githubusercontent.com/7840963/230946625-e77ced56-2352-461d-adf3-34173b77efa8.png)

Comparando os cursos de enfermagem com os de medicina vemos que os cursos de medicina são muito mais caros mesmo sendo de uma área correlata.

![image](https://user-images.githubusercontent.com/7840963/230946701-a3e7d155-cfea-480a-926a-f83ac98b535d.png)


Em relação as faculdades, a que tem a melhor nota é a campo real.

![image](https://user-images.githubusercontent.com/7840963/230946734-0dc9c4b4-904d-4dc2-9bce-f2bd5424eff2.png)

## Como a quantidade de bolsas variou nos últimos anos?

Fonte: https://pt.wikipedia.org/wiki/Programa_Universidade_para_Todos Acessado em: 16/03/2023

Tivemos um aumento de bolsas em 2021

![image](https://user-images.githubusercontent.com/7840963/230946830-93200900-6781-4f6d-b643-9f6ba98c4906.png)

Caso a pessoa decida tentar uma universidade pública a USP é a que possui melhor nota, seguida pela Unicamp.

![image](https://user-images.githubusercontent.com/7840963/230946881-e1d81473-35da-4156-b3fb-c9c7dc1457c9.png)





