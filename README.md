<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->

# Descoberta de padrões em bases de dados de engenharia para automatizar o preenchimento

#### Aluno: [Jackson Luan Queiroz](https://github.com/Jacksonluan).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

- [Link para o código](https://github.com/link_do_repositorio/nome_do_arquivo_de_codigo). <!-- caso não aplicável, remover esta linha -->

- Trabalhos relacionados: <!-- caso não aplicável, remover estas linhas -->
    - [How to use Python Seaborn for Exploratory Data Analysis](https://www.justintodata.com/how-to-use-python-seaborn-for-exploratory-data-analysis/).
    - [Hands-On Guide To Market Basket Analysis With Python Codes](https://analyticsindiamag.com/hands-on-guide-to-market-basket-analysis-with-python-codes/).
    - [GradientBoostingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html).
    - [Gradient Boosting In Classification: Not a Black Box Anymore!](https://blog.paperspace.com/gradient-boosting-for-classification/).

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

O projeto de engenharia consiste em projetar diversos elementos e conecta-los de forma a ter no final o produto desejado. Para projetar esses itens são utilizados diversos
softwares de diferentes empresas, seja para simulação, seja para determinação de parâmetros ou para adequação às opções disponíveis no mercado. Percebe-se entretanto que
apesar de todo projeto ser diferente um do outro, muita das informação segue determinados padrões, se uma determinada váriável sobe, outra variável também sobe, assim se
essas relações estivessem todas mapeadas seria necessário calcular somente as variáveis de entradas primárias e todas as demais informações seriam resultantes de cálculos.

Entretanto muitas dessas relações são desconhecidas e as ferramentas de mercado não totalmente integráveis, demandando assim ainda um enorme esforço de cópia de informação
de um software para outro de forma manual, um homem hora de engenharia demasiadamente custos e muitas vezes sujeito a falhas de preenchimento. Atualmente temos um sistema
que sinaliza todas as informações que deveriam ser preenchidas e sinaliza para as disciplinas aquelas que faltam ser preenchidas, porém com a inteligência antificial e 
com os projetos passados a disposição podemos criar um ambiente de aprendizado de forma que seja cada vez menos necessário o preenchimento dessas informações faltantes, pois
elas podem ser aprendidas pelo sistema e recomendar o preenchimento ao engenheiro, economizando assim HH.

Este trabalho visa iniciar esse passo, nesse primeiro momento buscaremos encontrar relacionamentos dos itens elementos de engenharia chamados de "Equipamentos", analisaremos
a correlação entre as informações de forma a encontrar atributos que sejam possíveis ser inferidos. Por se tratar de um trabalho inicial, vamos abordar o método dos Gradientes
Boostering, pois eles utilizam árvores de decisão simples e possibilitam entregar quais atributos foram os principais responsáveis na identificação do padrão, possibilitando
assim um entendimento lógico sobre o relacionamento entre as variáveis para validação das disciplinas de engenharia.

Os resultados foram bem animadores, somente com essa técnica foi possível concluir que 12 dos 87 atributos são automatizáveis e apresentam relacionamento com outros atributos.
No projeto em questão esses 12 atributos requisitariam 43048 preenchimentos, se cada preenchimento durasse 30 segundos seriam necessário 359 HH de engenharia com preenchimento.
Considerando o HH de engenharia ao valor (conforme valores de salário básico do CREA) de R$ 43/HH estamos falando de R$ 15.585 economizados para um único elemento em um único projeto. Evoluindo esse trabalho para mais
elementos e utilizando não somente atributos dentro do mesmo elementos, mas atributos de elementos conectados estamos falando de um potencial de economia que superará facilmente
a casa dos milhões de reais.

São trabalhos como esse que mostram o valor e potencial da inteligência artificial no dia-a-dia das empresas.

---

Matrícula: 192.190.085

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
