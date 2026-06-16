🏦 OrgBank Dashboard - Projeto Fintech

Atividade avaliativa desenvolvida para a disciplina de Análise e Desenvolvimento de Sistemas (FIAP).

💻 Sobre o Projeto

Este projeto consiste no desenvolvimento da interface (Front-end) de uma Dashboard Financeira para a fintech fictícia OrgBank. A aplicação foi construída para consolidar os conhecimentos adquiridos em HTML, CSS e na utilização do framework CSS Tailwind.

O objetivo principal foi criar uma interface limpa, moderna, responsiva e que mantivesse a identidade visual da marca (baseada nas cores de sua logo: Azul, Verde e Amarelo).

🎯 Funcionalidades da Interface

A tela principal simula o ambiente logado de um usuário em um banco digital e apresenta:

Menu de Navegação: Lateral expansivo para desktop e otimizado para mobile.

Visão Geral: Card com o saldo atual do usuário e métricas de entrada do mês.

Ações Rápidas: Botões de acesso fácil para Área Pix, Pagamentos, Transferências e Recargas.

Cartão de Crédito Virtual: Representação visual de um cartão "Black" construída integralmente com HTML/CSS, exibindo fatura e limite.

Extrato Resumido: Tabela estruturada com as últimas transações do usuário, informando estabelecimento, data, status e valor.

Análise de Despesas: Gráficos de barras horizontais indicando o percentual de gastos por categoria.

🛠️ Tecnologias Utilizadas

Para a construção do layout, foram utilizadas as seguintes tecnologias e ferramentas:

HTML5: Estruturação semântica do conteúdo.

CSS3: Estilização personalizada, criação de gradientes complexos e efeitos de transição (hover).

Tailwind CSS (via CDN): Framework utilitário utilizado para a rápida construção do layout responsivo e aplicação de cores padronizadas da identidade visual (sem necessidade de build via Node.js, garantindo execução direta).

Font Awesome: Biblioteca de ícones vetoriais.

Google Fonts (Inter): Tipografia oficial escolhida para o projeto.

⚙️ Arquitetura e Organização

Visando as melhores práticas e os critérios da atividade, o projeto respeita a separação de responsabilidades (HTML vs. CSS):

📁 projeto-fintech/
│
├── 📄 index.html         # Estrutura principal da página e importação do Tailwind
├── 📄 README.md          # Documentação do projeto
│
├── 📁 css/
│   └── 📄 style.css      # Customizações específicas (Scrollbar, degradê do cartão, animações)
│
└── 📁 images/
    └── 🖼️ logoorgbank.png # Logotipo oficial da aplicação


🚀 Como executar o projeto

O projeto foi configurado para rodar de maneira simplificada, sem a necessidade de instalar pacotes (NPM/Yarn) ou servidores locais complexos.

Clone este repositório em sua máquina:

git clone https://github.com/joaopeorossi/fiap-fintech-tela.git


Entre na pasta do projeto:

cd fiap-fintech-tela


Dê um duplo clique no arquivo index.html.

Alternativa: Clique com o botão direito no arquivo index.html e escolha "Abrir com" > Selecione seu navegador de preferência (Google Chrome, Firefox, Edge, etc.).

Nota: Para que o layout seja renderizado corretamente, é necessário possuir uma conexão ativa com a internet, pois o Tailwind CSS e a fonte Inter são carregados externamente via CDN.

Feito com 💻 e ☕ por João Pedro Rossi.
