---
title: Latex no Mardown
author: Gabriel Fanto Stundner
date: 2022-09-12 21:00:00 +0800
categories: [Básico, Markdown]
tags: [Markdown, LATEX]
math: true
mermaid: true
---

Podemos utilizar comandos LATEX para facilitar nossa vida para construir um artigo, veja abaixo os comandos mais comuns matemáticos

* A matemática do Github é utilizando KATEX
* Documento oficial com comandos: [Comandos](https://katex.org/docs/supported.html#logic-and-set-theory)


|**Glossário**|
|---|
|<a href="#tipos">Tipos de Comandos</a>|
|<a href="#simbol">Utilizando Símbolos matemáticos</a>
|<a href="#logic">Utilizando Símbolos lógicos</a>
|<a href="#math">Utilizando Fórmulas matemáticas</a>
|<a href="#math">Utilizando Fórmulas matemáticas</a>
|<a href="#color">Cores no LATEX</a>

---


<p id="tipos"></p>

### Tipos de comandos:

1. Se utilizarmos `$$texto$$`, ou seja, o símbolo `$` duas vezes de cada lado, ele vai centralizar o texto:

$$\boxed{Centralizado}$$

Código do teste acima:

```latex
$$\boxed{Centralizado}$$
```

2. Se utlizarmos `$text$`, ou seja, o símbolo `$` somente uma vez de cada lado, ele vai deixar o texto na mesma linha

* Hoje, após ${\color{red}10}$ dias, estaremos livres.

Código do teste acima:

```latex
Hoje, após ${\color{red}10}$ dias, estaremos livres.
```

---
---

<p id="simbol"></p>

## $${ \color{yellow} \boxed{ \color{lightgreen} Utilizando \space Símbolos \space Matemáticos } }$$


|Código|Símbolo|significado
|---|---|---|
|`$\leq$`|$\leq$| Menor ou igual
|`$\geq$`|$\geq$| Maior ou igual
|`$a_0$`|$a_0$| Primeiro valor de um conjunto
|`$2^2$`|$2²$| Potência de um valor
|`$\infty$`|$\infty$| Símbolo de infinito
|`$\int$`|$\int$| Símbolo de uma integral
|`$\overrightarrow{a}$`|$\overrightarrow{a}$| Colocar uma seta encima da letra
|`$\pm$`|$\pm$|Sinal de mais ou menos
|`$\pi$`|$\pi$| Sinal do pi
|`$\mu$`|$\mu$| Simbolo grego mu
|`$\not =$`|$\not = $| Símbolo de diferente
|`$\lbrace$`|$\lbrace$| Chave da esquerda
|`$\rbrace$`|$\rbrace$| Chave da direita
|`$\cancel{5}$`|$\cancel{5}$ | Corta um valor
|`$\xcancel{ABC}$`|$\xcancel{ABC}$ | Corta vários valores juntos
|`$\overbrace{a+b+c}$`|$\overbrace{a+b+c}$| Marca um conjunto de dados
|`$\overbrace{a+b+c}^{\text{exemplo}}$`|$\overbrace{a+b+c}^{\text{exemplo}}$| Colocar um texto encima de um conjunto
|`$\overbrace{a+b+c}_{\text{exemplo}}$`|$\overbrace{a+b+c}_{\text{exemplo}}$| Colocar um texto embaixo de um conjunto
|`$\boxed{\pi = 3.1415}$`|$\boxed{\pi = 3.1415}$| Colocar texto dentro de uma caixa
|`$\mathbb{N}$`|$\mathbb{N}$| Simbolo para o conjunto dos Números Naturais
|`$\mathbb{Z}$`|$\mathbb{Z}$| Símbolo para o conjunto dos Números Inteiros
|`$\mathbb{R}$`|$\mathbb{R}$| Símbolo para o conjunto dos Números Reais


---

<p id="logic"></p>

## $${ \color{purple} \boxed{ \color{lightblue} Utilizando \space Símbolos \space Lógicos } }$$

|Código|Símbolo|significado
|---|---|---|
|`$\forall$`|$\forall$| Para todo lógico, significa que todos os elementos de um conjunto seguem uma regra
|`$\in$`|$\in$| Pertence, para dizer que um valor x pertence a um conjunto
|`$\in !$`|$\in !$| Não pertence, para dizer que um valor x não pertence ao conjunto
|`$\exists$`|$\exists$| Existe lógico, quer dizer que existe pelo menos um dentro de um conjunto
|`$\exists !$`|$\exists !$| Não existe, quer dizer que não existe nenhum dentro de um conjunto
|`$\neg$`|$\neg$| Negação lógica
|`$\Rightarrow$`|$\Rightarrow$| implica em algo, significa que se a fórmula da direita for verdade, implica em outra conclusão (Se,então)
|`$\Leftrightarrow$`|$\Leftrightarrow$| significa que um depende do outro para ser verdadeiro
|`$\wedge$`|$\wedge$| é o & lógico, onde os dois tem que ser verdadeiros para ser verdadeiro
|`$\lor$`|$\lor$| é o | lógico, onde pelo menos um deles tem que ser verdadeiro para ser verdadeiro
|`$\top$`|$\top$| é uma Tautologia, significa que é sempre verdadeiro 
|`$\bot$`|$\bot$| é uma Contradição, significa que é sempre falso
|`$\equiv$`|$\equiv$| é equivalência, significa que duas informações são parecidas mas não são iguais

---

<p id="math"></p>

## $${ \color{white} \boxed{ \color{cyan} Utilizando \space Fórmulas \space Matemáticas } }$$

|Código|Símbolo|significado
|---|---|---|
|`$\sum\limits_{i=1}^n i$`|$\sum\limits_{i=1}^n i$|É o somatório de todos de i indo de 1 até n
|`$\prod_{i=a}^{b} f(i)$`|$\prod_{i=1}^{n} i$| É o produtório (multiplicação de todos os valores) de i indo de 1 até n
|`$\frac{n}{k}$`|$\frac{n}{k}$| É a fração, divisão de dois números
|`$\binom{k}{n}$`|$\binom{k}{n}$| é a fórmula de um binômio
|`$\sqrt[2]{144}$`|$\sqrt[2]{144}$| Raiz quadrada
|`$\int\limits_a^b$`|$\int\limits_a^b$| Integrais
|`$\lim\limits_{x \to \infty} f(x) = L$`|$\lim\limits_{x \to \infty} f(x) = L$|Limites
|`$\begin{vmatrix} a & b \newline c & d \end{vmatrix}$`|$\begin{vmatrix} a & b \newline c & d \end{vmatrix}$| Matrizes

---

### Se deseja comentar a fórmula ao lado 

```latex
$$\tag{Somatório} \sum$$
```

$$\tag{Somatório} \sum$$

---

<p id="color"></p>

## $${ \color{pink} \boxed{ \color{lightblue}C \color{lightgreen}O \color{red}R \color{cyan}E \color{purple}S } }$$

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

## $${ \color{teal} \boxed{ \color{magenta} TESTES } }$$

```latex
$${\color{red}\sum\limits_{\color{lightblue}i=0}^{\color{orange}n} {\color{pink}i}} = \frac{\color{pink}n!}{\color{lightblue}k!(n-k)!}$$
```


$${\color{red}\sum\limits_{\color{lightblue}i=0}^{\color{orange}n} {\color{pink}i}} = \frac{\color{pink}n!}{\color{lightblue}k!(n-k)!}$$