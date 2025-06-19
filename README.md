# 💳 Identificador de Bandeira de Cartão de Crédito

Uma aplicação simples feita em **HTML**, **CSS** e **JavaScript** que identifica a bandeira de um cartão de crédito com base nos números digitados pelo usuário, de acordo com os prefixos padrões de cada bandeira.

---

## 🔧 Tecnologias Utilizadas

<div style="display:flex; gap:10px; align-items:center;">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</div>

---

## 🎯 Funcionalidades

- 🧠 Identifica automaticamente a bandeira do cartão com base no número inicial:
  - Visa → começa com `4`
  - MasterCard → começa com `51` até `55`
  - American Express → `34` ou `37`
  - Diners Club → `36`
  - Discover → `6011`
  - JCB → `35`
- ✅ Aceita apenas números, mesmo que o usuário cole com espaços ou traços
- 🔢 Formata o número digitado em blocos de 4 dígitos para facilitar a leitura

---

## 🖼️ Exemplo das Bandeiras Suportadas

<div style="display:flex; gap:10px;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Visa_Inc._logo.svg" alt="Visa" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Mastercard-logo.png" alt="MasterCard" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/American_Express_logo_%282018%29.svg" alt="Amex" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Diners_Club_Logo3.svg" alt="Diners" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Discover_Card_logo.svg" alt="Discover" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/JCB_logo.svg" alt="JCB" height="40"/>
</div>

---

## ▶️ Como Usar

1. Abra o arquivo `index.html` em seu navegador
2. Digite (ou cole) os números do cartão no campo
3. O sistema formatará automaticamente e exibirá a **bandeira** identificada abaixo

---

## 📁 Estrutura do Projeto

