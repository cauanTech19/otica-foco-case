# 👁️ Foco Perfeito - Sistema de Gestão para Óticas

*(Coloque aqui um print daquela tela de Resumo Geral com o grid 2x2)*

## 💻 Sobre o Projeto
O **Foco Perfeito** é um Web App (PWA) desenvolvido para digitalizar e otimizar a gestão de clientes, receitas médicas e fluxo de caixa de uma ótica. 

Este foi um projeto desenvolvido com o objetivo de resolver um problema real de negócio: substituir controles manuais por um sistema ágil, acessível pelo celular e com cálculo automatizado de saldos pendentes.

## 🚀 Principais Funcionalidades
* **Gestão de Clientes:** Cadastro completo com dados pessoais e histórico de compras.
* **Ficha Clínica Ótica:** Registro detalhado de prescrições (Longe/Perto, ESF, CIL, EIXO, DP) e especificações de armações e lentes.
* **Controle Financeiro:** Cálculo automático de valor total, sinal (entrada) e saldo a receber.
* **Dashboard Analítico:** Painel de resumo financeiro em tempo real, destacando valores pendentes e total de vendas.
* **Progressive Web App (PWA):** Instalável no smartphone para uso nativo, com suporte a Dark Mode.

## 🛠️ Tecnologias Utilizadas
O projeto foi construído focando em uma arquitetura leve, sem o uso de frameworks complexos no front-end, garantindo alta performance e controle total sobre a interface e a lógica.

* **Front-end:** HTML5, CSS3 (CSS Grid, Flexbox, Variáveis nativas) e JavaScript Vanilla (ES6+ Modules).
* **Back-end & Banco de Dados:** [Supabase](https://supabase.com/) (BaaS / PostgreSQL) para persistência de dados e consultas assíncronas.
* **Ícones:** Tabler Icons.

## 🧠 Destaques da Arquitetura
* **Modularidade JS:** Código componentizado (`clients.js`, `stats.js`, `form.js`) facilitando a manutenção e escalabilidade.
* **Agregação de Dados no Front-end:** Uso de métodos como `.reduce()` e `.filter()` para processar respostas do Supabase e renderizar o dashboard de estatísticas dinamicamente.
* **UI/UX Responsiva:** Interface mobile-first desenvolvida do zero, com estados de carregamento (spinners), toasts de feedback e layout adaptativo.

## 👨‍💻 Autor
Desenvolvido por **[Seu Nome]**
* [LinkedIn](https://www.linkedin.com/in/cauan-da-paz-justino-9306b9350/))
* Estudante de Análise e Desenvolvimento de Sistemas (ADS).

---
*Nota: O código-fonte original é mantido em um repositório privado para proteção dos dados reais e lógicas de negócio do estabelecimento.*
