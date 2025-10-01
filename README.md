💼 Sistema de Cadastro de Vagas (Front-End Simulado)
Este projeto foi desenvolvido como um exercício prático focado na criação de um front-end moderno, utilizando conceitos de componentes, rotas e design responsivo, simulando o consumo de uma API em um ambiente que se assemelha a uma aplicação em Spring Boot/Angular.

✨ Requisitos do Projeto
API Simulado: O arquivo vagas-db.json atua como a API para o front-end.

Rotas: Possui pelo menos duas rotas principais:

/ (Listagem de Vagas)

/vaga/:id (Detalhes da Vaga)

/sobre (Página Adicional)

Design: Utiliza Tailwind CSS e CSS customizado para um design limpo, moderno e responsivo, cumprindo o requisito de criatividade e organização de layout (conhecimento UC8).

Tecnologias: HTML, JavaScript (para lógica de rotas) e Tailwind CSS.

🚀 Como Rodar o Projeto
Como a aplicação é composta por arquivos estáticos e usa fetch() para carregar o arquivo vagas-db.json, é necessário executá-la a partir de um servidor web local para evitar erros de CORS (Cross-Origin Resource Sharing).

Pré-requisitos:

Node.js (ou qualquer outra ferramenta que possa subir um servidor estático).

Opção 1: Usando http-server (Recomendado)
Instale o pacote http-server globalmente via npm:

npm install -g http-server

Navegue até a pasta onde você salvou os arquivos:

cd [caminho_do_seu_projeto]

Inicie o servidor:

http-server

Abra seu navegador e acesse a URL fornecida (geralmente http://127.0.0.1:8080 ou http://localhost:8080).

Opção 2: Usando o Live Server do VS Code
Se você utiliza o VS Code, pode usar a extensão "Live Server" para abrir o arquivo index.html.

📂 Estrutura de Arquivos
/
├── index.html        # Front-End completo (HTML, JS, CSS/Tailwind)
├── vagas-db.json     # A API simulada com a lista de vagas
└── README.md         # Este arquivo
