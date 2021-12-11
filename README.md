# Default Frontend

## Arquivo base para HTML5. 

### Nele tem as meta tags:

- description
- keywords
- author
- meta tags de compartilhamento: Facebook, Whatsapp e instagram, Twitter


```
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

```
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
```
