# ReciCasa: Gestão Eficiente da Coleta Seletiva em Condomínios

## Visão Geral

O ReciCasa é um projeto dedicado à gestão eficiente da coleta seletiva de resíduos em condomínios residenciais. Seu principal objetivo é facilitar o processo de coleta seletiva, tornando-o acessível para os moradores, ao mesmo tempo em que promove a separação adequada de materiais recicláveis. Através de um site intuitivo, o administrador pode agendar a coleta conforme necessidade, e a partir disto os moradores irão receber informações sobre a separação correta de resíduos, obter lembretes sobre os dias de coleta e até mesmo acompanhar o histórico de coleta. Além disso, o sistema permite que os moradores forneçam feedback e relatem problemas relacionados à gestão de resíduos.

## Funcionalidades Principais

- Agendamento de Coleta Seletiva.
- Notificações e Lembretes sobre Dias de Coleta.
- Orientações sobre Separação Adequada de Materiais Recicláveis.
- Histórico de Coleta.
- Sistema de Feedback e Relatórios de Problemas.

## Tecnologias Utilizadas

- Linguagem de Programação: JavaScript, HTML, CSS.
- Banco de Dados: MySQL.
- Front-end: HTML, CSS, JavaScript.

## Pré-Requisitos

- **Navegador Web:** O ReciCasa é uma aplicação web
  
- **Editor de Código:** Ultilizado para modificar e visualizar os arquivos HTML, CSS e JavaScript. 

- **Git:** Ultilizado paraclonar o repositório Git do ReciCasa para seu ambiente local

## Instalação

[Upl <!DOCTYPE html>
<html>
<head>
    <title>Página Inicial</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: black;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2ecc71;
            color: white;
            padding: 20px;
            /*display: flex;*/
            justify-content: space-between;
            align-items: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #e0e0e0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            color: black;
        }
        h1 {
            font-size: 24px;
        }
        p {
            font-size: 16px;
            line-height: 1.5;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            display: inline;
            margin-right: 20px;
        }
        ul li a {
            text-decoration: none;
            font-size: 18px;
            color: #000000;
            font-family: "Arial", sans-serif;
        }
        button.logout-button {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-family: "Arial", sans-serif;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: black;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2ecc71;
            color: white;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #e0e0e0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            color: black;
        }
        h1 {
            font-size: 24px;
        }
        p {
            font-size: 16px;
            line-height: 1.5;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            display: inline;
            margin-right: 20px;
        }
        ul li a {
            text-decoration: none;
            font-size: 18px; /* Altere o tamanho da fonte conforme necessário */
            color: #000000; /* Altere a cor do texto conforme necessário */
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="container" style="text-align: center;">
            <img src="logotipo.jpeg" alt="Projeto ReciCasa Logo" style="max-width:40%;">
                <h1>Bem-vindo ao ReciCasa</h1>
            <ul>
                <li><a href="sobre nos.html">Sobre Nós</a></li>
                <li><a href="noticia.html">Notícia</a></li>               
            </ul>
        </div>
        <button class="logout-button" onclick="logout()">Logout</button>
        </div>
    </header>
    <!-- Resto do conteúdo da página -->

    <script>
        function logout() {
            window.location.href = "registro.html"; // Redireciona para a página de login
        }
    </script>
</body>
    </header>
    <!-- Resto do conteúdo da página -->
</body>
    </head>
    <body>
       <div class="container">
            <h2>Conscientização Ambiental</h2>
            <p>O Projeto ReciCasa é dedicado a aumentar a conscientização ambiental em condomínios residenciais. A coleta seletiva é uma parte vital da preservação do meio ambiente e do desenvolvimento sustentável, e estamos comprometidos em educar e envolver as comunidades.</p>
            <p>Através do nosso site, oferecemos informações, dicas e recursos para incentivar práticas mais sustentáveis e responsáveis com o lixo e a reciclagem. Junte-se a nós para fazer a diferença!</p>
            <img src="conscientizacao.jpg" alt="Conscientização Ambiental">
            
            <h2>Reciclagem e Coleta Seletiva</h2>
            <p>Defendemos a importância da reciclagem e da coleta seletiva. Através do Projeto ReciCasa, você pode agendar a coleta seletiva no seu condomínio, obter lembretes e orientações sobre como separar materiais recicláveis corretamente.</p>
            <p>Queremos facilitar o processo de reciclagem para você e sua comunidade, contribuindo para a preservação do meio ambiente e para o cumprimento das ODS.</p>
            <img src="reciclagem.png" alt="Reciclagem e Coleta Seletiva">

            <h2>Notícias e Atualizações</h2>
            <p>Fique por dentro das últimas notícias e informações relacionadas à coleta seletiva e ao meio ambiente. Mantemos você informado sobre projetos, iniciativas e dicas que podem ajudar a tornar sua comunidade mais sustentável.</p>
            <p>Estamos comprometidos em promover práticas responsáveis e inspirar a ação. A mudança começa com o conhecimento e a conscientização.</p>
            <img src="noticias.jpg" alt="Notícias e Atualizações">

            <html>
    </html>
oading inicial.html…]()

## Uso

- Acesso ao site.
- Login ou criar uma conta.
- Agende a coleta seletiva, obtenha lembretes e orientações.
- Acompanhe o histórico de coleta e forneça feedback.

## Autores

- [Gabriel Ferraz]
- [Jonathan Lensk]
- [Stefany Fernandes]



