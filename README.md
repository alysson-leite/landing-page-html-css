## Tabela do conteúdo

- [Visão geral](#visao-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
  - [Feito com](#feito-com)
  - [O que Eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-continuo)
- [Autor](#autor)
- [Agradecimentos](#agradecimentos)



## Visão geral

### O desafio

Usuários deve ser capaz de:

- Ver o layout ideal para a página, dependendo do tamanho de tela dos dispositivos
- Ver estados de hover, ao passar o mouse, para todos os elementos interativos da página


### Screenshot

![](./screenshot-landing-page.png)


### Feito com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### O que eu aprendi

Recapitulei e aprendi melhor a colocar ícones que funcionam como fontes (do font-awesome por exemplo), que são muito úteis em geral. Aprendi melhor a utilizar o display grid e flex para organizar o template do site em geral. Também aprendi a usar o hover para estilizar menus ou botões quando o mouse passa em cima. E aprendi também a utilizar fontes do google no projeto.

```html
<div class="social">
               <a href="">
                    <i class="fab fa-facebook-square"></i>
</div>
```
```css
body {
     display: grid;
     grid-template-areas: "header header"
          "image info"
          "footer footer";
     grid-template-columns: repeat(2, 1fr);
}

.info a:hover {
     background-color: hsl(300, 69%, 71%);
     color: #fff;
}

.footer {
     grid-area: footer;
     display: flex;
     flex-direction: column;
}
```


### Desenvolvimento contínuo

Pretendo continuar focando em praticar projetos do mundo real para fixar melhor as principais tags de html e css, para em seguida aprender Javascript e continuar minha jornada de aprendizado como Dev.


## Autor

- Frontend Mentor - [@alysson-leite](https://www.frontendmentor.io/profile/alysson-leite)


## Agradecimentos

Agradecer ao pessoal do Dev em Dobro por ter lançado o desafio e sempre solícitos tirando dúvidas. Obrigado.
