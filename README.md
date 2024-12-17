# Projeto ETL Python

Um pipeline de dados que realiza operações ETL (Extract, Transform, Load) utilizando Python e a biblioteca requests.

## Visão Geral

Este projeto extrai dados de [origem] através de chamadas API, transforma os dados de acordo com regras de negócio e carrega em [destino].

## Funcionalidades

- Extração de dados utilizando a biblioteca `requests`
- Integração com API de [fonte de dados]
- Transformação e limpeza de dados
- Carregamento de dados em [destino]
- Tratamento de erros e logging
- Capacidade de agendamento automatizado

## Requisitos

- Python 3.8+
- requests
- pandas
- python-dotenv

## Instalação

1. Clone o repositório:
```
git clone https://github.com/seuusuario/projeto-etl-python.git
cd projeto-etl-python
```

2. Crie um ambiente virtual e ative-o:
```
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

3. Instale as dependências:
```
pip install -r requirements.txt
```

## Configuração

1. Crie um arquivo `.env` na raiz do projeto:
```
API_KEY=sua_chave_api
API_URL=url_da_api
```

## Como Usar

Execute o pipeline ETL:
```
python src/main.py
```

## Estrutura do Projeto
```
projeto-etl-python/
├── src/
│   ├── extract.py
│   ├── transform.py
│   ├── load.py
│   └── main.py
├── config/
│   └── config.py
├── tests/
├── .env
├── requirements.txt
└── README.md
```

## Como Contribuir

1. Faça um fork do repositório
2. Crie uma nova branch
3. Faça suas alterações
4. Envie um pull request

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.


