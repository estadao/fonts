# Fontes Estadão

Famílias tipográficas reservadas para uso exclusivo no site do [Estadão](https://estadao.com.br) e em outros produtos e marcas do **Grupo Estado**.

## Como utilizar

A maneira mais prática de utilizar é através da CDN

https://cdn.jsdelivr.net/gh/estadao/fonts/

Por exemplo, para a **Estado Headline Bold**, adicione isso ao CSS:

```css
@font-face {
  font-family: "Estado Headline";
  font-style: normal;
  font-weight: 700;
  font-display: swap;
  src:
    url(https://cdn.jsdelivr.net/gh/estadao/fonts/Estado/EstadoHeadline/EstadoHeadline-Bold.woff2) format("woff2"),
    url(https://cdn.jsdelivr.net/gh/estadao/fonts/Estado/EstadoHeadline/EstadoHeadline-Bold.woff) format("woff");
}
```

**NOTA:** Omitindo a versão, é usada a mais recente.
