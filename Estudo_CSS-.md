# 🛠️ _**CSS**_

### _Estudo sobre o **CSS** e suas funções._

Responda as seguintes questões sobre o assunto:

O que é o **CSS**?
_R:_   CSS e uma linguagen de estilização.

Aonde é usado o **CSS**?
_R:_ O **CSS** e usado no desenvolvimento web, para websites, aplicativos mobiles etc. 

Como usar o **CSS**?
_R:_  Ele pode ser usado Inline que é na propria linha a ser estilizada, pode ser usado interno usando a tag ```<style>``` no cabeçalio, ou Externo  em um arquivo separado com a extenção ``.css`` e vinculado ao  html atravez da tag ``<link>``.

**Comandos:**
- **Color**     ```p {
  color: red;
}```  Serve para definir ou alterar a cor do texto de um elemento HTML

- **background-color**   ```body {
  background-color: #f0f0f0;
}
div {
  background-color: #3498db;
  color: white;
  padding: 20px;
}``` Serve para definir a cor de fundo de um elemento HTML

- **font-size** ```p {
  font-size: 16px;
}``` Serve para definir o tamanho do texto de um elemento na página web

- **border** ```.elemento {
  border: 2px solid red;
}``` Serve para criar e estilizar um contorno ao redor de um elemento HTML

- **font-weight** ```p {
  font-weight: normal;
}
strong {
  font-weight: bold;
}``` Serve para definir a espessura, o peso ou a intensidade do traço de um texto  

## Seletores CSS

### *O que são seletores css?*
_R:_  Os **seletores CSS** são padrões ou instruções usados para encontrar e escolher os elementos HTML de uma página web que você deseja estilizar.




### *Quais os principais seletores?*
_R:_ 
- **Seletor de Elemento (ou Tag):** Alvo direto em tags HTML específicas.
    - **Exemplo:** `p { color: gray; }` (afeta todos os parágrafos).
    
    
- **Seletor de Classe:** Alvo em elementos que possuem um atributo `class`. É o mais recomendado para reutilização de código. Começa com ponto `.`.
    
    
	- **Exemplo:** `.card { background: white; }` (afeta todos os elementos com `class="card"`).
- **Seletor de ID:** Alvo em um elemento único com um atributo `id`. Deve ser usado apenas uma vez por página. Começa com `#`.


	- **Exemplo:** `#logo { width: 150px; }` (afeta apenas o elemento com `id="logo"`).

- **Seletor Universal:** Seleciona todos os elementos da página de uma só vez. Representado por `*`.
    - **Exemplo:** `* { box-sizing: border-box; }` (afeta a página inteira).



### *Como Usar estes seletores?*

_R:_ No arquivo HTML, adicione tags e de nome a elas usando class (Para vários elementos) e ID (Para elemento único )
```html
<h1 id="titulo">Olá Mundo</h1>
<p class="texto">Este é um parágrafo.</p>
```

Ai no arquivo css vc chama estes elementos usando as seguintes regras:
- Para TAGS escreva o próprio nome dela Ex : `p`
- Para Classe coloque um ponto antes Ex: `.classe`
- Para Id coloque um hashtag antes Ex: `#id`

Apos isso coloque chaves {} e a propriedade que quer mudar no meio delas, Exemplo:

```css
/* Alvo: tag h1 com id="titulo" */
#titulo {
  color: blue;
}

/* Alvo: tag p com class="texto" */
.texto {
  font-size: 18px;
}
```

### *Widht*
- Define a largura de um elemento na tela
- Exemplo :  ```css
  .botao {
  width: 150px;
}
  ```


