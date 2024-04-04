# Aplicações Web de Inteligência Artificial com Streamlit

## Ambiente de desenvolvimento

Para criar um ambiente de desenvolvimento, siga os passos abaixo:

python == 3.10.12

1. Crie um ambiente virtual com o comando `python -m venv nome_do_ambiente-env`
2. Ative o ambiente virtual com o comando `source nome_do_ambiente-env/bin/activate` (no Windows, o comando é `nome_do_ambiente-env\Scripts\activate`)
3. Instale as dependências com o comando `pip install -r requirements.txt`

## Executando a aplicação

1. Execute no terminal o comando `streamlit run nome_arquivo.py` (substitua `nome_arquivo.py` pelo nome do arquivo que deseja executar)
    obs: para executar o comando acima, é necessário estar no diretório raiz do projeto
2. Acesse o endereço `http://localhost:8501` no navegador
3. Para encerrar a aplicação, pressione `Ctrl + C` no terminal

## Projetos

### Caso 1: Prevendo Custos para abrir Franquia (Regressão)

- Problema de Regressão Linear: modelar e prever os custos iniciais para estabelecer uma franquia.
- Decisão de Investimentos:
  - Custo Anual
  - Investimento Inicial
- A partir da taxa anual é possível prever qual será o custo inicial para montar a franquia?
- Dados históricos para criar um modelo para servir como base para as previsões
  - dataset: 'slr12.csv'
  - arquivo: 'regressao-linear.py'
