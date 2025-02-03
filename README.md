# Site E-Commerce

Este é um projeto simples de um site de e-commerce desenvolvido com Flask, HTML, CSS e JavaScript. Ele inclui funcionalidades básicas como exibição de produtos, navegação e tratamento de erros.

## Funcionalidades

- **Exibição de Produtos**: Lista de produtos com imagens, descrições e preços.
- **Navegação**: Barra de navegação responsiva para acessar diferentes páginas (Início, Sobre, Contato).
- **Tratamento de Erros**: Página personalizada para erros 404.
- **Responsividade**: Interface adaptável para diferentes dispositivos (desktop, tablet e celular).

## Estrutura do Projeto
site-e-commerce/
│
├── app.py                  # Backend principal (Flask)
├── static/                 # Arquivos estáticos
│   ├── css/                # Estilos CSS
│   ├── js/                 # Lógica JavaScript
│   └── images/             # Imagens dos produtos
│
├── templates/              # Templates HTML
│   ├── base.html           # Template base
│   ├── index.html          # Página inicial
│   ├── about.html          # Página "Sobre"
│   ├── contact.html        # Página "Contato"
│   └── 404.html            # Página de erro 404
│
└── README.md               # Documentação do projeto

## Como Executar o Projeto

### Pré-requisitos

- Python 3.x instalado.
- Pip (gerenciador de pacotes Python).

### Passos

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Brunno2269/Navbar_Basico.git
   cd site-e-commerce