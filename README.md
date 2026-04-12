# FertIA - Digital Cultivator

Um sistema web para agricultura inteligente e sustentável.

## Estrutura do Projeto

```
fert.ia/
├── index.html              # Página inicial/landing page
├── pages/
│   ├── app/                # Sistema FertIA (área logada)
│   │   ├── alertas.html    # Centro de alertas inteligentes
│   │   ├── chat.html       # Interface de chat com FertIA AI
│   │   ├── creditos-carbono.html # Créditos de carbono
│   │   ├── dashboard.html  # Dashboard principal
│   │   ├── roi.html        # Retorno sobre investimento
│   │   ├── settings.html   # Configurações
│   │   └── talhoes.html    # Gestão de talhões
│   └── site/               # Site/Portfólio (área pública)
│       ├── assinatura.html # Página de assinatura
│       ├── home.html       # Página inicial do sistema
│       ├── login.html      # Página de login
│       ├── registro.html   # Página de registro
│       └── start.html      # Página inicial após registro
├── assets/                 # Recursos estáticos
│   └── images/             # Imagens do projeto
├── README.md               # Documentação do projeto
├── .gitignore              # Controle de arquivos ignorados
└── .git/                   # Controle de versão
```

## Tecnologias Utilizadas

- **HTML5** - Estrutura das páginas
- **Tailwind CSS** - Framework CSS para estilização
- **Material Symbols** - Ícones do Google
- **Google Fonts** - Fontes Inter e Manrope

## Como Executar

1. Clone o repositório
2. Abra o `index.html` em um navegador web
3. Navegue pelas páginas através dos menus

## Funcionalidades

- **Dashboard**: Visão geral da fazenda com métricas e alertas
- **Gestão de Talhões**: Controle e monitoramento de áreas cultivadas
- **Chat com FertIA**: Assistente IA para recomendações agrícolas
- **Alertas Inteligentes**: Notificações sobre condições do solo, clima, etc.
- **ROI Calculator**: Cálculo de retorno sobre investimento
- **Sistema de Créditos de Carbono**: Compensação ambiental

## Desenvolvimento

O projeto utiliza uma arquitetura de páginas estáticas com navegação baseada em links HTML. Todas as páginas compartilham componentes comuns como sidebar de navegação e headers responsivos.
