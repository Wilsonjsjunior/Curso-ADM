# ADM-Curso
## Dia 1
---
Se você estiver usando um sistema operacional Windows, lembre-se de salvar todos os arquivos na unidade USB externa, porque nós iniciaremos o Linux Ubuntu mais tarde e você precisará acessar os arquivos que estão na sua unidade USB.

Comece fazendo um diretório em seu drive USB chamado MDA-Curso. Crie outro diretório dentro do MDA-Curso chamado Pratica_dia_1. Você pode fazer tudo isso em uma linha no terminal, se souber o nome da sua unidade USB. Substitua o nome da sua unidade USB nos locais apropriados abaixo.

Para criar um diretório no ubuntu faça:

`mkdir /media/ubuntu/"driver_name"/MDA-curso && mkdir /media/ubuntu/"Driver_name"/MDA-curso/Pratica_dia_1`

`mkdir` = *Make directory* "Cria um novo diretório"

`&&` = adiciona uma nova tarefa

# Adquirindo Dados do GenBank
---
Vamos usar recursos publicamente disponíveis para recuperar dados de sequência para comparação com dados de sequência que coletamos para os quais temos uma hipótese sobre sua origem (ou seja, gênero).

A primeira coisa que vamos fazer é certificar-se de que sequenciamos o organismo correto, comparando-o às sequências que foram depositadas no GenBank, que é hospedado pelo *National Center for Biotechnology Information Search database* [NCBI](https://www.ncbi.nlm.nih.gov/).

O GenBank® é o banco de dados de sequências genéticas do NIH, uma coleção anotada de todas as seqüências de DNA publicamente disponíveis. O GenBank faz parte da Colaboração Internacional de Banco de Dados de Sequência de Nucleotídeos, que compreende o DNA DataBank do Japão (DDBJ), o European Nucleotide Archive (ENA) e o GenBank no NCBI. Essas três organizações trocam dados diariamente. Mais informações [GenBank](https://www.ncbi.nlm.nih.gov/genbank/)

### Usando o BLAST para consultar o Genbank

Para pesquisar o banco de dados do GenBank, precisamos ter alguns meios de comparar nossas sequências com as sequências mais semelhantes.

##### O que é o BLAST?

É um algoritmo para comparar sequências.

A Ferramenta de Pesquisa de Alinhamento Local Básico [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) localiza regiões de similaridade local entre sequências. O programa compara sequências de nucleotídeos ou proteínas a bancos de dados de sequências e calcula a significância estatística das correspondências. O BLAST pode ser usado para inferir relações funcionais e evolutivas entre sequências, bem como ajudar a identificar membros de famílias de genes.

## Prática :computer:
---
Responda as seguintes questões:
1. Qual é o comprimento da sequência?
2. Quantos gêneros e espécies estão representados nos 10 melhores *hits*?
3. Qual porcentagem da nossa sequência de consulta está alinhada com a correspondência superior?
4. Qual porcentagem de nucleotídeos é idêntica à *top match*?
5. Quantas das 10 melhores correspondências não são idênticas ao longo do comprimento da sequência de consulta?
6. Qual é a probabilidade de você encontrar a mesma correspondência no banco de dados de sequências aleatórias do banco de dados atual do GenBank, dado o tamanho da sequência de consulta?
7. Esta sequência é publicada? Onde?
8. O *top match* está publicado? Onde?

Consulte o GenBank com as mesmas sequências e responda às seguintes perguntas:
1. Que região do genoma esta sequência representa?
2. Esta é uma sequência codificante?
3. Quantas espécies são representadas nos 15 melhores *hits*? Todos eles têm a mesma identidade de sequência com a sequência de consulta?
4. Os dois primeiros *hits* são publicados?
5. Qual é o número de acesso do GenBank para o melhor resultado?