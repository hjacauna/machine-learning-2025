# Machine Learning 2025

Este repositório contém exemplos do curso **Machine Learning 2025** ministrado no canal Téo Me Why. O objetivo é demonstrar conceitos básicos de aprendizado de máquina utilizando Python e bibliotecas populares.

## Estrutura do projeto

- `frutas.py` &ndash; script simples que treina uma árvore de decisão a partir de um conjunto de dados sobre frutas.
- `data/` &ndash; diretório onde deve ser colocado o arquivo `dados_frutas.xlsx` com as informações de treinamento (não incluído no repositório).
- `semana_01/` &ndash; coleção de scripts utilizados nas aulas, com exemplos de classificação, regressão e um app em Streamlit.
- `churn/train.py` &ndash; exemplo de pipeline para modelagem de churn com `pandas` e `scikit-learn`.

## Dependências

Para executar os exemplos é recomendável utilizar Python 3.9 ou superior.
Sugerimos criar um ambiente virtual antes de instalar as dependências necessárias:

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas scikit-learn matplotlib streamlit
```

## Como executar

1. Coloque os arquivos de dados necessários em `data/`. Cada script indica os nomes esperados.
2. Rode o script `frutas.py` para treinar uma árvore de decisão simples:

```bash
python frutas.py
```

3. Para executar o aplicativo de exemplo acesse `semana_01` e rode:

```bash
streamlit run app.py
```

4. O exemplo de churn pode ser iniciado em `churn/train.py` (requere o arquivo `abt_churn.csv` em `data/`).

## Contribuições

Este repositório faz parte de atividades de estudo. Sugestões e melhorias são bem-vindas via pull request.

