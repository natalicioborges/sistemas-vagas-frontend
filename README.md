<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README | Sistema de Cadastro de Vagas (Front-End Simulado)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        h1 {
            color: #1c3d5e;
            border-bottom: 2px solid #3b82f6;
            padding-bottom: 10px;
        }
        h2 {
            color: #3b82f6;
            margin-top: 25px;
        }
        code, pre {
            background-color: #eee;
            padding: 5px;
            border-radius: 4px;
            font-family: Consolas, monospace;
        }
        pre {
            padding: 15px;
            overflow-x: auto;
            border: 1px solid #ddd;
        }
        .icon {
            font-size: 1.2em;
            margin-right: 5px;
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>

    <h1><span class="icon">💼</span> Sistema de Cadastro de Vagas (Front-End Simulado)</h1>

    <p>Este projeto foi desenvolvido como um exercício prático focado na criação de um front-end moderno, utilizando conceitos de <strong>componentes</strong>, <strong>rotas</strong> e <strong>design responsivo</strong>, simulando o consumo de uma API em um ambiente que se assemelha a uma aplicação em Spring Boot/Angular.</p>

    <h2>✨ Requisitos do Projeto</h2>

    <ul>
        <li><strong>API Simulado:</strong> O arquivo <code>vagas-db.json</code> atua como a API para o front-end.</li>
        <li><strong>Rotas:</strong> Possui pelo menos duas rotas principais:
            <ul>
                <li><code>/</code> (Listagem de Vagas)</li>
                <li><code>/vaga/:id</code> (Detalhes da Vaga)</li>
                <li><code>/sobre</code> (Página Adicional)</li>
            </ul>
        </li>
        <li><strong>Design:</strong> Utiliza <strong>Tailwind CSS</strong> e <strong>CSS customizado</strong> para um design limpo, moderno e responsivo, cumprindo o requisito de criatividade e organização de layout (conhecimento UC8).</li>
        <li><strong>Tecnologias:</strong> HTML, JavaScript (para lógica de rotas) e Tailwind CSS.</li>
    </ul>

    <h2>🚀 Como Rodar o Projeto</h2>

    <p>Como a aplicação é composta por arquivos estáticos e usa <code>fetch()</code> para carregar o arquivo <code>vagas-db.json</code>, é necessário executá-la a partir de um <strong>servidor web local</strong> para evitar erros de CORS (Cross-Origin Resource Sharing).</p>

    <p><strong>Pré-requisitos:</strong></p>
    <ul>
        <li>Node.js (ou qualquer outra ferramenta que possa subir um servidor estático).</li>
    </ul>

    <h3>Opção 1: Usando <code>http-server</code> (Recomendado)</h3>

    <ol>
        <li>Instale o pacote <code>http-server</code> globalmente via npm:
            <pre><code>npm install -g http-server</code></pre>
        </li>
        <li>Navegue até a pasta onde você salvou os arquivos:
            <pre><code>cd [caminho_do_seu_projeto]</code></pre>
        </li>
        <li>Inicie o servidor:
            <pre><code>http-server</code></pre>
        </li>
        <li>Abra seu navegador e acesse a URL fornecida (geralmente <code>http://127.0.0.1:8080</code> ou <code>http://localhost:8080</code>).</li>
    </ol>

    <h3>Opção 2: Usando o Live Server do VS Code</h3>

    <p>Se você utiliza o VS Code, pode usar a extensão "Live Server" para abrir o arquivo <code>index.html</code>.</p>

    <h2>📂 Estrutura de Arquivos</h2>

    <pre><code>/
├── index.html        # Front-End completo (HTML, JS, CSS/Tailwind)
├── vagas-db.json     # A API simulada com a lista de vagas
└── README.md         # Este arquivo
</code></pre>

</body>
</html>
