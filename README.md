# 📋 Tree Prime - Sistema de Gestão Contábil

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📋 Sobre o Projeto

O **Tree Prime** é um painel de acompanhamento de rotinas para um escritório de contabilidade: cadastro de clientes, checklists de obrigações (abertura, mensal contábil, fiscal, departamento pessoal, obrigações acessórias) e exportação de relatórios em PDF. É uma SPA (single page application) em JavaScript puro, sem framework e sem backend — todos os dados ficam salvos no `localStorage` do navegador, com opção de exportar/importar um backup em JSON.

> **Nota de escopo:** este é um protótipo funcional client-side, não uma aplicação com backend/banco de dados real. Login e persistência local são adequados para demonstração e uso individual, não para múltiplos usuários simultâneos em produção.

## 🎯 Funcionalidades

- **Dashboard** — visão geral das rotinas
- **Cadastro de Abertura** e **Clientes Ativos** — com busca por nome
- **Checklists** — Mensal Contábil, Fiscal, Departamento Pessoal, Obrigações Acessórias
- **Gestão de usuários** — perfil administrador com tela própria
- **Backup** — exportação e importação dos dados em JSON
- **Relatórios em PDF** — via [html2pdf.js](https://github.com/eKoopmans/html2pdf.js)
- **Gráficos** — via [Chart.js](https://www.chartjs.org/)

## 🛠️ Stack Técnico

- JavaScript (vanilla, sem framework)
- HTML5 + CSS3
- `localStorage` para persistência de dados no navegador
- Font Awesome, html2pdf.js e Chart.js via CDN

## 🚀 Como rodar

Não há instalação nem dependências — basta abrir o arquivo `sistema-checklist-contabil/index.html` em um navegador.

---
*Desenvolvido por Rodrigo Aparecido*
