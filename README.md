# 🎬 FilmBox

O **FilmBox** é uma aplicação web interativa desenvolvida para catalogar, avaliar e acompanhar todos os filmes assistidos ao longo do ano. O projeto funciona como um diário pessoal de cinema, permitindo registrar resenhas, calcular estatísticas de tempo assistido e acompanhar metas anuais.

---

## 🚀 Funcionalidades

- **Painel Geral (Dashboard):**
  - Contagem total de filmes assistidos.
  - Cálculo automático da média das notas.
  - Indicador de filmes favoritos e tempo total investido (horas/minutos).
  - Barra de progresso para a meta anual de filmes.

- **Registro de Filmes:**
  - Cadastro de detalhes: título, diretor, gênero, ano de lançamento e duração.
  - Registro de experiência: data assistida, plataforma (cinema, streaming, mídia física).
  - Sistema de avaliação por **estrelas (1 a 5)**.
  - Campo de resenha/anotações pessoais.
  - Opções para marcar como **Favorito ❤️** ou **Re-watch 🔄**.

- **Catálogo & Filtros (Página Dedicada):**
  - Visualização em cards gerados dinamicamente via JavaScript.
  - Busca por título ou diretor.
  - Filtros por gênero e plataforma.
  - Ordenação por recentes, antigos, notas e ordem alfabética.
  - Edição e remoção de registros.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica e acessível (com uso de `<fieldset>`, `<legend>`, e tags de formulário nativas).
- **CSS3:** Estilização moderna, uso de variáveis CSS, layout flexível com Flexbox e CSS Grid, componentes interativos e total responsividade para dispositivos móveis.
- **JavaScript (ES6+):** Manipulação dinâmica do DOM, tratamento de eventos e persistência de dados localmente.
- **LocalStorage API:** Armazenamento permanente dos filmes no navegador do usuário (sem necessidade de backend inicial).

---

## 📂 Estrutura do Projeto

```text
FilmBox/
├── index.html       # Página principal (Dashboard e Formulário de Cadastro)
├── dashboard.html    # Página do Catálogo Completo (Busca, Filtros e Cards)
├── style.css        # Estilização global e responsiva
└── script.js        # Lógica da aplicação e manipulação do LocalStorage
