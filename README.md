<div align="center">

# 🎨 Tailwind CSS · Portfólio Auto-Explicativo

**Um site que se explica. Feito 100% com Tailwind CSS.**

[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![SESI](https://img.shields.io/badge/SESI-2°_Semestre-blue?style=for-the-badge)](https://www.sesi.org.br/)

[📖 Sobre](#-sobre-o-projeto) · [✨ Funcionalidades](#-funcionalidades) · [🚀 Como rodar](#-como-rodar) · [🎮 Mini-jogo](#-mini-jogo-tailwind-builder) · [👥 Equipe](#-equipe)

</div>

---

## 🌐 Site ao vivo

👉 **Acesse o portfólio online:** [https://seu-usuario.github.io/seu-repositorio](https://seu-usuario.github.io/seu-repositorio)

> 💡 O site também roda offline — basta abrir o `index.html` no navegador.

---

## 📖 Sobre o projeto

Este repositório contém o **portfólio interativo sobre Tailwind CSS** desenvolvido pelo **Grupo 1** para o projeto do **2° semestre do SESI**.

O objetivo do projeto é **ensinar Tailwind CSS de forma prática**, permitindo que qualquer pessoa veja a tecnologia funcionando em tempo real — e, ao mesmo tempo, entenda o código por trás de cada demonstração.

### 💡 O conceito: um site que se explica

A grande ideia do portfólio é que **o próprio site é a demonstração da tecnologia**.

Isso porque no Tailwind CSS **o estilo é escrito direto no HTML**, em forma de classes utilitárias. Diferente do CSS tradicional (onde o estilo fica num arquivo separado), aqui não tem "arquivo escondido": o código **está** no HTML.

O portfólio leva isso a sério:

> **Cada seção tem um botão "Ver código" que revela o HTML exato que gera o visual ao lado.**

Não é uma cópia. Não é uma captura de tela. É o **mesmo código** que está rodando — extraído do DOM em tempo real. Clicando, você vê o esqueleto por baixo da pele.

---

## ✨ Funcionalidades

### 📚 Seções educativas

Cada seção segue o **mesmo padrão visual** (header → body → footer) e ensina um conceito diferente do Tailwind:

| #   | Seção            | O que ensina               | Classes-chave                                       |
| --- | ---------------- | -------------------------- | --------------------------------------------------- |
| 01  | **Tipografia**   | Escala de tamanhos e pesos | `text-xs` a `text-9xl`, `font-light` a `font-black` |
| 02  | **Botões**       | Estados interativos        | `hover:`, `active:`, `focus:`, `disabled:`          |
| 03  | **Cards**        | Composição de componentes  | `rounded-*`, `shadow-*`, `flex`, `gap-*`            |
| 04  | **Cores**        | Escala de tons             | `bg-{cor}-{50 a 950}`                               |
| 05  | **Espaçamento**  | Padding, margin e gap      | `p-*`, `m-*`, `gap-*`                               |
| 06  | **Flex vs Grid** | Layouts lado a lado        | `flex`, `grid grid-cols-*`                          |
| 07  | **Responsivo**   | Breakpoints mobile-first   | `sm:`, `md:`, `lg:`                                 |
| 08  | **Mini-jogo**    | Testar o aprendizado       | tudo junto 🎮                                       |

### 🎨 Recursos visuais

- **Hero animado** com paths em SVG no fundo (azul, cobertura total)
- **Máscara radial** que apaga os paths no centro (mantém o texto legível)
- **Dark mode** via `class="dark"` no `<html>`
- **Tipografia dupla** — Space Grotesk (títulos) + Inter (corpo)
- **Botões "Ver código" + "Copiar"** em cada seção
- **Animação de letras** no título do hero (efeito spring)

---

## 🎮 Mini-jogo "Tailwind Builder"

O portfólio inclui um jogo educativo **completo** onde o jogador precisa **completar o HTML com a classe correta** antes do tempo acabar.

### Como funciona

- **6 fases**, cada uma com uma missão diferente
- **15 segundos por fase** (timer visível)
- **Preview ao vivo** — o código se aplica em tempo real
- **Hover preview** — passar o mouse numa opção já mostra como ficaria
- **Pontuação**: +10 + bônus de tempo (acerto) / -5 (erro ou timeout)
- **Feedback visual** — "CORRETO!", "ERROU!", "TEMPO ESGOTADO!"
- **Tela final** com mensagem personalizada por pontuação

### O que o jogo ensina

| Fase | Conceito                                               |
| ---- | ------------------------------------------------------ |
| 1    | Cor de fundo (`bg-blue-900`)                           |
| 2    | Bordas arredondadas (`rounded-full`)                   |
| 3    | Sombra (`shadow-lg`)                                   |
| 4    | Centralização com Flex (`justify-center items-center`) |
| 5    | Hover (`hover:text-red-600`)                           |
| 6    | Padding (`p-8`)                                        |

O jogo **não ensina nada novo** — ele **testa o que o portfólio ensinou**. É a prova viva de que o aprendizado aconteceu.

---

## 🛠️ Tecnologias

| Tecnologia                 | Uso                                                |
| -------------------------- | -------------------------------------------------- |
| **HTML5**                  | Estrutura do site                                  |
| **Tailwind CSS (via CDN)** | Estilização 100% por classes utilitárias           |
| **JavaScript vanilla**     | Interatividade (toggle de código, jogo, animações) |
| **Google Fonts**           | Inter + Space Grotesk + Fira Code                  |
| **SVG inline**             | Paths de fundo do hero                             |
| **CSS keyframes**          | Animações (letras do título, feedback do jogo)     |

> ⚠️ **Nenhum framework de JavaScript** (React, Vue, etc.) foi usado. Tudo é HTML + Tailwind + JS puro, para manter o foco no que realmente importa: as classes.

---

## 👥 Equipe

Projeto desenvolvido pelo **Grupo 1 — 2° Semestre SESI**.

| Integrante          | Função principal                       |
| ------------------- | -------------------------------------- |
| **Cleiton Candido** | Criação do Site demonstrativo          |
| **Luiza Cabral**    | Apresentação teórica + slides no Canva |
| **Giovana Ramos**   | Apresentação teórica + slides no Canva |

> 💡 **Todos participaram de todas as etapas** — a divisão acima é apenas organizacional. Pesquisa, criação do site, ensaio e apresentação foram feitas em conjunto.

---

## 🚀 Como rodar

O projeto **não precisa de instalação**. Basta abrir o arquivo HTML no navegador.

### Opção 1 — Abrir direto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
