Esse projeto tem como objetivo a criação de um report que busque os sentimentos dos candidatos para presidência dos EUA em 2016 sobre determinados assuntos que comentaram em seus twitters.


BASE- A base tweets.csv contém os textos escritos pelos candidatos na rede social twitter durante meses próximos as eleições. A base foi adquirida através do kanggle, mas um robô que minere os dados do twitter poderia ser criado para montar a base se fosse preciso, o que poderia fazer o relatório continuar atualizando até os dias de hoje.

PROCESSAMENTO- Os dados passam por um processamento pelo powerquery no qual uma api de serviços cognitivos da azure é chamada para avaliar os sentimentos dos candidatos em cada texto. Uma segunda api também da azure é utilizada para separar as palavras chaves dos mesmos textos, assim temos as palavras chaves dos textos que os candidatos escreveram e os sentimentos relacionados aos mesmos.

EXIBIÇÃO- O report exibi as informações de várias formas diferentes buscando fornecer mais de uma ferramenta para se poder interpretar os dados, varias medidas foram criadas através da linguagem DAX para que houvesse KPIS próprios em cada análise. O relatório busca também trazer uma possibilidade de interpretação da reação do público geral sobre esses tweets dos candidatos exibindo favorites e compartilhamentos dos mesmos.

