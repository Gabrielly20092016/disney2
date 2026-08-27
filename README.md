# Mundo Disney — Integração com API

## Autor

* **Nome:** Gabrielly Vitória Rosa De Jesus Silva
* **Ano:** 2026

## 1. Identificação do projeto

* **Nome do projeto:** Meu Disney
* **Instituição de ensino:** 
* **Unidade curricular:** UC8 - Desenvolver Aplicações Mobile
* **Professor(a):** Rafaela Pessin

---

## 2. Sobre o projeto

> O projeto é uma página, onde o nome e Meu Disney, que busca personagens da Disney em uma API e mostra cada um em um card com imagem e nome.

## 3. Estrutura do projeto

Apresente a organização dos arquivos e pastas do seu projeto.

**Exemplo:**

```text
mundo-disney/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   └── sem-imagem.png
├── fonts/
│   └── waltograph42.otf
└── README.md
```

### Descrição dos arquivos

| Arquivo      | Descrição                                                        |
| ------------ | ---------------------------------------------------------------- |
| `index.html` | É a estrutura principal da página. |
| `style.css`  | Cuida do visual e da responsividade da página. |
| `script.js`  | Faz a conexão com a API e cria os cards. |
| `README.md`  | Contém as informações do projeto. |

> **Caso seu projeto possua outras pastas ou arquivos, apresente-os também na estrutura acima.**

---

## 💻 4. Tecnologias utilizadas

Liste as tecnologias utilizadas no desenvolvimento do projeto.

* HTML5
* CSS3
* JavaScript

---

## 5. API utilizada

### Nome da API

**Disney API**

### Endpoint utilizado

```text
https://api.disneyapi.dev/character
```

### Para que a API foi utilizada?

>A API foi utilizada para pesquisar os personagens da Disney e exibir suas informações na página.

### Quais informações foram consumidas?

>Foram utilizados principalmente o nome, a imagem e as informações de paginação dos personagens.

---

##  6. Como executar o projeto

Explique passo a passo como outra pessoa pode executar seu projeto em outra máquina.

### Pré-requisitos

Informe se é necessário instalar algum programa ou ferramenta para executar o seu projeto em outr máquina

### Passo a passo

* Passo 1: Baixe os arquivos do projeto.
* Passo 2: Mantenha as pastas e arquivos organizados.
* Passo 3: Abra o `index.html` no navegador.

---

## 7. Como funciona a integração

Explique de forma objetiva e em até 10 passos como sua aplicação se comunica com a API.

1-O JavaScript informa o endereço da API.
2-A URL é criada com a página atual e 50 personagens.
3-O fetch() realiza a requisição à API.
4-A resposta é convertida para JSON.
5-Os personagens são obtidos no resultado.
6-O código percorre cada personagem.
7-Um card é criado para cada um deles.
8-O nome e a imagem são adicionados ao card.
9-O botão carrega a página seguinte sem remover os anteriores.
 10-O contador e a página são atualizados.


## 8. Desafios encontrados

Registre pelo menos um problema ou dificuldade que você encontrou durante o desenvolvimento e como resolveu

### Desafios encontrados

**Problema:**

> 1. Apresenteu  dificuldade para fazer os personagens aparecerem corretamente na página.
> 2.Também tive dificuldade para organizar os cards e fazer o botão carregar mais personagens.

**Como identifiquei o problema:**

> 1.Percebi que os personagens não estavam sendo exibidos como esperado na página.
> 2.Testei o código e observei que o botão não estava funcionando corretamente.

**Como resolvi:**

> 1.Revisei o código JavaScript e corrigi a forma como os dados da API eram acessados.
> 2.Ajustei o código dos cards e da paginação para carregar os personagens corretamente.

---

## 9. Aprendizados

> Aprendi a usar `fetch()`, criar cards com JavaScript e fazer uma página responsiva. Também aprendi um pouco mais sobre como organizar os arquivos do projeto.

---
