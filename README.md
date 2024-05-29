# Case Engenharia de Dados - FakeStore API

Este projeto é parte do teste técnico para a vaga de engenheiro de dados júnior.

## Descrição

O objetivo deste projeto é consumir dados de uma API, transformá-los e persistí-los em um arquivo CSV. O arquivo final contém as seguintes informações:
- Identificador de usuário.
- Data mais recente em que o usuário adicionou produtos ao carrinho.
- Categoria em que o usuário tem mais produtos adicionados ao carrinho.

## Como Executar

1. Clone este repositório:
    ```bash
    git clone https://github.com/Lribeiro27/enjoei-case-fakestore-api.git
    ```
2. Crie e ative um ambiente virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```
3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
4. Execute o notebook:
    - Abra o notebook `enjoei_case.ipynb` em um ambiente Jupyter.
    - Selecione a opção de executar tudo.

## Estrutura do Projeto

```plaintext
CaseEnjoei/
├── data/
│   └── analise.csv
├── src/
│   ├── enjoei_case.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Comentários

Optei por utilizar a linguagem Python neste projeto e uma pequena parte em SQL, semelhante ao uso que faço do spark no dia a dia, onde parte do desenvolvimento é realizada com pyspark e parte com sparksql. 
Fiz todo o desenvolvimento em português incluindo comentários, mas mantendo a nomenclatura original das variáveis em inglês, como retornado na API.
Os detalhes sobre a execução de cada célula estão no Notebook.