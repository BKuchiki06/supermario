<!DOCTYPE html>
<html lang="pt-br">

<head>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@300;700&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport"content="width=device-width, initial-scale=1.0">
    <title>Super Mario</title>

</head>

<body>
    
    <div class="video-mario">
        <video src="video.mp4" autoplay muted loop></video>
    <div class="mascara-video"></div>
    </div>
    <div class="caixa-principal">
        <img src="logo.png" alt="logo do super mario" class="logo-mario">
        <p>Encanadores Mario & Luigi - Resolvendo Seus Problemas Com Estilo!</p>
        <p>Você já se encontrou em uma situação de emergência com encanamento? Vazamentos inesperados, canos entupidos ou torneiras que não param de pingar? Não se preocupe, porque estamos aqui para salvar o dial Apresentamos a vocês os encanadores mais famosos do Reino dos Cogumelos - Mario e Luigil</p>
        <button onclick="cliqueiNoBotao()">Fale Conosco</button>
    </div>
    <img src="mario.png" alt="logo mario e luigi" class="logo-mario-luigi">
    <link rel="stylesheet" href="style.css">
    
    <form class="fale-conosco" action="https://formsubmit.co/jomersonrodrigo@gmail.com" method="POST">
        <h1>Fale Conosco</h1>
        <input placeholder="Seu nome" type="text" name="nome">
        <input placeholder="Seu telefone" type="tel" name="telefone">
        <textarea placeholder="Digite aqui seu problema" name="info"></textarea>
        <button onclick="sumirFormulario">Enviar formulário</button>
        
    </form>
    <div class="mascara-form"></div>
</body>

<script>
    
    let formulario = document.querySelector(".fale-conosco")
    let mascara = document.querySelector(".mascara-form")
    
    console.log(formulario)
    
    function cliqueiNoBotao(){
        
        formulario.style.left="900px"
        mascara.style.visibility="visible"
    }
    
    function sumirFormulario(){
        formulario.style.left="-360px"
        mascara.style.visibility="hidden"
    }
    
    
</script>

</html>
