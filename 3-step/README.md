# ADM-Curso

## Dia 3

# Alinhando sequências de nucleotídeos
---
## Alinhando sequências de nucleotídeos com o mafft Online

1- Acesse o [Mafft](https://mafft.cbrc.jp/alignment/software/)

Usando os arquivos do organismo desconhecido, execute os alinhamentos a seguir. Abra uma nova guia no seu navegador para cada alinhamento.
- FFT-NS-1; deixe tudo como padrão; selecione saída rápida; copie e cole no arquivo de texto; salvar como ascos.its.mafft.FFT-NS-1.aln
- G-INS-i; deixe tudo como padrão; salvar como "nome".mafft.GINS-i.aln
- E-INS-i; deixe tudo mais padrão; salve como "nome".mafft.EINS-i.aln
- G-INS-i; mude a penalidade de abertura de abertura para 5.0; salvar como "nome".mafft.GINS-i.op5.aln
- G-INS-i; mudar "matriz de pontuação para seqüências de nucleotídeos" de 200PAM / k = 2 para 1PAM / k = 2; certifique-se de que a penalidade de abertura de lacuna seja ajustada para 1.53; salvar como "nome".mafft.GINS-i.1PAM.aln

1. Esses alinhamentos diferem em comprimento?
2. Você acha que um alinhamento é melhor que os outros? É obviamente pior do que os outros?
3. Você pode melhorar o alinhamento fazendo ajustes manuais? Isso parece objetivo?

Veja o menu "Alinhar" no Aliview para saber como editar manualmente os alinhamentos.

Existem outros programas que permitem a vizualização de sequências e alinhamentos como por exemplo:

- Aliview [:minidisc:](http://ormbunkar.se/aliview/downloads)
- MEGA [:minidisc:](https://www.megasoftware.net/)
- Ugene [:minidisc:](http://ugene.net/)

# Minimizando a incerteza de alinhamento
---
Como você pode ver no alinhamento acima, pode haver muita incerteza no processo de alinhamento e lidar com essa incerteza ajustando manualmente os alinhamentos não é o ideal.

Vamos usar algumas abordagens diferentes para lidar com a incerteza de alinhamento: Guidance2 e GBLOCKS.

Rodando o GUIDANCE

Na página de resultados do MAFFT, você verá um botão de opções que permitirá direcionar a saída de alinhamento de múltiplas seqüências do MAFFT para o servidor GUIDANCE. Abra a guia no seu navegador para o seu alinhamento GINS-i (ascos.its.mafft.GINS-i.aln).
Clique no botão de rádio GUIDANCE2. Clique em OK na caixa de diálogo pop-up.
Você deve ser direcionado ao servidor GUIDANCE2 e seu alinhamento deve aparecer. Certifique-se de que GUIDANCE2 seja o algoritmo selecionado. Digite seu endereço de e-mail e atribua à tarefa um nome descritivo (ascos.its.mafft.GINS-i.aln.guidance2).
Deixe o bootstrap repetido no padrão de 100.
Digite os caracteres da imagem na parte inferior para provar que você não é um robô.
Enquanto isso está sendo executado, vamos ver como usar o GBLOCKS. Voltaremos a falar sobre os resultados do GUIDANCE2.