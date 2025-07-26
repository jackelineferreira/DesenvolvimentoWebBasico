# 📋 Lista de Exercícios 3 – Desenvolvimento Web Básico

Projeto desenvolvido como parte da Lista de Exercícios 3 da disciplina de Desenvolvimento Web Básico.  
O objetivo é praticar HTML5 semântico, CSS básico, Flexbox, Grid e responsividade, além de criar um menu hamburger funcional.

---

## ✅ Estrutura do projeto

- **index.html**
  - Estrutura principal do site com:
    - `<header>` contendo `<h1>` (título) e `<p>` (introdução)
    - `<main>` com duas subseções:
      - Seção **Missão** (`<h2>` e `<p>`)
      - Seção **Visão** (`<h2>` e `<p>`)
    - `<footer>` com `<p>` de copyright

- **listas.html**
  - Lista não ordenada (`<ul>`) com cinco hobbies
  - Lista ordenada (`<ol>`) com passo a passo de uma receita simples
  - Bloco de navegação (`<nav>`) com três links externos

- **feedback.html**
  - Formulário contendo:
    - Nome
    - E-mail
    - Endereço Completo
    - Tipo de feedback
    - Campo para escrever o feedback
    - Botão de envio

- **styles.css**
  - Cores de fundo e de texto para `<header>`, `<main>` e `<footer>`
  - Aplicação de `margin`, `padding` e `border` para evidenciar contornos
  - Estilo para `<h2>` com `font-size` maior e `text-decoration: underline`
  - Classe `.destaque` que deixa o texto em itálico e adiciona background
  - ID `#importante` que adiciona uma `border-top` mais espessa em um parágrafo específico

- **galeria.html** (ou seção na index)
  - Galeria com oito imagens e legendas
  - Organizada com Grid Layout
  - Contêiner externo usando Flexbox para centralizar e permitir quebra de linha
  - Ajuste de colunas com media queries para telas menores

- **Menu hamburger**
  - Aparece apenas em telas com largura ≤ 600 px
  - Abre e fecha ao ser clicado, ocultando a navegação padrão

---

## 🛠 Tecnologias usadas

- HTML5
- CSS3 (incluindo Flexbox e Grid)
- JavaScript básico para interação do menu hamburger

---

## 📦 Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git

2. Abra a pasta no VS Code:

cd NOME_DO_REPOSITORIO
code .

3. Abra o arquivo index.html no navegador para visualizar.

✏️ Autor
Projeto criado como atividade prática para fixar conceitos de HTML e CSS.
Personalize, adicione comentários e melhore conforme evoluir!

