CSS
body{
    margin: 0;
}


#header{
    background-color:black;
    height: 10vh;
    width: 110vw;
    display: flex;
    justify-content: space-around;
    font-size: small;
    color: orange;
}

.H1{
    color:white ;
}

#tela{
    background-color: white;
    height: 90vh;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
    content: '';
    position: fixed;
    width: 100vw;
    height: 100vh;
    background-image: url(IMAGENS/Foto_Fluxo.png);
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    -webkit-background-size:cover;
    background-size: cover;
}

#entar {
    background-color: orange;
    color: white;
    border-radius: 8px;
}

#precapa{
    height: 600px;
    width: 900px;
    margin:auto 0;
    size: 10%;
    background-position: left center;

}
#input{
    width: 400px;
    height: 45px;
}

#formulario{
    background-color: orange;
    height: 60vh;
    width: 45vw;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 8px;
    background-color: transparent;
    color: white;
}

.pergunta{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 30px;
}

JAVA SCRIPT

function alertalogin() {
    return alert("Usuário logado com sucesso!")
}

HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FLUXO</title>
    <link rel="stylesheet" href="styles.css"></link>
</head>
<body>
    <div id="header">
        <img id="logo" src="IMAGENS/logoFluxo.png"/>
       <H1>FLUXOSOCIAL</H1>
       <h2>It's happening now!</h2>
    </div>
    <div id="tela">
        <div class="background"></div>
        <img id="precapa" src="IMAGENS/Pré-Capa.png"/>
        <form id="formulario"> Email
            <label class="pergunta">
                <input class="caixaPergunta" style="border-radius: 8px;height:30px;width:300px;"/> 
            </label>

            <label class="pergunta"> Senha
                <input class="caixaPergunta" style="border-radius: 8px;height: 30px;width: 300px;"/>
                <ahref="#">esqueceu sua senha?</a>
            </label>
            <button id="botaologin" onclick=" alertalogin()" style="height: 30px; width: 300px; background-color: orange;">Logar</button>
            <button id="Apple" style="border-radius: 8px;">Entrar com Apple</button>
            <button style="border-radius: 8px;">Login com Google</button>
        </form>
    </div>
</body>
</html>
