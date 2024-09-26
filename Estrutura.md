biblioteca/
│
├── src/                        # Código-fonte do projeto
│   ├── __init__.py             # Torna o diretório um pacote Python
│   ├── main.py                 # Arquivo principal do sistema de gerenciamento de biblioteca
│   ├── database.py             # Contém funções para conectar ao banco de dados e manipular dados
│   ├── menu.py                 # Contém funções para exibir o menu e gerenciar interações com o usuário
│   └── exploratory_analysis.py  # Análise exploratória dos dados
│
├── data/                       # Diretório para armazenar datasets e o banco de dados
│   ├── biblioteca.db           # Banco de dados SQLite
│   └── datasets/               # Armazena arquivos CSV para dados de exemplo
│       ├── books.csv           # Dataset de livros
│       ├── users.csv           # Dataset de usuários
│       └── loans.csv           # Dataset de empréstimos
│
├── docs/                       # Documentação do projeto
│   ├── README.md               # Documento de descrição do projeto
│   ├── LICENSE                 # Licença do projeto
│   └── relatorio.md            # Relatório sobre o sistema e suas funcionalidades
│
├── .gitignore                  # Arquivo para ignorar arquivos e diretórios no Git
└── requirements.txt            # Dependências do projeto (se houver)
