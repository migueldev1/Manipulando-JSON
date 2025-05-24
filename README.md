# 📂 Manipulação de JSON com JavaScript

Este projeto demonstra como carregar, interpretar e utilizar dados de um arquivo JSON externo usando JavaScript puro, sem o uso de bibliotecas ou frameworks.

## 📌 Objetivo

Praticar o uso da API `fetch()` e a manipulação de dados JSON para criar elementos HTML dinamicamente com base em um arquivo de dados estruturado.

O foco do projeto está na **leitura, interpretação e uso de um JSON** com uma lista de objetos, onde cada objeto representa um item (no caso, um jogo com nome e imagem).

## 📦 Dados (JSON)

O projeto utiliza um arquivo `jogos.json` com a seguinte estrutura:

```json
[
  {
    "nome": "Minecraft",
    "imagem": "img/minecraft.webp"
  },
  {
    "nome": "Fortnite",
    "imagem": "img/fortnite.jpg"
  }
]
```
## Cada objeto do JSON contém:

`nome:` o nome do jogo

`imagem:` caminho da imagem correspondente

## 📜 Lógica JavaScript
Utiliza `fetch()` para carregar o arquivo jogos.json

Converte a resposta usando `.json()`

Itera pelos objetos usando `.map()`

Cria elementos HTML (div, img, h3) dinamicamente com base nos dados do `JSON`

Insere os elementos no DOM

## 📚 O que você aprende com este projeto
Como importar arquivos `JSON` em projetos web

Como trabalhar com `.then()` para lidar com Promises

Como transformar objetos `JSON` em elementos HTML de forma programática

Como interagir com o DOM baseado em dados externos

## 🛠️ Tecnologias utilizadas
HTML5

CSS3

JavaScript (ES6+)

JSON (JavaScript Object Notation)

