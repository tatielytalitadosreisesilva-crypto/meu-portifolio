# Relatório – Meu Portfólio

## 1. Introdução

O projeto desenvolvido foi um site de portfólio pessoal com o objetivo de apresentar um pouco sobre mim, minha formação e alguns dos projetos que já desenvolvi durante o curso Técnico em Informática para Internet.

O site foi desenvolvido utilizando principalmente **HTML5 e CSS3**. O repositório foi organizado no GitHub e possui os arquivos `index.html`, `projetos.html` e `style.css`.

---

## 2. Matérias e conteúdos utilizados

Durante o desenvolvimento do portfólio, foram utilizados conhecimentos de diferentes conteúdos trabalhados no curso.

### Desenvolvimento Web / Linguagem de Marcação

Foi utilizado **HTML5** para criar toda a estrutura das páginas. Com HTML foram criados títulos, textos, menus, seções, cartões, imagens, links e rodapé.

Também foram utilizados elementos como:

- `<header>` para o cabeçalho;
- `<nav>` para o menu de navegação;
- `<main>` para o conteúdo principal;
- `<section>` para separar as partes da página;
- `<h1>`, `<h2>` e `<h3>` para títulos;
- `<p>` para textos;
- `<div>` para organizar os elementos;
- `<img>` para colocar imagens dos projetos;
- `<a>` para criar os links entre as páginas;
- `<footer>` para o rodapé.

No `index.html`, por exemplo, o menu possui links para a página inicial e para a página de projetos.

### CSS / Estilização

O **CSS** foi utilizado para deixar o site organizado e visualmente agradável.

Foram trabalhados conceitos como:

- cores;
- fontes;
- tamanhos;
- margens e espaçamentos;
- bordas;
- cartões;
- posicionamento;
- `display`;
- efeitos ao passar o mouse;
- cabeçalho fixo;
- organização dos elementos na página.

O site utiliza principalmente tons de rosa, como `#e91e63`, `#f06292` e `#fff7fa`.

Também foi utilizado `display: inline-block` para organizar os cartões das habilidades e os projetos lado a lado.

### Git e GitHub

O **GitHub** foi utilizado para armazenar e organizar o código do projeto. O repositório é público e contém os arquivos necessários para o funcionamento do site.

Isso também permite acompanhar as alterações feitas no projeto e manter uma versão online do código.

---

## 3. Uso de Inteligência Artificial

A **Inteligência Artificial** foi utilizada como uma ferramenta de apoio durante o desenvolvimento do projeto, principalmente para obter ideias de organização visual, textos e escolha dos elementos que poderiam ser utilizados no portfólio.

Nos cartões da página inicial foram utilizados ícones para representar as áreas apresentadas:

- 🎓 para representar estudante;
- 💻 para representar desenvolvimento web;
- 🎨 para representar design.

No código, esses ícones aparecem como emojis dentro de uma `<div>` com a classe `icone`. Portanto, eles não são imagens externas nem uma biblioteca de ícones: são caracteres/emoji inseridos diretamente no HTML.

A IA foi utilizada como apoio, mas o código precisou ser organizado e adaptado para funcionar de acordo com o projeto.

---

## 4. Explicação do código HTML

O arquivo `index.html` é a página inicial do portfólio.

Primeiro é definida a estrutura básica do documento:

```html
<!DOCTYPE html>
```

Essa declaração informa que o documento utiliza HTML5.

Depois aparece:

```html
<html lang="pt-br">
```

que define o idioma da página como português do Brasil.

Dentro do `<head>` são colocadas informações da página, como a codificação dos caracteres, a configuração para diferentes tamanhos de tela e o título.

Também existe:

```html
<link rel="stylesheet" href="style.css">
```

Essa linha conecta o HTML ao arquivo CSS, fazendo com que os estilos criados no `style.css` sejam aplicados à página.

---

## 5. Cabeçalho e menu

No `<header>` foi criado o menu de navegação.

O nome **Tatiely Reis** funciona como uma espécie de logo e existem links para:

- Início;
- Projetos.

Os links são feitos utilizando a tag `<a>`, por exemplo:

```html
<a href="projetos.html">Projetos</a>
```

Quando o usuário clica em "Projetos", o navegador abre a página `projetos.html`.

---

## 6. Apresentação

Na página inicial existe uma seção chamada `apresentacao`.

Nela foi colocado um título de apresentação e dois parágrafos explicando que estou aprendendo Desenvolvimento Web e que o site serve para apresentar meus projetos.

Essa parte foi estilizada no CSS com fundo rosa, texto branco, centralização e espaçamento.

---

## 7. Cards de habilidades

A seção "Sobre Mim" possui três cartões:

- **Estudante:** mostra que estou cursando Técnico em Informática para Internet.
- **Desenvolvedora Web:** mostra que estou aprendendo HTML e CSS com foco em front-end.
- **Design:** apresenta meu interesse pela criação de interfaces bonitas e funcionais.

Cada cartão possui um ícone, título e texto.

No CSS, a classe `.card` define características como largura, altura mínima, margem, preenchimento, fundo branco, borda e bordas arredondadas.

---

## 8. Página de projetos

A segunda página do site é o `projetos.html`.

Nela são apresentados alguns projetos desenvolvidos durante o curso:

- Formulário;
- Centro Arte Cultura;
- Metodiza;
- Portfólio.

Cada projeto possui uma imagem, um título e uma pequena descrição.

As imagens são adicionadas utilizando a tag `<img>` e o atributo `src` indica o caminho da imagem.

Por exemplo:

```html
<img src="imagens/formulario.png">
```

Isso informa ao navegador onde está localizada a imagem que deve aparecer no site.

---

## 9. Explicação do CSS

O arquivo `style.css` é responsável por toda a aparência do site.

Primeiramente foi utilizado:

```css
* {
    box-sizing: border-box;
}
```

Essa configuração facilita o controle do tamanho dos elementos.

Também foi utilizado:

```css
html {
    scroll-behavior: smooth;
}
```

para deixar a movimentação da página mais suave quando são utilizados links internos.

No `body`, foram definidos a fonte, a cor de fundo, a cor dos textos e o espaçamento superior.

---

## 10. Cabeçalho fixo

O cabeçalho foi configurado com:

```css
position: fixed;
```

Isso faz com que o menu fique fixo na parte superior da tela mesmo quando o usuário rola a página.

Também foram definidas largura de 100%, altura de 70 pixels e uma cor rosa para o fundo.

---

## 11. Organização dos cartões

Para os cartões foi utilizado:

```css
display: inline-block;
```

Isso permite colocar os cartões lado a lado, mantendo uma estrutura organizada.

Também foram utilizados:

- `border-radius` para deixar os cantos arredondados;
- `padding` para criar espaço interno;
- `margin` para criar espaço entre os cartões;
- `border` para criar uma borda ao redor deles.

---

## 12. Rodapé e botão de voltar

No final das páginas existe um `<footer>` com o texto de direitos autorais.

Também foi criado um botão com a seta "↑", que utiliza:

```html
href="#topo"
```

Esse link leva o usuário novamente para o elemento que possui o `id="topo"`, fazendo com que seja possível voltar rapidamente para o início da página.

---

## 13. Conclusão

O desenvolvimento do portfólio permitiu aplicar na prática os conteúdos estudados no curso, principalmente HTML, CSS, organização de páginas, links, imagens, classes e estilização.

O projeto também ajudou a entender melhor como HTML e CSS trabalham juntos: o HTML cria a estrutura da página, enquanto o CSS modifica sua aparência.

A utilização do GitHub também foi importante para armazenar o projeto e acompanhar seu desenvolvimento.

Além disso, a Inteligência Artificial foi utilizada como ferramenta de apoio para ideias e elementos visuais, mas a implementação do site foi feita a partir dos conhecimentos de desenvolvimento web trabalhados durante o curso.