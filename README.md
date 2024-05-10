<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Medicina nos avanços tecnológicos</title>
<style>
    body {
        background-image: url('medicina.jpg'); /* Imagem de fundo */
        background-size: cover;
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    #container {
        width: 80%;
        margin: 0 auto; /* Centraliza o container */
        text-align: center;
        padding-top: 50px; /* Espaçamento superior */
    }
    h1 {
        font-size: 36px; /* Tamanho da fonte do título */
        color: #333; /* Cor do texto */
    }
    p {
        font-size: 18px; /* Tamanho da fonte do parágrafo */
        color: #666; /* Cor do texto */
        line-height: 1.6; /* Altura da linha */
        margin-bottom: 20px; /* Espaçamento inferior */
    }
    .imagem {
        width: 80%; /* Largura da imagem */
        max-width: 600px; /* Largura máxima */
        height: auto; /* Altura ajustável */
        display: block; /* Centraliza a imagem */
        margin: 0 auto; /* Centraliza a imagem */
        margin-top: 20px; /* Espaçamento superior */
        margin-bottom: 20px; /* Espaçamento inferior */
    }
    .video {
        width: 80%; /* Largura do vídeo */
        max-width: 800px; /* Largura máxima */
        height: auto; /* Altura ajustável */
        display: block; /* Centraliza o vídeo */
        margin: 0 auto; /* Centraliza o vídeo */
        margin-top: 20px; /* Espaçamento superior */
        margin-bottom: 20px; /* Espaçamento inferior */
    }
    .botao {
        background-color: #4CAF50; /* Cor de fundo do botão */
        color: white; /* Cor do texto do botão */
        padding: 15px 25px; /* Espaçamento dentro do botão */
        text-align: center; /* Alinhamento do texto dentro do botão */
        display: inline-block; /* Torna o botão um bloco de nível inline */
        font-size: 16px; /* Tamanho da fonte do botão */
        cursor: pointer; /* Cursor do mouse ao passar pelo botão */
        border: none; /* Remove a borda do botão */
        border-radius: 5px; /* Borda arredondada */
        text-decoration: none; /* Remove sublinhado padrão do link */
        margin-top: 20px; /* Espaçamento superior */
        margin-bottom: 20px; /* Espaçamento inferior */
    }
    .bloco-flutuante {
        width: 300px; /* Largura do bloco flutuante */
        background-color: #f1f1f1; /* Cor de fundo do bloco flutuante */
        padding: 20px; /* Espaçamento dentro do bloco flutuante */
        position: fixed; /* Define o posicionamento fixo */
        top: 50%; /* Alinha o bloco flutuante ao centro verticalmente */
        left: 50%; /* Alinha o bloco flutuante ao centro horizontalmente */
        transform: translate(-50%, -50%); /* Move o bloco flutuante para o centro */
        border-radius: 10px; /* Borda arredondada */
    }
</style>
</head>
<body>
<div id="container">
    <h1>Robótica na Saúde</h1>
    <p>A robótica desempenha um papel importante na área da saúde, trazendo inovações e avanços significativos.</p>
    <img src="robotica_saude.jpg" alt="Robótica na Saúde" class="imagem">
    <p>Robôs cirúrgicos, por exemplo, permitem procedimentos mais precisos e menos invasivos, resultando em tempos de recuperação mais rápidos para os pacientes.</p>
    <div class="video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/NrPZ1W_LmWc" frameborder="0" allowfullscreen></iframe>
    </div>
    <p>Para saber mais sobre como a robótica está revolucionando a saúde, clique no botão abaixo:</p>
    <a href="mais_informacoes.html" class="botao">Mais Informações</a>
</div>

<div class="bloco-flutuante">
    <h2>Newsletter</h2>
    <p>Assine nossa newsletter para receber atualizações sobre robótica na saúde.</p>
    <form>
        <input type="email" placeholder="Digite seu e-mail" style="width: 100%; padding: 10px;">
        <input type="submit" value="Assinar" class="botao" style="width: 100%;">
    </form>
</div>

</body>
</html>
