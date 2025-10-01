💼 Sistema de Cadastro de Vagas (Front-End Simulado)

Este é um projeto de front-end criado em um único arquivo HTML usando JavaScript puro para simular um sistema de gerenciamento de vagas. Ele atende aos requisitos de rotas, componentes e design.

O objetivo é simular o consumo de dados de uma API, utilizando o arquivo local vagas-db.json.

🛠️ Tecnologias

HTML, JavaScript (Puro): Estrutura e lógica de roteamento.

Tailwind CSS: Framework utilitário para um design responsivo e moderno (substituindo o Bootstrap e cumprindo o requisito de CSS criativo da UC8).

JSON: Arquivo vagas-db.json para simular os dados da API.

🗺️ Rotas Implementadas

A aplicação possui rotas baseadas na URL (hash routing):

/: Lista todas as vagas disponíveis.

/vaga/:id: Exibe os detalhes de uma vaga específica.

/sobre: Página informativa adicional.

🚀 Como Executar

Para rodar este projeto, é necessário um servidor web local devido à leitura do arquivo vagas-db.json via fetch().

Método Recomendado (com Node.js):
Instale o http-server globalmente:

npm install -g http-server

Navegue até a pasta do projeto e inicie o servidor:

http-server

Acesse a URL fornecida (ex: http://localhost:8080) no seu navegador.

Arquivos Principais:

index.html (Contém todo o front-end: HTML, JS, CSS)

vagas-db.json (Dados da API)
