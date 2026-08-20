# 📘 Roteiro de Revisão Prática: Manipulação do DOM com JavaScript

Guia de revisão para **manipulação do DOM (Document Object Model)**, conectando o comportamento interativo (**JavaScript**) à estrutura (**HTML**) e aparência (**CSS**) de forma modular e gradativa.

---

### ⚙️ Como usar este material:
1. **Estrutura Isolada:** Criem uma pasta própria (ex: `aula1-ex1`).
2. **Separação de Arquivos:** Os códigos estão organizados em arquivos separados (`index.html`, `style.css` e `script.js`) para o foco na lógica do JavaScript, sem misturar tags de estilo ou scripts dentro do HTML .
3. **Foco Prático:** Cada aula traz um resumo conceitual rápido seguido de **3 exercícios práticos progressivos**.

---

## 📅 Aula 1: Selecionando Elementos e Alterando Conteúdo (Os Fundamentos)

**Objetivo:** Compreender a árvore do DOM como uma estrutura de "nós", aprender a selecionar elementos de forma precisa e alterar conteúdos de texto e valores de campos de formulário a partir de cliques em botões ].

### 🧠 Resumo Teórico 
* **Selecionar é o primeiro passo:** Para alterar qualquer elemento na página, precisamos primeiro "capturá-lo" no JavaScript. Usamos `document.getElementById("id")` para IDs únicos ou `document.querySelector(".classe" ou "#id")` para seletores de estilo CSS.
* **Modificando o Texto:** A propriedade `textContent` lê ou altera o texto contido no elemento (sem interpretar tags HTML).
* **Lendo Inputs:** Para obter o texto que o usuário digitou em um campo de texto (`<input>`), acessamos a propriedade `.value` do elemento.
* **Escutador de Eventos:** Para reagir a cliques, adicionamos um "ouvinte" ao botão com `elemento.addEventListener("click", funcao)`.

---

### 🧩 Exercício 1.1: Criador de Títulos Dinâmico
O aluno deve capturar o texto digitado em um input eexibi-lo instantaneamente em um título h1 que já existe na página ao clicar em um botão.

---

### 🧩 Exercício 1.2: Contador de Cliques Simples
*O aluno criará um botão de clique que incrementa um contador numérico na tela a cada clique.*



### 🧩 Exercício 1.3: Copiar Texto Instantâneo
*O aluno irá praticar a transferência de dados entre elementos textuais sem usar inputs, copiando o texto de um parágrafo para outro com um clique.*
