!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!--Bootstrap CSS-->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com//jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"> </script>
</head>

<body>
    <div class="conteiner mt-5">
        <h1>Exemplo de Tabela com Classes de Estilo do Bootstrap 4</h1>
        <table class="table table-bordered"> 
        <thead class="table-primary">
         <tr>
            <th>#</th>
            <th>Nome</th>
            <th>Sobrenome</th>
            <th>Email</th>
         </tr>   
        </thead>
        <tbody>
            <tr>
                <th scope="row" class="table-secundary">1</th>
                <td>João</td>
                <td class="table-sucess">Silva</td>
                <td> joao.silva@example.com</td>
                </tr>
                <tr class="tbale-danger">
                <th scope="row">2</th>
                <td>Maria</td>
                <td>Oliveiro</td>
                <td class="table-warning">maria.oliveira@example.com</td>
                </tr>
                <th scope="row" class="table-info">3</th>
                <td>Pedro</td>
                <td>Santos</td>
                <td>pedro.santos@example.com</td>
                    </tr>
                    <tr>
                        <th scope="row" class="table-light">4</th>
                        <td class="table-dark text-white">Ana</td>
                        <td>Souza</td>
                        <td>ana.souza@example.com</td>
                    </tr>
                    <tr class="table-active">
                        <th scope="row">5</th>
                        <td>José</td>
                        <td class="table-primary>">Ferreira</td>
                        <td>jose.ferreira@example.com </td>
                    </tr>                    
        </tbody>
        </table>
          
    </div>
</body>
</html>