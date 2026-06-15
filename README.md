<!-- HEADER ANIMADO -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=4ade80&height=200&section=header&text=CactusFinance&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Dashboard%20Financeiro%20Pessoal&descAlignY=55&descSize=20" />
</div>
<!-- BADGES -->
<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" />
</div>
<br/>
<!-- STATUS -->
<div align="center">
  <img src="https://img.shields.io/badge/status-concluído-4ade80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FIAP-1TDSOB-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ADS-2026-blue?style=for-the-badge" />
</div>
<br/>

🌵 Sobre o Projeto

O CactusFinance é uma plataforma Fintech de gestão financeira pessoal desenvolvida como projeto acadêmico na FIAP. O objetivo é oferecer ao usuário uma visão clara e intuitiva das suas finanças — saldo, receitas, despesas e categorias de gastos — em um único dashboard.

Esta atividade consistiu em recriar em HTML, CSS e Tailwind CSS a tela de Dashboard (Visão Geral) prototipada no Figma durante a Fase 2 do projeto.


🖥️ Tela Desenvolvida — Dashboard (Visão Geral)

A tela do Dashboard foi escolhida por ser a mais completa do sistema, reunindo:

ElementoDescrição📊 Sidebar de navegaçãoMenu lateral com links para todas as seções💰 Card de SaldoExibe o saldo disponível do mês📈 Card de ReceitasTotal de entradas no mês📉 Card de DespesasTotal de saídas no mês🍩 Gráfico DonutGastos divididos por categoria (Lazer, Alimentação, Contas)📋 Últimas TransaçõesTabela com as transações mais recentes🌙 Toggle Dark/LightBotão de alternância de tema visual


🛠️ Tecnologias Utilizadas


HTML5 — Estrutura semântica da página
CSS3 — Estilização customizada com variáveis e flexbox
Tailwind CSS v3 — Framework utilitário instalado via npm
Google Fonts — Fontes Space Grotesk e Inter
npm — Gerenciador de pacotes para compilação do Tailwind



📁 Estrutura do Projeto

cactusfinance_FIAP/
├── 📁 Images/
│   └── logo.png
├── 📁 dist/
│   └── output.css        ← CSS compilado pelo Tailwind
├── 📁 node_modules/
├── index.html            ← Página principal (Dashboard)
├── style.css             ← Estilos customizados
├── input.css             ← Diretivas do Tailwind
├── tailwind.config.js    ← Configuração do Tailwind
├── package.json
└── README.md


🚀 Como Executar

bash# 1. Clone o repositório
git clone https://github.com/KauaDaudt/cactusfinance-fiap.git

# 2. Entre na pasta
cd cactusfinance-fiap

# 3. Instale as dependências
npm install

# 4. Compile o Tailwind
npx tailwindcss -i ./input.css -o ./dist/output.css --watch

# 5. Abra o index.html no navegador


📱 Responsividade

O layout é totalmente responsivo, adaptando-se a diferentes tamanhos de tela:


Desktop — Sidebar expandida, grid de 3 colunas
Mobile — Sidebar recolhida com ícones, layout em coluna única



👨‍💻 Autor

<div align="center">
  <img src="https://avatars.githubusercontent.com/KauaDaudt" width="100px" style="border-radius: 50%" />
  <br/>
  <strong>Kauã Daudt Gomes</strong>
  <br/>
  Turma: 1TDSOB — ADS — FIAP 2026
  <br/><br/>
  <a href="https://github.com/KauaDaudt">
    <img src="https://img.shields.io/badge/GitHub-KauaDaudt-181717?style=for-the-badge&logo=github" />
  </a>
</div>

<!-- FOOTER ANIMADO -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=4ade80&height=120&section=footer&animation=fadeIn" />
</div>
