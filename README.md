
# Data Science Screening (Lopes Labs)

O teste busca entender o seu processo de resolução de problemas, e entendimento dos dados disponibilizados, dando espaço para você demonstrar seus conhecimentos de Data Science e Machine Learning.

Os dados disponibilizados são de sobre imóveis da Lopes e seu respectivo preço, as features disponibilizadas representam as características de cada imóvel.

### Objetivo
O objetivo é que o candidado **faça uma breve análise dos dados**, da forma que achar melhor, e **desenvolva um modelo de precificação (regressão)** utilizando como target/variável dependente a coluna `sale`. A função custo a se minimizar é sugerido o **RMSE**, porém caso queira utilizar outra função **justifique**.

Sugerimos que o código desenvolvido tenha todos os comentários necessários para entendermos o processo, bem como boas práticas de programação e desenvolvimento de software.

Desenvolver todas as analises e treinamentos dentro do notebook `train.ipynb`!

### Dados
Os dados fornecidos estão dentro do diretório `/data` e contém dois arquivos `train.csv` e `test.csv`. A coluna `sku` identifica o imóvel, e as demais colunas as características do mesmo. A coluna `sale` é a target, que significa o valor daquele imóvel.
### Recomendações
Aproveite as capacidades do Jupyter Notebook de utilizar markdowns e comentários para documentar sua linha de pensamento.

### Formato do arquivo de predições
Após o treinamento e ajuste do modelo, as inferências deverão ser feitas com o arquivo `test.csv` o qual contém todas colunas do arquivo `train.csv` exceto a **target**. O arquivo final deverá conter somente 2 colunas, `sku` e `predict` conforme o exemplo abaixo, e salvo em formato `.csv` e com o nome `output.csv`

| sku | predict |
|---|---|
| 51173fe76f683f3ccd556ed32ce2f2ca | 750000 |
| b62f5788ed7c0f37d522085fe401dab7 | 230000 |
| cb40092e1db4824b5d352e2b46f4a478 | 856700 |
| 8253796889c2733a3a10fd4d1e9af1c5 | 1000000 |

### Entregável

Os arquivos finais a serem entregues é o notebook `train.ipynb`, o arquivo de `requirements.txt` com as libraries utilizadas e as predicts do modelo desenvolvido dentro do arquivo `output.csv`.
Zipar em um arquivo `<nome_do_candidato>.zip` e enviar para o RH da Lopes.


### Pontos de Atenção
Reprodutibilidade do treinamento, validação do modelo entregue.