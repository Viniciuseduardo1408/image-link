# Projeto: Imagem com Link Externo 🖼️

Este é um projeto simples para praticar conceitos fundamentais de HTML. O objetivo é exibir uma imagem na página que, ao ser clicada, redireciona o usuário para um site externo.

## 🚀 O que estou aprendendo

Neste projeto, o foco foi aprender a:

* **Estruturar um documento HTML básico:** Utilizando as tags `<!DOCTYPE html>`, `<html>`, `<head>` e `<body>`.
* **Criar um hyperlink:** Usando a tag `<a>` (âncora) com o atributo `href` para definir o URL de destino.
* **Inserir uma imagem:** Usando a tag `<img>` com os atributos `src` (para a fonte da imagem) e `alt` (para acessibilidade).
* **Combinar tags para criar um link em uma imagem:** O conceito principal aqui foi aninhar a tag `<img>` dentro da tag `<a>`. Isso faz com que a imagem se torne o elemento clicável do link.

## 💻 Código Utilizado

O comportamento foi alcançado aninhando a tag de imagem dentro da tag de link, desta forma:

```html
<a href="[https://google.com](https://google.com)">
    <img src="[https://placehold.co/300x200/png](https://placehold.co/300x200/png)" alt="placeholder">
</a>
```

## Como Visualizar

1.  Salve o código como um arquivo `index.html`.
2.  Abra este arquivo em qualquer navegador web.
3.  Você verá uma imagem. Clique nela para ser redirecionado ao Google.
