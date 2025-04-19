A_odisseia_de_um_prato/
│
├── assets/                  # Arquivos de mídia
│   ├── images/              # Imagens (sprites, cenários, etc)
│   └── sounds/              # Efeitos sonoros e música
│
├── PPlay/                           # Dependência do projeto
│
├── src/                     # Código-fonte
│   ├── game.py              # Loop principal e gerenciamento de estados
│   ├── main.py              # Arquivo principal (onde o jogo começa)
│   ├── settings.py          # Constantes e configurações do jogo
│   ├── scenes/              # Diferentes cenas do jogo (menu, fases, game over)
│   │   ├── menu.py
│   │   └── phase.py
│   ├── entities/            # Classes do player e estruturas
│   │   ├── player.py
│   │   └── structures.py
│   └── utils/               # Funções reutilizáveis quando perceber código repetido em várias partes
│       └── helpers.py
│
└── README.md                # Informações do projeto