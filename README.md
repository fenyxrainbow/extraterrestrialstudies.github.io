# extraterrestrialstudies.github.io
@import url('https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
}

body {

    font-size: 100%; 

    background: linear-gradient(68.15deg, #000000 16.62%, #524d4d 85.61%)
    

}

.cabecalho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
}

.cabecalho-imagem {

    height: 72px;

}

.cabecalho-menu {
display: flex;
gap: 32px;
}
.cabecalho-menu-item {
    font-family: 'Sarala', sans-serif;
    color:#FFF2e7;
    font-weight: 400
    ;
    font-size: 18px;
}

.conteudo {
margin-bottom: 48px;
    border-top: 0.4px solid #FFF2e7;
}

.conteudo-principal {
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-around;
}
.conteudo-principal-escrito{
display: flex;
flex-direction: column;
gap: 32px;
}
.conteudo-principal-escrito-titulo {
    font-family: 'Righteous', cursive;
font-weight: 400;
font-size: 30px;
color: #FFF2e7;
}

.conteudo-principal-escrito-subtitulo {
font-family: 'Sarala', sans-serif;
font-weight: 400; ;
font-size: 24px;
color: #ffffff;
}
.conteudo-principal-escrito-botao {
background-color: #FFF2e7;
width: 180px;
height: 60px;
border:none;
box-shadow: 4px 5px 4px rgba(0, 0, 0, 0.25);
border-radius: 20px;
font-family:'Sarala', sans-serif ;
font-weight: 400;
font-size: 18px;
color: #000000;
}
.conteudo-principal-escrito-botao:hover{
    background-color: rgba(71, 71, 71, 0.53) ;
}
.conteudo-principal-imagem {
   padding-top: 25px;
    height: 370px;
}

.conteudo-secundario {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;
}
.conteudo-secundario-titulo {
    border-top: 0.4px solid #FFF2e7;
    padding-top: 48px;
    font-family:'Righteous', cursive;
font-weight: 380;
font-size: 24px;
color: #FFF2e7;
margin-bottom: 16px;
}
.conteudo-secundario-paragrafo {
    font-family: 'Sarala',sans-serif;
    font-weight: 280;
    font-size: 18px;
    color: #FFF2e7;
}

.rodape {
    padding: 32px;
    border-top: 0.4px solid #FFF2e7;
}
.rodape-imagem{
    height: 48px;
    display: block;
    margin: 0 auto;
}
