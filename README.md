<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiropraxia - Seu Guia de Saúde</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0056b3;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #003d7a;
        }
        .container {
            padding: 2rem;
        }
        section {
            margin-bottom: 2rem;
        }
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .form-group textarea {
            height: 100px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Quiropraxia - Seu Guia de Saúde</h1>
    </header>
    <nav>
        <a href="#sobre">O que é Quiropraxia?</a>
        <a href="#beneficios">Benefícios</a>
        <a href="#tratamentos">Tratamentos</a>
        <a href="#sobre-quiropraxista">Sobre o Quiropraxista</a>
        <a href="#depoimentos">Depoimentos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="sobre">
            <h2>O que é Quiropraxia?</h2>
            <p>A quiropraxia é uma prática de saúde focada no diagnóstico e tratamento de problemas neuromusculoesqueléticos, com ênfase na coluna vertebral. O objetivo é restaurar a função adequada do sistema nervoso e promover a saúde geral do corpo.</p>
        </section>
        <section id="beneficios">
            <h2>Benefícios</h2>
            <ul>
                <li>Alívio da dor nas costas e pescoço</li>
                <li>Melhoria na postura</li>
                <li>Aumento da mobilidade e flexibilidade</li>
                <li>Redução da dor de cabeça e enxaquecas</li>
            </ul>
        </section>
        <section id="tratamentos">
            <h2>Tratamentos</h2>
            <p>Os tratamentos quiropráticos incluem ajustes na coluna vertebral, técnicas de mobilização e terapias físicas para melhorar a função articular e aliviar a dor. Cada plano de tratamento é personalizado de acordo com as necessidades do paciente.</p>
        </section>
        <section id="sobre-quiropraxista">
            <h2>Sobre o Quiropraxista</h2>
            <p>O Dr. João da Silva é um quiropraxista experiente com mais de 10 anos de prática. Ele é especializado no tratamento de dores crônicas e distúrbios musculoesqueléticos e se dedica a fornecer cuidados personalizados para cada paciente.</p>
        </section>
        <section id="depoimentos">
            <h2>Depoimentos</h2>
            <blockquote>
                <p>"A quiropraxia mudou minha vida! O tratamento foi eficaz e a equipe é muito profissional." - Maria Oliveira</p>
            </blockquote>
            <blockquote>
                <p>"Recomendo fortemente a quem precisa de alívio da dor nas costas. O Dr. João é excelente!" - Pedro Santos</p>
            </blockquote>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <form action="mailto:seuemail@exemplo.com" method="post" enctype="text/plain">
                <div class="form-group">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                </div>
                <div class="form-group">
                    <label for="email">E-mail:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" required></textarea>
                </div>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
    <footer>
        <p>Segue-nos nas redes sociais:</p>
        <a href="https://facebook.com/seuperfil" target="_blank">Facebook</a> | 
        <a href="https://twitter.com/seuperfil" target="_blank">Twitter</a> | 
        <a href="https://instagram.com/seuperfil" target="_blank">Instagram</a>
    </footer>
</body>
</html>
