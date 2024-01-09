# Organização e limpeza de dados | Análise exploratória | Análise Inferencial


## enem_sp_2019_tratamento_de_dados:
- Arquivo com o objetivo de receber os dados, entender os valores de cada coluna e procurar por incosistência, bem como realizar os tratamentos necessários.
- As principais alterações foram:
 - Alteração de nome das colunas para facilitar a digitação e entendimento dos dados.
 - Alteração dos valores de algumas colunas para facilitar entendimento dos dados, por exemplo, trocar valores 1 por "Sim" na coluna "TREINEIRO"
 - Limite de idade de 15 até 80 anos de idade para evitar inconsistência.
 - Correção das notas, de 0 a 100 para 0 a 1000
 - Alteração de ID de inscrição
 - Exclusão de colunas
 - Exclusão de inscritos com residência em SP porém com escolas fora de São Paulo
- Caso prefira acessar o link pelo Google Colab [clique aqui.](https://colab.research.google.com/drive/1uJ24UuEilYrMctTisxI3M1bYEFeg0nse?authuser=1)
---
## enem_sp_2019_EDA:
- Arquivo destinado a análise exploratória, procurando observar os dados de forma geral, e realizar comparações entre amostras de dados para levantamento de discussões
- Observação das médias de notas dos alunos de forma geral e por tipo de prova
- Comparação entre desempenho de inscritos por agrupamentos como sexo, cor/raça, treineiro/vestibulando e tipo de escola(pública ou privada)
- Caso prefira acessar o link pelo Google Colab [clique aqui.](https://colab.research.google.com/drive/1ewEltefJ0gASSJStPg4HCdd5-Vow0zMA?usp=sharing)
---
## analise_tipo_escola
- Arquivo para verificar se há diferença estatística de notas entre escolas públicas e privadas (evitar olhar apenas o valores absolutos)
- Para este estudo foram utilizados grupos de amostras independentes e relativamente grandes
- Teste de Lilliefors para cada amostra (N > 5000)
- Teste de Mann Whitney para comprovação hipótese
- - Caso prefira acessar o link pelo Google Colab [clique aqui.](https://colab.research.google.com/drive/1aRzfFbbQ0x_JbDZqLoCsCxs4iwT4B66a?usp=sharing)
  
