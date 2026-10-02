<h2 align="center">Calculadora Galática</h2>

Uma calculadora científica com temática espacial, desenvolvida utilizando HTML, CSS e JavaScript. O projeto combina funcionalidades matemáticas com uma interface visual inspirada no universo e na tecnologia.

<h2 align="center">Sobre o projeto</h2> 

A Calculadora Galáctica foi desenvolvida como um projeto de estudo para praticar conceitos fundamentais de desenvolvimento web, principalmente:

Estruturação de páginas com HTML;
Estilização e criação de interfaces com CSS;
Manipulação de elementos com JavaScript;
Funções e eventos em JavaScript;
Operações matemáticas;
Organização de uma interface interativa.

A interface possui um fundo estrelado animado e uma calculadora central com elementos visuais inspirados em uma estética futurista/espacial.

Funcionalidades

A calculadora permite realizar:

➕ Adição
➖ Subtração
✖️ Multiplicação
➗ Divisão
% Porcentagem
. Números decimais
⌫ Apagar último caractere
CE Limpar cálculo
= Realizar cálculo
sin Seno
cos Cosseno
tan Tangente
log Logaritmo

As funções científicas utilizam métodos matemáticos disponíveis no JavaScript, como Math.sin(), Math.cos(), Math.tan() e Math.log().

<h2 align="center">Interface</h2>

O projeto utiliza uma identidade visual baseada em:

🌌 Fundo preto com estrelas;
💠 Tons de azul e roxo;
✨ Efeitos de brilho;
🔵 Botões com gradientes;
🖥️ Display digital;
🚀 Estética espacial.

O fundo estrelado utiliza uma textura externa e uma animação CSS para criar o movimento das estrelas.

<h2 align="center">Tecnologias utilizadas</h2> 
Tecnologia	Utilização
HTML5	Estrutura da calculadora
CSS3	Estilização, layout, animações e efeitos visuais
JavaScript	Lógica e funcionamento da calculadora

📂 Estrutura do projeto
calculadora-galactica/
│
└── index.html
└── style.css

O projeto está organizado em um único arquivo HTML, contendo a estrutura, estilos CSS e funcionalidades JavaScript da aplicação.

Abra o arquivo:

index.html

Você também pode utilizar uma extensão como Live Server no VS Code para executar o projeto localmente.

<h2 align="center">Como funciona?</h2> 

Os números e operadores são inseridos diretamente no display através da função inserir().

function inserir(valor) {
    document.calc.display.value += valor;
}

Para realizar o cálculo, o projeto utiliza a função calcular(), que interpreta a expressão inserida e apresenta o resultado no display.

📚 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de praticar desenvolvimento Front-End e compreender melhor a integração entre:

HTML + CSS

Além da lógica de programação, o projeto também trabalha conceitos de design de interface, interação com o usuário e animações CSS.

<h2 align="center">Desenvolvido por: </h2> 

Izadora Rodrigues

Estudante de Engenharia de Software e apaixonada por tecnologia, desenvolvimento, design e criação de soluções digitais.

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
