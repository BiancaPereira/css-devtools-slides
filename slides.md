---
theme: ./theme
highlighter: prism
title: Dicas para Debugar o CSS
lineNumbers: true
---

## Debugando <u>CSS</u> com <span class="text-pink-500">DevTools</span>

<div class="justify-center">
  <img src="/assets/icons/oculos-estrelinha.svg" class="h-40 m-10" />
</div>

---

<div class="flex justify-center">
  <img src="/assets/images/eu-gil.png" class="h-30 rounded-1/2 m-5" />
  <img src="/assets/images/gatos.png" class="h-30 rounded-1/2 m-5" />
  <img src="/assets/images/gatos-2.png" class="h-30 rounded-1/2 m-5" />
  <img src="/assets/images/taemin.jpeg" class="h-30 rounded-1/2 m-5" />
  <img src="/assets/images/killua.jpeg" class="h-30 rounded-1/2 m-5" />
</div>

<span class="text-pink-500">**Bianca Pereira**</span>
- <twemoji-laptop /> Sênior frontend developer **@Grupo Boticário**
- <twemoji-books /> Ciências da Computação, MBA em Engenharia de Software
- <twemoji-cat-face /> Mãe de gatos
- <twemoji-cherry-blossom /> Fã de cultura pop asiática
- <twemoji-hot-beverage /> **Líder de comunidade [@Cafeína Vagas](https://t.me/CafeinaVagas) no Telegram**

---

# <span class="text-pink-500">Debugar</span> é a arte de remover os <u>bugs</u> de um sistema

---

### Nosso melhor amigo: o <span class="text-pink-500">Devtools</span>

- **DevTools**: Ferramenta do desenvolvedor
- Pressione <kbd>F12</kbd> ou clique no botão direito do mouse e selecione **Inspecionar**

---

### Explorando o Devtools

1. Aba elementos
2. Aba styles
3. Aba console
4. Aba computed

<p>
  <twemoji-backhand-index-pointing-right />
  <a target="_blank" href="https://codepen.io/BiancaPereira/full/rLKOoE"> Exemplo</a>
</p>


---

## CSS Grid

```css
.wrapper {
  display: grid;
}
```

<p>
  <twemoji-backhand-index-pointing-right />
  <a target="_blank" href="https://codepen.io/BiancaPereira/full/LqzPda"> Exemplo</a>
</p>

---

## CSS Flex

```css
.wrapper {
  display: flex;
}
```

<p>
  <twemoji-backhand-index-pointing-right />
  <a target="_blank" href="https://codepen.io/BiancaPereira/full/MLvwEV"> Exemplo</a>
</p>

---

## Animações e transições

```css
@keyframes nome-animacao {
  from {background-color: red;}
  to {background-color: yellow;}
}

div {
  animation-name: nome-animacao;
  animation-duration: 4s;
}
```

<p>
  <twemoji-backhand-index-pointing-right />
  <a target="_blank" href="https://codepen.io/syedrafeeq/full/QWKvYQ"> Exemplo</a>
</p>

---

## Console.log do CSS

```css
* {
  border: 1px solid red;
}
```

<p>
  <twemoji-backhand-index-pointing-right />
  <a target="_blank" href=""> Exemplo</a>
</p>

---

<h1 class="flex">
  <span class="m-5">Obrigada!</span>
  <img src="/assets/icons/rainha.svg" class="h-30 m-5" />
</h1>

<div class="flex items-center">
  <div>
    <img src="/assets/images/qr-code.svg" class="h-sm m-5" />
  </div>

  <div>
    <strong class="uppercase text-3xl">
      <twemoji-sparkles /> <a href="https://developer.chrome.com/docs/devtools/css/">Referências</a> <twemoji-sparkles />
    </strong>
    <ul class="text-3xl">
      <li>LinkedIn: <a href="https://www.linkedin.com/in/biancacpereira">biancacpereira</a></li>
      <li>Twitter: <a href="https://twitter.com/BiaSailorGeek">@BiaSailorGeek</a></li>
      <li>Instagram: <a href="https://www.instagram.com/biibis_">@biibis_</a></li>
      <li>Github: <a href="https://github/biancapereira">biancapereira</a></li>
    </ul>
  </div>
</div>

> **Comunidade para Iniciantes em TI [@CafeínaVagas](https://t.me/CafeinaVagas) <twemoji-hot-beverage /> no Telegram**
