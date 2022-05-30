# Default Frontend

## Arquivo base para HTML5. 

### Nele tem as meta tags:

- description
- keywords
- author
- meta tags de compartilhamento: Facebook, Whatsapp e instagram, Twitter


```HTML
  <meta name="description" content="">
  <meta name="keywords" content="">
  <meta name="author" content="João Victor Oliveira Pereira, github: @joaoquinto">
  
  <!-- Meta tags de compartilhamento -->
  <!-- Metatag Facebook, Whatsapp e instagram -->
  <meta property="og:url" content="" />
  <meta property="og:type" content="website" />
  <meta property="og:title" content="" />
  <meta property="og:description" content="" />
  <meta property="og:image" content="" />
  
  <!-- Metatag Twitter -->
  <meta name="twitter:title" content="">
  <meta name="twitter:description" content="">
  <meta name="twitter:image" content="">
```

### Arquivo base para CSS3

- É feito o reset de quase todos os estilos padrões

```CSS
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  display: block;
  max-width: 100%;
}

ul,
li {
  list-style: none;
}

a {
  text-decoration: none;
}

@font-face {
  font-family: ;
  src: url();
  font-style: ;
  font-weight: ;
  /* Faz rederizar a fonte padrão do computador em vez da fonte declarada e impede do texto ficar invisível,
     Isso ocorre quando a internet do usuário está lenta;\*
  font-display: swap;
}

:root {

}
```

### Arquivo base para Stylus

```stylus
*
  margin: 0
  padding: 0


img
    display: block
    max-width 100%

ul
  li
    list-style none

a
  text-decoration: none
```


