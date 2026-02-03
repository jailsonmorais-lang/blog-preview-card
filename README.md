# Frontend Mentor - Blog Preview Card

Esta é uma solução para o desafio [Blog preview card do Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01I_L). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Sumário

- [Visão Geral](#visão-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que aprendi](#o-que-aprendi)
- [Autor](#autor)

## Visão Geral

### O desafio

Os usuários devem ser capazes de:
- Visualizar estados de hover e foco para todos os elementos interativos da página (como o título do card).
- Ver o layout otimizado dependendo do tamanho da tela do dispositivo.

### Screenshot

![Screenshot do Projeto](https://jailsonmorais-lang.github.io/blog-preview-card/preview.jpg)

### Links

- Site oficial (Github Pages): [Acesse aqui](https://jailsonmorais-lang.github.io/blog-preview-card/)

## Meu processo

### Tecnologias utilizadas

- Tags HTML5 semânticas
- Propriedades personalizadas de CSS (Variáveis)
- CSS Grid
- Flexbox
- Mobile-first workflow

### O que aprendi

Neste projeto, foquei em refinar o uso de **CSS Grid** para centralização e o uso de **Box Shadow** sólido para criar o estilo visual conhecido como *Neo-brutalismo*. 

Aprendi a manipular sombras sem desfoque para criar profundidade mantendo as bordas nítidas, conforme o código abaixo:

```css
.container {
    border: 1px solid var(--Gray-950);
    box-shadow: 8px 8px 8px 5px var(--Gray-950);
}
