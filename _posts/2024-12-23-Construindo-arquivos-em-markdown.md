---
title: Construindo arquivos em Markdown
author: Gabriel Fanto Stundner
categories: [Básico, Markdown]
tags: [Markdown, LATEX]
math: true
img_path: assets/img
pin: true
---

Esta é a primeira página deste Website, onde eu irei explicar como construir os arquivos em Markdown necessários para escrever informações que auxiliem nos meus estudos de Programação
e tecnologias úteis.

|**Glossário**|
|---|
|<a href="#glossario">Tabelas e Glossários</a>
|<a href="#titulos">Títulos</a>
|<a href="#list">Listas</a>
|<a href="#prompts">Prompts</a>
|<a href="#images">Imagens</a>
|<a href="#code">Códigos</a>
|<a href="#colors">Cores</a>
|<a href="#center">Centralização</a>


<p id="glossario"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{TABELAS \space E \space GLOSSÁRIO}}}$$

Glossários são muito úteis para vincular dados de um mesmo arquivo, podendo separar as informações de uma forma eficiente.

Para construir um glossário, construa uma tabela, utilizando a seguinte estrutura em Markdown:

```markdown
| Coluna 1 |
|----------|
|  Linha 1 |
|  Linha 2 |
```

Depois colocamos dentro de cada linha uma tag de referencia, como abaixo

```html
<a href="#section">Títulos</a>
```

o nome definido no `href` é o nome que iremos fazer a busca no texto, então colocamos a seguinte tag perto do inicio do tópico que queremos vincular:

```html
<p id="section"></p>
```

Com isso, sempre que clicarmos no link, ele vai nos levar na área desse tópico onde foi vinculado.

---

<p id="titulos"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{TÍTULOS}}}$$


Construir títulos é só colocar `#` no inicio da linha, quanto mais `#` colocar menor fica o título.

O código para gerar um título

```markdown
# Título
```

Exemplo:

# Título

Diferentes tamanhos:

```markdown
# Título
## Título
### Título
#### Título
##### Título
```

Exemplo:

# Título
## Título
### Título
#### Título
##### Título

---

<p id="list"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{LISTAS}}}$$

Podemos construir diferentes tipos de listas em Markdown, uma delas é a lista ordenada:

```markdown
1. Tópico 1
2. Tópico 2
3. Tópico 3
```

Exemplo:

1. Primeiro
2. Segundo
3. Terceiro

Outra lista é a lista de camadas, onde podemos colocar valores dentro de valores

```markdown
- Primeiro Nivel
  - Segundo Nivel
    - Terceiro Nivel
```

Exemplo:

- Primeiro Nivel
  - Segundo Nivel
    - Terceiro Nivel

Podemos construir listas com checkbox para determinar tarefas, onde elas também podem ter subniveis

```markdown
- [ ] TODO
- [x] Completado
  - [x] completado subtarefa
  - [ ] mais uma subtarefa
```

Exemplo:

- [ ] TODO
- [x] Completado
  - [x] completado subtarefa
  - [ ] mais uma subtarefa

Podemos construir uma lista de descrição de algo, onde podemos explicar algo

```markdown
Gabriel
: anjo protetor dos fracos e oprimidos, avisou a maria que jesus seria seu filho
```

Exemplo:

Gabriel
: anjo protetor dos fracos e oprimidos, avisou a maria que jesus seria seu filho

---

<p id="prompts"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{PROMPTS}}}$$


Prompts servem para mostrar uma informação, podemos usar os prompts como mostrado abaixo:

```markdown
> Exemplo visual de uma `dica` em formato de prompt.
{: .prompt-tip }
```

Exemplo

> Exemplo visual de uma `dica` em formato de prompt.
{: .prompt-tip }

```markdown
> Exemplo visual de uma `informação` em formato de prompt.
{: .prompt-info }
```

Exemplo:

> Exemplo visual de uma `informação` em formato de prompt.
{: .prompt-info }


```markdown
> Exemplo visual de um `warning` em formato de prompt.
{: .prompt-warning }
```

> Exemplo visual de um `warning` em formato de prompt.
{: .prompt-warning }

```markdown
> Exemplo visual de `perigo` em formato de  prompt.
{: .prompt-danger }
```

> Exemplo visual de `perigo` em formato de  prompt.
{: .prompt-danger }

---

<p id="images"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{IMAGENS}}}$$

Colocamos imagens no markdown utilizando duas formas:

Forma 1 é a estrutura de uma imagem do markdown

```markdown
![Texto](url)
```

Com isso podemos pegar uma imagem e colocar no sistema, mas não tem controle do tamanho.

Exemplo

```markdown
![texto](favicons/android-chrome-512x512.png)
```

![My helpful screenshot](/assets/img/favicons/favicon-16x16.png)

Se queremos ter um controle da imagem, devemos usar a tag HTML `<img>`

```html
<img src="url" width="largura" height="altura">
```

Exemplo:

```html
<img src="assets/img/favicons/android-chrome-512x512.png" width="200" height="200">
```

![https://imgur.com/a/0nDAGVt](https://imgur.com/a/0nDAGVt)

---

<p id="code"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{CÓDIGOS}}}$$

Podemos colocar código de duas formas:

Forma 1 é colocar ``` encima e embaixo de um código, junto com o nome da linguagem

```java
System.out.println
```

---

<p id="colors"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{CORES}}}$$

> Graças ao comando `\color{}` podemos colocar cores no texto, tanto no $\LaTeX$ quanto no markdown, as cores abaixo são as mais comuns
{: .prompt-info }

|Código|Símbolo
|---|---|
|`${\color{red}COR}$`|${\color{red}COR}$
|`${\color{green}COR}$`|${\color{green}COR}$
|`${\color{blue}COR}$`|${\color{blue}COR}$
|`${\color{orange}COR}$`|${\color{orange}COR}$
|`${\color{cyan}COR}$`|${\color{cyan}COR}$
|`${\color{purple}COR}$`|${\color{purple}COR}$
|`${\color{yellow}COR}$`|${\color{yellow}COR}$
|`${\color{black}COR}$`|${\color{black}COR}$
|`${\color{white}COR}$`|${\color{white}COR}$
|`${\color{pink}COR}$`|${\color{pink}COR}$
|`${\color{magenta}COR}$`|${\color{magenta}COR}$
|`${\color{teal}COR}$`|${\color{teal}COR}$
|`${\color{violet}COR}$`|${\color{violet}COR}$
|`${\color{lightgray}COR}$`|${\color{lightgray}COR}$
|`${\color{lime}COR}$`|${\color{lime}COR}$
|`${\color{olive}COR}$`|${\color{olive}COR}$
|`${\color{brown}COR}$`|${\color{brown}COR}$

---

<p id="center"></p>

# $$\color{red}\boxed{\mathbb{\color{lime}{CENTRALIZAR}}}$$

> Podemos centralizar dados utilizando as tags de `<center>` ou uma estrutura base que funciona no Github e no Gitlab
{: .prompt-info }

- Tag Center

```html
<center>
  <!-- Conteúdo aqui -->
</center>
```

- Construção que aceita colocar no Github e Gitlab

```html
<table align="center"><tr><td align="center" width="9999">
  <!-- Conteúdo aqui -->
</td></tr></table
```
