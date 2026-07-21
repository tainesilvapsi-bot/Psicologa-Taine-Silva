# Psicologa-Taine-Silva
<!DOCTYPE html>
<html lang="pt-BR">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Psicóloga Taine Silva | Psicoterapia Psicanalítica</title>

<meta name="description" content="Psicóloga Taine Silva - Atendimento presencial e online. Psicoterapia para adultos com abordagem psicanalítica.">

<link rel="stylesheet" href="style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<script defer src="script.js"></script>

</head>

<body>

<header>

<nav class="navbar">

<div class="logo">
Psicóloga Taine Silva
</div>

<ul class="menu">

<li><a href="#inicio">Início</a></li>

<li><a href="#sobre">Sobre</a></li>

<li><a href="#especialidades">Especialidades</a></li>

<li><a href="#terapia">Terapia</a></li>

<li><a href="#faq">FAQ</a></li>

<li><a href="#contato">Contato</a></li>

</ul>

<div class="menu-mobile">
☰
</div>

</nav>

</header>

<section id="inicio" class="hero">

<div class="hero-text">

<h1>
Um espaço seguro para cuidar da sua saúde emocional.
</h1>

<p>

A psicoterapia é um caminho para compreender sua história, fortalecer seus recursos internos e construir novas possibilidades.

</p>

<a href="#" class="btn">
Agendar Consulta
</a>

</div>

<div class="hero-img">

<img src="img/psicologa.jpg" alt="Psicóloga">

</div>

</section>

<section id="sobre">

<div class="container">

<h2>Sobre Mim</h2>

<p>

Olá!

Sou <strong>Psicóloga Taine Silva</strong>, atuo com atendimento psicológico para adultos utilizando a abordagem psicanalítica.

Meu compromisso é oferecer um ambiente acolhedor, ético e seguro para o desenvolvimento emocional.

</p>

</div>

</section>

<section id="especialidades">

<div class="container">

<h2>Como posso ajudar</h2>

<div class="cards">

<div class="card">

<h3>Ansiedade</h3>

<p>Compreensão dos sintomas e desenvolvimento de novos recursos emocionais.</p>

</div>

<div class="card">

<h3>Autoestima</h3>

<p>Fortalecimento da identidade e autoconhecimento.</p>

</div>

<div class="card">

<h3>Relacionamentos</h3>

<p>Questões afetivas, familiares e conjugais.</p>

</div>

<div class="card">

<h3>Traumas</h3>

<p>Elaboração psíquica e ressignificação da experiência.</p>

</div>

<div class="card">

<h3>Luto</h3>

<p>Acolhimento durante processos de perda.</p>

</div>

<div class="card">

<h3>Desenvolvimento Pessoal</h3>

<p>Autoconhecimento e crescimento emocional.</p>

</div>

</div>

</div>

</section>

<section id="terapia">

<div class="container">

<h2>Como funciona a terapia?</h2>

<div class="passos">

<div>

<h3>1</h3>

<p>Agendamento da primeira consulta.</p>

</div>

<div>

<h3>2</h3>

<p>Primeiro acolhimento e compreensão da demanda.</p>

</div>

<div>

<h3>3</h3>

<p>Construção do processo terapêutico.</p>

</div>

</div>

</div>

</section>

<section id="faq">

<div class="container">

<h2>Perguntas Frequentes</h2>

<div class="faq">

<button class="accordion">
Como funciona a primeira sessão?
</button>

<div class="panel">

<p>
A primeira sessão é um momento de acolhimento e compreensão da sua demanda.
</p>

</div>

<button class="accordion">
O atendimento é online?
</button>

<div class="panel">

<p>
Sim. Os atendimentos podem ocorrer de forma online ou presencial.
</p>

</div>

<button class="accordion">
Quanto tempo dura a sessão?
</button>

<div class="panel">

<p>
Em média 50 minutos.
</p>

</div>

</div>

</div>

</section>

<section id="contato">

<div class="container">

<h2>Entre em contato</h2>

<form>

<input type="text" placeholder="Nome">

<input type="email" placeholder="E-mail">

<textarea placeholder="Mensagem"></textarea>

<button type="submit">
Enviar
</button>

</form>

</div>

</section>

<footer>

<p>

© 2026 Psicóloga Taine Silva

</p>

</footer>

<a class="whatsapp" href="#">
WhatsApp
</a>

<button id="topo">
↑
</button>

</body>
</html>
/* ===========================
   RESET
=========================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{

    font-family:'Poppins',sans-serif;

    background:#f8f7f5;

    color:#444;

    line-height:1.7;

}

/* ===========================
NAVBAR
=========================== */

header{

    width:100%;

    background:#ffffff;

    position:fixed;

    top:0;

    left:0;

    z-index:999;

    box-shadow:0 3px 10px rgba(0,0,0,.08);

}

.navbar{

    max-width:1200px;

    margin:auto;

    display:flex;

    justify-content:space-between;

    align-items:center;

    padding:18px 25px;

}

.logo{

    font-size:22px;

    font-weight:600;

    color:#6E8B74;

}

.menu{

    display:flex;

    list-style:none;

    gap:35px;

}

.menu a{

    text-decoration:none;

    color:#555;

    transition:.3s;

}

.menu a:hover{

    color:#6E8B74;

}

.menu-mobile{

    display:none;

    font-size:30px;

    cursor:pointer;

}

/* ===========================
HERO
=========================== */

.hero{

    display:flex;

    align-items:center;

    justify-content:space-between;

    max-width:1200px;

    margin:auto;

    padding:150px 30px 80px;

    gap:50px;

}

.hero-text{

    flex:1;

}

.hero h1{

    font-size:48px;

    color:#425648;

    margin-bottom:25px;

}

.hero p{

    font-size:18px;

    margin-bottom:35px;

}

.hero-img{

    flex:1;

    text-align:center;

}

.hero-img img{

    width:100%;

    max-width:450px;

    border-radius:20px;

    box-shadow:0 15px 35px rgba(0,0,0,.15);

}

/* ===========================
BOTÃO
=========================== */

.btn{

    display:inline-block;

    background:#6E8B74;

    color:white;

    text-decoration:none;

    padding:15px 35px;

    border-radius:40px;

    transition:.3s;

}

.btn:hover{

    background:#59705f;

}

/* ===========================
SEÇÕES
=========================== */

section{

    padding:90px 30px;

}

.container{

    max-width:1200px;

    margin:auto;

}

section h2{

    text-align:center;

    color:#6E8B74;

    font-size:36px;

    margin-bottom:50px;

}

/* ===========================
CARDS
=========================== */

.cards{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));

    gap:30px;

}

.card{

    background:white;

    padding:30px;

    border-radius:18px;

    box-shadow:0 10px 25px rgba(0,0,0,.08);

    transition:.3s;

}

.card:hover{

    transform:translateY(-8px);

}

.card h3{

    color:#6E8B74;

    margin-bottom:15px;

}

/* ===========================
PASSOS
=========================== */

.passos{

    display:flex;

    justify-content:space-between;

    gap:25px;

}

.passos div{

    flex:1;

    background:white;

    padding:35px;

    text-align:center;

    border-radius:20px;

}

.passos h3{

    width:60px;

    height:60px;

    margin:auto auto 20px;

    border-radius:50%;

    background:#6E8B74;

    color:white;

    display:flex;

    align-items:center;

    justify-content:center;

}

/* ===========================
FAQ
=========================== */

.accordion{

    width:100%;

    border:none;

    background:#6E8B74;

    color:white;

    padding:20px;

    margin-top:15px;

    text-align:left;

    cursor:pointer;

    border-radius:8px;

    font-size:17px;

}

.panel{

    display:none;

    background:white;

    padding:20px;

}

/* ===========================
FORMULÁRIO
=========================== */

form{

    display:flex;

    flex-direction:column;

    gap:18px;

}

input,
textarea{

    padding:15px;

    border:1px solid #ddd;

    border-radius:8px;

    font-size:16px;

}

textarea{

    resize:none;

    min-height:170px;

}

form button{

    background:#6E8B74;

    color:white;

    border:none;

    padding:16px;

    border-radius:30px;

    cursor:pointer;

    font-size:16px;

}

/* ===========================
FOOTER
=========================== */

footer{

    background:#6E8B74;

    color:white;

    text-align:center;

    padding:30px;

}

/* ===========================
WHATSAPP
=========================== */

.whatsapp{

    position:fixed;

    right:25px;

    bottom:25px;

    background:#25D366;

    color:white;

    text-decoration:none;

    padding:15px 20px;

    border-radius:50px;

    font-weight:600;

    box-shadow:0 8px 20px rgba(0,0,0,.25);

}

/* ===========================
BOTÃO TOPO
=========================== */

#topo{

    position:fixed;

    bottom:95px;

    right:30px;

    width:45px;

    height:45px;

    border:none;

    border-radius:50%;

    background:#6E8B74;

    color:white;

    cursor:pointer;

}

/* ===========================
RESPONSIVO
=========================== */

@media(max-width:900px){

.hero{

flex-direction:column-reverse;

text-align:center;

}

.hero h1{

font-size:36px;

}

.menu{

display:none;

}

.menu-mobile{

display:block;

}

.passos{

flex-direction:column;

}

}
// =========================
// MENU MOBILE
// =========================

const menu = document.querySelector(".menu");
const menuMobile = document.querySelector(".menu-mobile");

menuMobile.addEventListener("click", () => {
    menu.classList.toggle("ativo");
});

// =========================
// FAQ (ACCORDION)
// =========================

const accordions = document.querySelectorAll(".accordion");

accordions.forEach((item) => {

    item.addEventListener("click", () => {

        item.classList.toggle("active");

        const panel = item.nextElementSibling;

        if (panel.style.display === "block") {

            panel.style.display = "none";

        } else {

            panel.style.display = "block";

        }

    });

});

// =========================
// BOTÃO VOLTAR AO TOPO
// =========================

const btnTopo = document.getElementById("topo");

window.addEventListener("scroll", () => {

    if (window.scrollY > 400) {

        btnTopo.style.display = "block";

    } else {

        btnTopo.style.display = "none";

    }

});

btnTopo.addEventListener("click", () => {

    window.scrollTo({

        top: 0,

        behavior: "smooth"

    });

});

// =========================
// ANIMAÇÃO AO ROLAR
// =========================

const elementos = document.querySelectorAll(
    ".card, .passos div, section h2, .hero-text, .hero-img"
);

function revelar() {

    elementos.forEach((el) => {

        const topo = el.getBoundingClientRect().top;

        const alturaTela = window.innerHeight * 0.85;

        if (topo < alturaTela) {

            el.classList.add("mostrar");

        }

    });

}

window.addEventListener("scroll", revelar);

window.addEventListener("load", revelar);

// =========================
// MENU ATIVO
// =========================

const secoes = document.querySelectorAll("section");
const links = document.querySelectorAll(".menu a");

window.addEventListener("scroll", () => {

    let atual = "";

    secoes.forEach((secao) => {

        const topo = secao.offsetTop - 150;

        if (window.scrollY >= topo) {

            atual = secao.getAttribute("id");

        }

    });

    links.forEach((link) => {

        link.classList.remove("ativo");

        if (link.getAttribute("href") === "#" + atual) {

            link.classList.add("ativo");

        }

    });

});

// =========================
// ANO AUTOMÁTICO NO RODAPÉ
// =========================

const footer = document.querySelector("footer p");

if (footer) {

    footer.innerHTML =
        `© ${new Date().getFullYear()} Psicóloga Taine Silva`;

}
