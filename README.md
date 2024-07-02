## Análise de-Dados - PProductions
Esse projeto se baseia em uma análise de dados detalhada de um banco cinematográfico para orientação de possíveis tendências na realização de um novo filme para a empresa PProductions.

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/RafaelRSR/PProductions-Challenge
    cd PProductions-Challenge
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # No Windows use `venv\\Scripts\\activate`
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Execução

1. Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## Usando o Arquivo .pkl

O arquivo `.pkl` contém o modelo treinado para previsão da nota do IMDB. Para usá-lo, siga os passos abaixo:

1. Carregue o modelo a partir do arquivo `.pkl`:
    ```python
    import joblib

    # Carregar o modelo treinado
    model = joblib.load('model.pkl')
    ```

2. No navegador, abra o arquivo `LH_CD_RAFAELSROCHA.ipynb`.

3. Execute as células do notebook para reproduzir a análise.

## Dependências

As dependências necessárias para este projeto estão listadas no arquivo `requirements.txt`.
