💼 Sistema de Cadastro de Vagas (Front-End Simulado)
Este projeto de front-end simula um sistema de vagas, desenvolvido como um exercício prático focado em componentes, rotas e design responsivo, simulando o consumo de uma API.

O objetivo é replicar a estrutura e a organização de um projeto moderno, como os criados em frameworks como Angular ou React, utilizando apenas JavaScript puro, HTML e Tailwind CSS.

✨ Requisitos Cumpridos
Requisito

Status

Detalhes

API Simulado

✅

O arquivo vagas-db.json simula a resposta do backend.

Duas Páginas de Rota

✅

Implementadas rotas para Listagem (/) e Detalhe da Vaga (/vaga/:id), além de uma página "Sobre".

Design / UC8

✅

Utilização de Tailwind CSS para design moderno, responsivo e criativo.

Organização

✅

Arquivos de código e dados separados para melhor estruturação.

🛠️ Tecnologias Utilizadas
Categoria

Tecnologia

Uso no Projeto

Estrutura

HTML5

Componentes e layout da interface.

Lógica

JavaScript (Puro)

Lógica de roteamento e consumo simulado da API.

Design

Tailwind CSS

Framework utilitário para design responsivo.

Dados

JSON

Arquivo vagas-db.json simulando o endpoint da API.

🚀 Como Rodar o Projeto Localmente
Para que a aplicação consiga carregar o arquivo vagas-db.json corretamente (via fetch()), é obrigatório executá-la a partir de um servidor web local para evitar problemas de segurança (CORS).

1. Estrutura de Arquivos
Certifique-se de que os seguintes arquivos estão na mesma pasta:

/sistema-vagas-frontend
├── index.html        # Front-End completo com JS e CSS
├── vagas-db.json     # Dados simulados da API
└── README.md         # Este arquivo

2. Iniciando o Servidor (Método Recomendado)
Se você tem o Node.js instalado, pode usar a ferramenta http-server:

Instale (se necessário):

npm install -g http-server

Navegue até a pasta do projeto:

cd [caminho_do_seu_projeto]

Execute o servidor:

http-server

Abra seu navegador e acesse a URL que aparecer no console (ex: http://127.0.0.1:8080).

3. Opção Alternativa
Você pode usar a extensão Live Server do VS Code. Basta clicar com o botão direito no index.html e selecionar "Open with Live Server".
