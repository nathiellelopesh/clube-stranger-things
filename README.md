<p align="center">
    <img width="300" src="https://micheleambrosio.github.io/semana-frontend-mundo-invertido/assets/images/banner/logo.svg">
</p>

---

Uma jornada para quem não tem medo do desconhecido. O caminho para o Mundo Invertido é incerto, repleto de obstáculos e perigos. Porém, a recompensa é grande: salvar Hawkings e o mundo todo das garras de Vecna. Você está preparado(a)?

## 💻 Tecnologias

- HTML
- CSS
- JavaScript

## 💬 Descrição

Foi desenvolvido uma página web responsiva onde podemos surfar entre os dois mundos de Stranger Things. O objetivo do programa é de poder inverter os mundos através de um botão, ou seja, o tema da página muda para claro no mundo normal, e escuro no mundo invertido. Além disso, existe uma música de fundo, que é diferente para cada mundo, e será dado play somente quando o usuário interagir com a página ao utilizar o botão para inverter os mundos.

O objetivo futuro será a integração de um banco de dados com o Firebase para validar o formulário de inscrição inserido na página.

Esse projeto foi baseado em uma live da semana front-end da Dio(Digital Innovation One), onde o ponto principal era de desenvolver uma página com tema Stranger Things.

## 🎨 Variáveis do Tema CSS

/*** VARIABLES & THEMES ***/

:root {
  --primary-color: #cf0f0f;
  --primary-color-contrast: #ffffff;
  --field-background-color: #000;
}

.light-theme {
  --page-background: linear-gradient(
    180deg,
    #ffffff 0%,
    #ffffff 65%,
    rgba(255, 255, 255, 0.75) 100%
  );
  --header-background-color: #e3e3e3;
  --highlight-color: #000000;
  --featured-font-family: "Archivo", sans-serif;
  --character-top-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-top-image-color: #ffffff;
  --character-bottom-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-bottom-image-color: #e5e5e5;
  --background-lamp-image: url("../images/backgrounds/lamps.png");
  --footer-background-color: #b5bbbf;
}

.dark-theme {
  --page-background: linear-gradient(
    180deg,
    #050000 0%,
    #130404 65%,
    rgba(19, 1, 1, 0.75) 100%
  );
  --header-background-color: #220f0f;
  --highlight-color: #ffffff;
  --featured-font-family: "Rubik Glitch", sans-serif;
  --character-bottom-image-src: url("../images/characters/kids-on-the-bike.svg");
  --character-bottom-image-color: rgba(255, 255, 255, 0.1);
  --character-top-image-src: url("../images/characters/inverted-world-monster.svg");
  --character-top-image-color: #000;
  --background-lamp-image: url("../images/backgrounds/lamps-inverted.png");
  --footer-background-color: #000;
}
```

## 🔗 Links auxiliares

- [W3C - World Wide Web Consortium](http://w3c.org)
- [WAI - Web Acessibility Initiative](https://www.w3.org/WAI/)
- [WCAG 2](https://www.w3.org/WAI/WCAG21/quickref/)
- [Figma](https://www.figma.com/file/I3Q42CcVUziRN3iMfTrbfb/Stranger-Things?node-id=0%3A1)
- [Demo](https://micheleambrosio.github.io/semana-frontend-mundo-invertido/)

