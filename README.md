# SINGLE PRICE GRID COMPONENT MASTER

Esta é uma solução para o [desafio no Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Índice

- [Visão geral](#visão geral)
  - [O desafio](#the-challenge)
  - [Captura de tela](#captura de tela)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído com)
  - [O que aprendi](#o-que-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento contínuo)
  - [Recursos úteis](#useful-resources)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)

## Visão geral

Este projeto mostra habilidades com uso de CSS3 para estilização de HTML5, seguindo a referencia por imagem e também o padrão de cores e tamanhos fornecidos juntos no pacote de inicio do projeto

### O desafio

Os usuários devem ser capazes de:

- Visualize o layout ideal para o componente, dependendo do tamanho da tela do dispositivo
- Veja um estado de foco na área de trabalho para a call-to-action Sign Up

### Captura de tela

![Desktop](/assets/design/exemplo.png)
![Mobile](/assets/design/exemplo%202.png)

### Links

- URL do site ao vivo: (<https://single-price-grid-component-master-omega-ivory.vercel.app/>)

## Meu processo

Demorei cerca de 5h de trabalho para concluir o desafio.

### Construído com

- HTML5
- Propriedades personalizadas de CSS
- Flexbox
- Grid CSS
- Fluxo de trabalho mobile-first

### O que eu aprendi

Ganhei mais segurança com detecção de estilos apartir de imagens de design. Melhorei minha habilidade com uso de grid e posicionamento de texto.

Para ver como você pode adicionar snippets de código, veja abaixo:

```CSS
 .main{
    display: grid;
    grid-template-areas: "A A" "B C";
    width: 700px;
    margin: 200px auto 40px auto;
   }
   .principal{
    grid-area: A;
   }
   .promocao{
    grid-area: B;
   }
   .sobre_nos{
    grid-area: C;
   }
```

### Desenvolvimento contínuo

Para o futuro vou refinar a tecnica de uso do CSS para otimizar a responsividade. Focar mais em atributos de foco para telas mobile.

### Recursos úteis

- [Cheatsheet - CSS](https://htmlcheatsheet.com/css/) - Essa ferramenta me ajudou muito a chegar so tom certo de sombreamento e a posição que mais se aproximou ao do exemplo. Vou utilizá-lo ainda por bastante tempo.

## Autor

- URL no front mentor: (<https://www.frontendmentor.io/profile/KatyaPalheta>)
- Linkedin:
(www.linkedin.com/in/katyapalheta)

## Agradecimentos

Agradeço a Alura, escola de programação, por ter sido minha fonte de conhecimento e minha amiga na trajetória de crescimento pessoal. Aos membros da comunidade Code, mentoria que está moldando minha mente para o mercado de trabalho. Especial agradecimento ao Monitor Jean (Meira#0542), que me orientou na construção desse Readme.
