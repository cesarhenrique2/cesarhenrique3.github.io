<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CRUD em PHP - Exercício</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous"></script>
</head>

<body>

<?php
    $pdo = new PDO('mysql:host=localhost;dbname=aulaprogweb','root',"");
    $pdo->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);


    if(isset($_POST['nome'])){
        $sql = $pdo->prepare("INSERT INTO tab_clientes VALUES(null, ?,?,?)");
        $sql->execute(array($_POST['nome'], $_POST['cpf'], $_POST['email']));
        echo "Cadastro realizado com Sucesso";}
    
    if(isset($_GET['delete'])){
            $cod_cliente = (int)$_GET['delete'];
            $pdo->exec("DELETE FROM tab_clientes WHERE cod_cliente=$cod_cliente");
            echo "Cliente excluído com Sucesso";
        }
    

    ?>

    <div>
    <form method="POST">
            <legend><h3 class="form-group d-flex justify-content-center">Cadastro de clientes - Insira os dados abaixo</h3></legend>
            <fieldset>
                <div>
                    Nome: <input type="text" name="nome" class="form-control">

                </div>

                <div>
                    CPF: <input type="text" name="cpf" class="form-control">

                </div>

                <div>
                    E-mail: <input type="text" name="email" class="form-control">

                </div>

                <br>
                <button type="submit" class='btn btn-primary' >Enviar</button>
                <a href="index.php">Limpar dados</a></button>
                <a href="index.php">Home</a></button>

                </fieldset>

            </form>
    </div>
    
    <?php

      $sql= $pdo->prepare("SELECT * FROM tab_clientes");
      $sql->execute();

      $fetchClientes = $sql->fetchAll();

      foreach ($fetchClientes as $key => $value){
        echo ''.$value['nome'].'|'.$value['cpf'].'|'.$value['email'].'<button onclick=\></button><a href="?delete='.$valu['cod_cliente'].'">(Excluir Cliente)</a>'."<a href='alterar.php'>Alterar</a>";}

       
    ?>

    
</body>
</html>