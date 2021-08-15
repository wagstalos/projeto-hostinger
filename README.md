

<h1 align="center"># Projeto hostinger </h1>

<h1 align="center">
    <a href="https://wagstalos.github.io/projeto-hostinger/">🔗 link  do projeto</a>
</h1>

## Descrição do Projeto

<p align="center">Olá, sou Wagner Paulo, profissional da área Desenvolvimento Web e Games, formado em Design Gráfico (UNIP) e Desenvolvimento Jogos Digitais(ETEC). Apaixonado por tecnologias, trabalho com produção de sites, aplicativos, PWA e jogos digitais com foco para o ensino EaD, neste projeto eu criei um site simples.</p>

<h1 align="center">
<img src="https://img.shields.io/static/v1?label=Site&message=SASS&color=3498db&style=for-the-badge&logo="/>
<img src="https://img.shields.io/static/v1?label=Status&message=Andamento&color=f1c40f&style=for-the-badge&logo="/>
</h1>

### Features

- [x] Treinar SASS
- [x] Site sem framework

Para rodar você precisa usar

#Sass

//importando para o main.scss
um arquivo SASS com _ na frente exemplo (_variables.scss )
@import 'variables';


// encadeamentos
.s-hero{
    button{
        background-color:black;
        &.active{
            background-color: red;
            color: black;
        }
        &:hover{
            background-color: yellow;
        }

    }
}

@mixin style-button{
width: 75px;
padding: 0 15px
color: #fff;
}

button{
@include style-button
}

@mixin style-btn($largura){
    width: $largura;
    height: 100px;
    background-color: pink;
    color: black;
    font-weight: bold;
    font-size: 2rem;
    border-radius: 5px;
}

.first-section{
    .btn{
        @include style-btn(350px);
    }
}

As seguintes ferramentas foram usadas na construção do projeto:

- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [SASS](https://sass-lang.com/)

Feito com ❤️ por Wagner Paulo 👋🏽
Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Wagner-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/wagner-silva-6a163555/)](https://www.linkedin.com/in/wagner-silva-6a163555/)
[![Gmail Badge](https://img.shields.io/badge/-wagstalos@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:wagstalos@gmail.com)](mailto:wagstalos@gmail.com)

</div>
