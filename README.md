<html>

<head>
    <link rel="stylesheet" href="style.css">
    
</head>

<body>

    <form action="">
        <p>

            <label for="Login">Login:</label>
            <input type="text" id="text_login" required="required">

        </p>

        <p>
            <label for="text_senha">Senha:</label>
            <input type="text" id="text_senha" required="required">
        </p>

        <p>
            <label for="email">password do usuario:</label>
            <input type="text" name="email" id="text_email" required="required">
        </p>

        <p>
            <input type="submit" value="Cadastrar">

            <a href="https://www.google.com" target="_blank">google</a>

        </p>



    </form>
</body>

<script>

    alert("Ola Pagina");

</script>


</html>







///////////////


input[type="submit"] {
    width: 100% !important;
    cursor: pointer;
    background: #3d9db3;
    padding: 8px 5px;
    color: #fff;
    font-size: 20px;
    border: 1px solid #fff;
    margin-bottom: 10px;
    text-shadow: 0 1px 1px #333;

    -webkit-border-radius: 5px;
    border-radius: 5px;

    transition: all 0.2s linear;
}

input[type="submit"]:hover {
    background: #4ab3c6;
}
