## Nesse estudo iremos abordar sobre html e seus conceitos.

**O que é HTML?**
**R:** É uma Linguagem de marcação assim como o _Markdown_ so que mais robusta,  O HTML é o Esqueleto de uma pagina web toda estrutura de texto links e imagens parte dele.

**Qual a Estrutura?**
**R:** 
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Este é o conteúdo principal do site.</p>
</body>
</html>

```

- `<!DOCTYPE html>`:  Informa ao navegador que a página usa o padrão HTML5.
- `<html>`:  Elemento raiz que engloba todo o conteúdo do site. 
-  O atributo `lang="pt-br"`:  Define o idioma.
- `<head>`: Guarda informações invisíveis para o usuário, como o título da aba e o padrão de caracteres (`utf-8`).
- `<body>`:  Abriga tudo o que aparece na tela, como textos, imagens e links.

**Quais Principais Tags?**
**R:** 

Estrutura Semântica

- `<header>`: Define o topo da página ou de uma seção.
- `<nav>`: Agrupa links de navegação do menu.
- `<main>`: Envolve o conteúdo principal e único da página.
- `<section>`: Agrupa conteúdos relacionados a um mesmo tema.
- `<article>`: Define um conteúdo autônomo, como um post de blog.
- `<aside>`: Conteúdo lateral relacionado ao principal (barras laterais).
- `<footer>`: Define o rodapé da página com direitos autorais e contatos.

Textos e Títulos

- `<h1>` a `<h6>`: Títulos da página, sendo `<h1>` o mais importante.
- `<p>`: Cria um parágrafo de texto.
- `<strong>`: Destaca um texto em **negrito** (importância c強a).
- `<em>`: Destaca um texto em _itálico_ (ênfase).
- `<span>`: Aplica estilos a partes pequenas de um texto.

 Elementos Multimídia e Links

- `<a>`: Cria links para outras páginas (usa o atributo `href`).
- `<img>`: Insere imagens na tela (usa os atributos `src` e `alt`).
- `<audio>`: Reproduz arquivos de som no navegador.
- `<video>`: Reproduz arquivos de vídeo na página.

Listas e Tabelas

- `<ul>`: Cria uma lista não ordenada (com marcadores de bolinha).
- `<ol>`: Cria uma lista ordenada (numerada de 1, 2, 3...).
- `<li>`: Define cada item pertencente a uma lista.
- `<table>`: Cria uma tabela para exibição de dados organizados.

Formulários

- `<form>`: Envolve todos os elementos de um formulário de envio.
- `<input>`: Cria campos de texto, senhas ou botões de seleção.
- `<button>`: Cria um botão clicável na página.
- `<textarea>`: Caixa de texto longa para mensagens ou comentários.

**O que é HTML semântico? **
**R:** HTML semântico é usar as tags com o nome correto daquilo que elas representam. Em vez de usar tags genéricas que não dizem nada sobre o conteúdo, você escolhe tags que informam diretamente ao navegador e ao Google exatamente o que é cada parte da página, como um título, um menu ou um rodapé. Isso serve para que os computadores entendam a função de cada texto ou bloco do seu site de forma automática.

