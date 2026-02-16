# ⚡ CRM PRO

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Motion-black?style=for-the-badge&logo=framer&logoColor=blue)

> **CRM PRO** é uma aplicação front-end de alta performance para gestão de carteira de clientes, negociações e auditoria de acionamentos. Projetado com uma estética **Brutalista Moderna** (Dark Mode, tipografia massiva e alto contraste) e micro-interações fluidas.

🔗 **[Acessar Live Demo (Vercel)](#)** *(Insira seu link aqui depois do deploy)*

---

## 📖 Sobre o Projeto & Refatoração

Este projeto é fruto de uma **refatoração arquitetural profunda** de um sistema legado. O objetivo foi transformar uma base de código monolítica (arquivos gigantes, excesso de *prop drilling* e UI acoplada a regras de negócio) em um **SaaS moderno, escalável e modularizado**.

**Destaques da Arquitetura:**
* **Componentização de UI:** Criação de um Design System próprio (`Card`, `Button`, `Input`) reutilizável.
* **State-Driven Routing:** Substituição de dezenas de rotas e re-renderizações desnecessárias por uma navegação fluida baseada em estado (`ActiveTab`) dentro do Dashboard.
* **Mock Database:** Desacoplamento de APIs legadas utilizando um banco de dados estático (`mockDatabase.js`), garantindo que o portfólio funcione 100% offline e com alta velocidade para demonstrações.
* **Tailwind v4 (CSS-First):** Utilização da versão mais recente do Tailwind, eliminando arquivos de configuração pesados e gerindo tokens semânticos diretamente no CSS.

---

## ✨ Funcionalidades Principais

- **📊 Dashboard Analítico:** Visão geral de KPIs da carteira de clientes (Débito total, inadimplência, previsões de pagamento).
- **👥 Visão 360º do Cliente:** Perfil unificado utilizando sistema de Abas (Dados Cadastrais, Processos, Serviços/O.S. e Ocorrências), eliminando a necessidade de múltiplas telas.
- **⚡ Ações Rápidas de UX:** Fluxo otimizado onde o usuário pode acionar o formulário de negociação diretamente do perfil do cliente, auto-preenchendo parâmetros (ID/Matrícula).
- **✅ Painel de Auditoria:** Interface com transições suaves (Exit animations) para aprovação ou recusa de acionamentos pendentes.
- **📱 Responsividade Total:** Layout adaptável com Sidebar colapsável e tabelas com *scroll* horizontal inteligente em dispositivos móveis.

---

## 🛠️ Tecnologias Utilizadas

- **Core:** [React 18](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Estilização:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Animações:** [Motion (Framer Motion)](https://motion.dev/)
- **Smooth Scroll:** [Lenis](https://lenis.studiofreight.com/)
- **Navegação:** [React Router v6](https://reactrouter.com/)
- **Ícones:** [Lucide React](https://lucide.dev/)

