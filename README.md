# CRUD---Cadastro

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario JS</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <section class="main">
        <h1 class="titulo">Cadastro de Aniversário</h1>
        <form class="form js-form">
            <label for="name">
                <span class="form-label">Nome</span>
                <input class="form-field js-field" id="name" maxlength="120" minlength="3" pattern="([aA-zZ\s]+)" name="name" required type="text">
            </label>
            <br>
            <label for="birth-date">
                <span class="form-label">Data de Nascimento</span>
                <input class="form-field js-field" id="birth-date" name="birth-date" required type="date">
            </label>
            <button class="botao" id="botao">Salvar</button>
        </form>

        <table class="tabela js-tabela">
            <tr>
                <th>Nome</th>
                <th>Data de Nascimento</th>
                <th>Ações</th>
            </tr>
            
            
        </table>
    </section>

    <script src="./index.js"></script>
</body>
</html>
