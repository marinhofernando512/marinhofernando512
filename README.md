<html>

<head>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="content">
            <div id="login">
                <form action="" method="post">
                    <h1>Login</h1>
                    <p>
                        <label for="text_nome">Nome: *</label>
                        <input type="text" id="text_nome" required="required">
                    </p>

                    <p>
                        <label for="text_email">e-mail *</label>
                        <input type="text" id="text_email" required="required">
                    </p>

                    <p>
                        <input type="checkbox" name="check_logado" id="check_logado">
                        <label for="">Manter-se logado.</label>
                    </p>

                    <input type="submit" value="Entrar">
                </form>
            </div>
            <div id="cadastro">
                <form action="" method="post">
                    <h1>Cadastrar</h1>
                    <p>
                        <label for="text_login_cad">Login:</label>
                        <input type="text"  name="text_login_cad" id="text_login_cad" required="required">
                    </p>

                    <p>
                        <label for="text_senha_cad">Senha:</label>
                        <input type="text"name="text_senha_cad" id="text_senha_cad"  required="required">
                    </p>

                    <p>
                        <label for="text_email_cad"> password do usuario:</label>
                        <input type="text" name="text_email_cad" id="text_email_cad" required="required">
                    </p>

                    <input type="submit" value="Cadastrar">

                    <a href="http://www.google.com/" target="_blank">google</a>

                </form>
            </div>
        </div>
    </div>
</body>

</html>
