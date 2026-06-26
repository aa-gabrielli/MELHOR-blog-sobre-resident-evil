```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MELHOR Blog sobre Resident Evil 4!!!!</title>

<link rel="stylesheet" href="style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

</head>

<body>

<header>

<div class="perfil">

<img
class="avatar"
src="https://images.unsplash.com/photo-1496065187959-7f07b8353c55?w=500"
alt="Rosa">

<div>

<h1>@aa.gabriellimelhordetodas</h1>

</div>

</div>

</header>

<h2 class="tituloBlog">
MELHOR Blog sobre Resident Evil 4!!!!
</h2>

<section class="status">

<p><b>Status:</b> apaixonadíssima por Leon Kennedy ❤️</p>

<p><b>Mood:</b> adorando Resident Evil</p>

<p><b>Now Playing:</b> Toxic - Britney Spears 🎵</p>

<button id="musica">
▶ Play / Pause Música
</button>

</section>

<section class="contador">

👁 Visitantes:
<span id="contador">
153724
</span>

</section>

<main>

<section class="introducao">

<h3>Resident Evil 4 (2005)</h3>

<p>

Mds gente... sério!! Resident Evil 4 simplesmente ZEROU a indústria dos games!! 😭💖

Lançado em 2005, esse jogo chegou chegando e fez todo mundo ficar tipo "CARAAAAA QUE JOGO É ESSE??"

A história acompanha Leon S. Kennedy, agora um agente especial, numa missão pra salvar Ashley Graham, filha do presidente dos EUA.

Só que nada é fácil né??

O lugar tá LOTADO de aldeões completamente surtados por causa dos Las Plagas.

Tem motosserra, castelo gigante, monges bizarros, monstros enormes e muito tiro.

Os gráficos eram MUITO perfeitos pra época.

A câmera por cima do ombro virou tendência em praticamente todos os jogos depois.

Sem contar as frases icônicas...

"Where's everyone going? Bingo?"

KKKKKKKKKKK simplesmente CINEMA.

Até hoje o original continua sendo um dos melhores jogos já feitos.

Quem jogou sabe.

Quem não jogou tá perdendo um verdadeiro HINO dos videogames.

Muito emo, muito 2005, muito perfeito.

</p>

</section>

<section class="parteEscura">

<img

class="logo"

src="https://upload.wikimedia.org/wikipedia/commons/4/48/Resident_Evil_4_logo.svg"

alt="Resident Evil 4">

<section class="personagem esquerda">

<img

src="https://static.wikia.nocookie.net/residentevil/images/4/43/LeonSKennedyRE4.png"

alt="Leon">

<div>

<h2>Leon Kennedy</h2>

<p>

O MAIOR de todos.

Bonito.

Perfeito.

Ícone.

Carrega o jogo inteiro nas costas e ainda faz piadinha enquanto derrota monstros gigantes.

Leon simplesmente inventou o conceito de protagonista.

</p>

</div>

</section>

<section class="personagem direita">

<div>

<h2>Ashley Graham</h2>

<p>

Sim, ela grita bastante.

Mas ela também é muito importante pra história.

Ela rende vários momentos engraçados e virou uma personagem extremamente marcante.

LEOOOOON HELPPPPP!!

</p>

</div>

<img

src="https://static.wikia.nocookie.net/residentevil/images/b/b4/Ashley_RE4.png"

alt="Ashley">

</section>

<section class="personagem esquerda">

<img

src="https://static.wikia.nocookie.net/residentevil/images/3/36/Ada_RE4.png"

alt="Ada">

<div>

<h2>Ada Wong</h2>

<p>

Misteriosa.

Elegante.

Linda.

Nunca dá pra saber de que lado ela realmente está.

E justamente por isso ela é tão incrível.

</p>

</div>

</section>

<section class="personagem direita">

<div>

<h2>Luis Serra</h2>

<p>

Luis chega fazendo piadinha o tempo todo.

Ele ajuda Leon diversas vezes e acaba se tornando um dos personagens mais queridos do jogo.

Muito carismático.

</p>

</div>

<img

src="https://static.wikia.nocookie.net/residentevil/images/5/5b/Luis_RE4.png"

alt="Luis">

</section>

<section class="personagem esquerda">

<img

src="https://static.wikia.nocookie.net/residentevil/images/c/c8/WeskerRE4.png"

alt="Wesker">

<div>

<h2>Albert Wesker</h2>

<p>

Mesmo aparecendo pouco, Wesker continua sendo um dos maiores vilões da franquia.

Tudo faz parte dos planos dele.

Icônico demais.

</p>

</div>

</section>

<section class="opiniao">

<h2>Minha opinião sobre a Ashley 💕</h2>

<p>

A Ashley recebe MUITO hate sem motivo.

Ela é literalmente uma garota comum colocada numa situação completamente absurda.

Eu acho ela super fofinha, engraçada e combina demais com o Leon durante a aventura.

Protegê-la faz parte da experiência do jogo.

Ashley merece muito mais carinho dos fãs!!

</p>

</section>

<section class="interacoes">

<button id="like">
❤️ Like
</button>

<button id="deslike">
🖤 Dislike
</button>

<button id="comentar">
💬 Comentar
</button>

</section>

<footer>

<h1>

OBRIGADA POR LER MEU BLOG!!!
<br><br>

XOXO ( ˘ ³˘)♥︎

</h1>

</footer>

</section>

</main>

<audio id="bgm" loop>

<source src="music/re4.mp3" type="audio/mpeg">

</audio>

<script src="script.js"></script>

</body>
</html>

```css
/* =====================================================
   RESET
===================================================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#ffffff;
    color:#222;
    font-family:"Press Start 2P",cursive;
    line-height:2;
    overflow-x:hidden;
    cursor:url("cursor.cur"),auto;
}

/* =====================================================
   SCROLLBAR
===================================================== */

::-webkit-scrollbar{
    width:12px;
}

::-webkit-scrollbar-track{
    background:#111;
}

::-webkit-scrollbar-thumb{
    background:#850000;
    border-radius:10px;
}

::-webkit-scrollbar-thumb:hover{
    background:#c00000;
}

/* =====================================================
   HEADER
===================================================== */

header{
    width:100%;
    display:flex;
    justify-content:center;
    margin-top:40px;
}

.perfil{

    width:90%;
    max-width:1000px;

    background:#FFCCDD;

    border:3px solid #FFB6CF;

    padding:25px;

    border-radius:20px;

    display:flex;

    align-items:center;

    box-shadow:0px 0px 20px rgba(255,182,207,.4);

}

.avatar{

    width:120px;
    height:120px;

    border-radius:50%;

    object-fit:cover;

    border:4px solid white;

    margin-right:25px;

}

.perfil h1{

    font-size:14px;

    color:#6d0037;

    text-shadow:2px 2px white;

}

/* =====================================================
   TÍTULO
===================================================== */

.tituloBlog{

    text-align:center;

    margin-top:35px;

    margin-bottom:35px;

    font-size:20px;

    color:#ff78a7;

    text-shadow:3px 3px white;

}

/* =====================================================
   STATUS
===================================================== */

.status{

    width:90%;
    max-width:900px;

    margin:auto;

    background:white;

    border:3px dashed #ffb6cf;

    padding:25px;

    border-radius:18px;

    margin-bottom:30px;

}

.status p{

    margin-bottom:15px;

    font-size:11px;

}

#musica{

    margin-top:15px;

    padding:12px 25px;

    background:#111;

    color:white;

    border:none;

    border-radius:12px;

    font-family:inherit;

    cursor:pointer;

    transition:.3s;

}

#musica:hover{

    background:#900000;

    transform:scale(1.05);

}

/* =====================================================
   CONTADOR
===================================================== */

.contador{

    width:300px;

    margin:35px auto;

    text-align:center;

    background:#efefef;

    border:2px solid #999;

    padding:15px;

    border-radius:10px;

    font-size:11px;

    box-shadow:5px 5px #ddd;

}

#contador{

    color:#9b0000;

}

/* =====================================================
   INTRODUÇÃO
===================================================== */

.introducao{

    width:90%;
    max-width:1100px;

    margin:auto;

    margin-bottom:80px;

    background:white;

    padding:35px;

    border-radius:20px;

    border:3px solid #ececec;

}

.introducao h3{

    color:#ff79a8;

    margin-bottom:30px;

    text-align:center;

    font-size:18px;

}

.introducao p{

    font-size:11px;

    text-align:justify;

}

/* =====================================================
   PARTE ESCURA
===================================================== */

.parteEscura{

    background:#04050B;

    color:white;

    margin-top:80px;

    padding-top:70px;

    padding-bottom:100px;

}

.logo{

    display:block;

    margin:auto;

    width:450px;

    max-width:90%;

    margin-bottom:80px;

}
=====================================================
   PERSONAGENS
===================================================== */

.personagem{

    width:90%;
    max-width:1200px;

    margin:80px auto;

    display:flex;

    align-items:center;

    justify-content:space-between;

    gap:50px;

}

.personagem img{

    width:320px;

    max-width:100%;

    border:6px solid #8B0000;

    border-radius:15px;

    box-shadow:0 0 25px rgba(139,0,0,.8);

    transition:.4s;

}

.personagem img:hover{

    transform:scale(1.05);

    box-shadow:0 0 40px rgba(255,0,0,.9);

}

.personagem div{

    flex:1;

}

.personagem h2{

    color:#a30000;

    margin-bottom:30px;

    font-size:20px;

    text-shadow:2px 2px black;

}

.personagem p{

    font-size:11px;

    text-align:justify;

    line-height:2.2;

}

/* =====================================================
   ALTERNÂNCIA DAS SEÇÕES
===================================================== */

.esquerda{

    flex-direction:row;

}

.direita{

    flex-direction:row-reverse;

}

/* =====================================================
   OPINIÃO SOBRE A ASHLEY
===================================================== */

.opiniao{

    width:90%;
    max-width:1000px;

    margin:100px auto;

    background:#111;

    border:4px solid #8B0000;

    border-radius:18px;

    padding:35px;

    box-shadow:0 0 30px rgba(139,0,0,.5);

}

.opiniao h2{

    color:#b00000;

    text-align:center;

    margin-bottom:35px;

    font-size:20px;

}

.opiniao p{

    font-size:11px;

    line-height:2.2;

    text-align:justify;

}

/* =====================================================
   BOTÕES
===================================================== */

.interacoes{

    display:flex;

    justify-content:center;

    gap:25px;

    flex-wrap:wrap;

    margin-top:70px;

    margin-bottom:70px;

}

.interacoes button{

    font-family:inherit;

    font-size:11px;

    padding:15px 28px;

    border:none;

    border-radius:12px;

    cursor:pointer;

    transition:.3s;

    color:white;

}

#like{

    background:#8B0000;

}

#deslike{

    background:#2c2c2c;

}

#comentar{

    background:#5d5d5d;

}

#like:hover{

    background:#c40000;

    transform:translateY(-4px);

}

#deslike:hover{

    background:#555;

    transform:translateY(-4px);

}

#comentar:hover{

    background:#7d7d7d;

    transform:translateY(-4px);

}

/* =====================================================
   FOOTER
===================================================== */

footer{

    margin-top:100px;

    text-align:center;

    padding:60px;

}

footer h1{

    color:white;

    font-size:28px;

    line-height:2;

    text-shadow:

    0 0 8px red,

    0 0 18px crimson,

    3px 3px black;

}

=====================================================
   ANIMAÇÕES
===================================================== */

@keyframes piscar{

    0%{
        opacity:1;
    }

    50%{
        opacity:.55;
    }

    100%{
        opacity:1;
    }

}

@keyframes flutuar{

    0%{
        transform:translateY(0px);
    }

    50%{
        transform:translateY(-6px);
    }

    100%{
        transform:translateY(0px);
    }

}

@keyframes brilho{

    0%{
        box-shadow:0 0 10px rgba(255,0,0,.2);
    }

    50%{
        box-shadow:0 0 30px rgba(255,0,0,.8);
    }

    100%{
        box-shadow:0 0 10px rgba(255,0,0,.2);
    }

}

.avatar{

    animation:flutuar 3s ease-in-out infinite;

}

.logo{

    animation:piscar 4s infinite;

}

.personagem img{

    animation:brilho 2.5s infinite;

}

/* =====================================================
   CURSOR PERSONALIZADO
===================================================== */

body{

    cursor:url("cursor.cur"), auto;

}

button{

    cursor:pointer;

}

/* =====================================================
   SELEÇÃO DE TEXTO
===================================================== */

::selection{

    background:#8B0000;

    color:white;

}

/* =====================================================
   LINKS
===================================================== */

a{

    color:#ff6f91;

    text-decoration:none;

    transition:.3s;

}

a:hover{

    color:#ffffff;

    text-shadow:0 0 10px crimson;

}

/* =====================================================
   DECORAÇÕES ESTILO TUMBLR/MSN
===================================================== */

.tituloBlog{

    animation:piscar 3s infinite;

}

.status{

    animation:flutuar 4s ease-in-out infinite;

}

.contador{

    animation:flutuar 5s ease-in-out infinite;

}

/* =====================================================
   RESPONSIVIDADE
===================================================== */

@media(max-width:900px){

    .perfil{

        flex-direction:column;

        text-align:center;

    }

    .avatar{

        margin-right:0;

        margin-bottom:20px;

    }

    .personagem{

        flex-direction:column !important;

        text-align:center;

    }

    .personagem img{

        width:260px;

    }

    .personagem h2{

        margin-top:20px;

    }

    .logo{

        width:320px;

    }

    footer h1{

        font-size:18px;

    }

}

@media(max-width:600px){

    .tituloBlog{

        font-size:15px;

        line-height:1.8;

    }

    .perfil h1{

        font-size:10px;

    }

    .status{

        font-size:9px;

    }

    .contador{

        width:90%;

    }

    .introducao,
    .opiniao{

        padding:20px;

    }

    .personagem h2{

        font-size:15px;

    }

    .personagem p{

        font-size:10px;

    }

    .interacoes{

        gap:12px;

    }

    .interacoes button{

        width:90%;

    }

}

/* =====================================================
   EFEITOS FINAIS
===================================================== */

body{

    background-image:
    radial-gradient(circle at top left, rgba(255,182,193,.12), transparent 40%),
    radial-gradient(circle at bottom right, rgba(255,0,0,.05), transparent 35%);

}

footer h1{

    animation:piscar 2s infinite;

}

button:active{

    transform:scale(.95);

}

img{

    user-select:none;

    -webkit-user-drag:none;

}

main{

    padding-bottom:60px;

}

```javascript
const musica = document.getElementById("musica");
const audio = document.getElementById("bgm");

let tocando = false;

musica.addEventListener("click", () => {

    if (!tocando) {

        audio.play();
        musica.innerHTML = "⏸ Pause Música";
        tocando = true;

    } else {

        audio.pause();
        musica.innerHTML = "▶ Play Música";
        tocando = false;

    }

});

/* ===========================
   BOTÃO LIKE
=========================== */

let likes = 0;

const like = document.getElementById("like");

like.addEventListener("click", () => {

    likes++;

    like.innerHTML = `❤️ Like (${likes})`;

});

/* ===========================
   BOTÃO DISLIKE
=========================== */

let dislikes = 0;

const dislike = document.getElementById("deslike");

dislike.addEventListener("click", () => {

    dislikes++;

    dislike.innerHTML = `🖤 Dislike (${dislikes})`;

});

/* ===========================
   BOTÃO COMENTAR
=========================== */

const comentar = document.getElementById("comentar");

comentar.addEventListener("click", () => {

    const comentario = prompt("Escreva seu comentário:");

    if (comentario && comentario.trim() !== "") {

        alert("Obrigada pelo comentário!! 💖");

    }

});

/* ===========================
   CONTADOR FAKE
=========================== */

const contador = document.getElementById("contador");

let visitas = 153724;

setInterval(() => {

    visitas += Math.floor(Math.random() * 3);

    contador.innerHTML = visitas.toLocaleString("pt-BR");

}, 3500);

/* ===========================
   BRILHO NOS BOTÕES
=========================== */

const botoes = document.querySelectorAll("button");

botoes.forEach(botao => {

    botao.addEventListener("mouseenter", () => {

        botao.style.boxShadow = "0 0 20px crimson";

    });

    botao.addEventListener("mouseleave", () => {

        botao.style.boxShadow = "none";

    });

});

/* ===========================
   TÍTULO PISCANDO
=========================== */

const titulo = document.querySelector(".tituloBlog");

let alterna = true;

setInterval(() => {

    titulo.style.opacity = alterna ? "0.6" : "1";

    alterna = !alterna;

}, 900);

/* ===========================
   EFEITO DE ENTRADA
=========================== */

window.addEventListener("load", () => {

    document.body.style.opacity = "0";

    document.body.style.transition = "opacity 1.2s";

    setTimeout(() => {

        document.body.style.opacity = "1";

    }, 100);

});

/* ===========================
   MENSAGEM DE BOAS-VINDAS
=========================== */

setTimeout(() => {

    alert("Bem-vinda ao MELHOR Blog sobre Resident Evil 4!!!! 💖");

}, 700);
```

