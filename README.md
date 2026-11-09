# 🔟 Super Tático — Guia Operacional Interativo Camisa 10 (`supertatico`)

Aplicação web mobile-first e interativa em **HTML5 + Vue 3 + Tailwind CSS** desenvolvida como **Guia Operacional e Painel Tático "Camisa 10"** para alinhamento diário da equipe de loja da **Ri Happy** durante grandes campanhas (como **Dia das Crianças / DDC 2026**, Black Friday e Natal).

---

## 🚀 Principais Funcionalidades

- **Visão Mobile do Colaborador (`index.html`)**:
  - Seletor rápido de colaborador com visualização personalizada da função tática do dia (Caixa `P1`, Pacote `PC`, Porta/Recepção `P2`, Salão `P3`, Apoio `P4`, Estoque/Omni).
  - Checklists interativos de execução por turno, metas prioritárias, argumentos de venda de itens adicionais e regras de ouro de atendimento.
- **Painel de Gestão / Admin (`admin.html` & `canva_interativo_camisa_10_ri_happy.html`)**:
  - Quadro tático interativo para distribuição visual da equipe no mapa da loja, configuração de turnos, horários de pico e exportação/apresentação para o briefing matinal.
- **Guia Rápido de Bolso (`guia.html`)**:
  - Ponto de acesso rápido às diretrizes táticas da operação.

---

## 🛠️ Tecnologias Utilizadas

- **Vue.js 3** (via CDN Global Build)
- **Tailwind CSS** com paleta customizada oficial Ri Happy (`ri.orange`, `ri.yellow`, `ri.purple`, `ri.blue`, `ri.green`, `ri.pink`)
- **FontAwesome 6 & Google Fonts (*Montserrat* e *Poppins*)**

---

## 📂 Estrutura do Repositório

```text
supertatico/
├── index.html                                # App Mobile do Colaborador (Guia Operacional Camisa 10)
├── admin.html                                # Painel Administrativo de Escalação Tática
├── canva_interativo_camisa_10_ri_happy.html  # Quadro Tático Interativo em Tela Cheia
├── guia.html                                 # Atalho e guia rápido de navegação
└── README.md
```

---

## 💻 Como Executar

Por ser uma aplicação **100% standalone**, basta abrir `index.html` (visão colaborador) ou `admin.html` (visão liderança) diretamente no navegador, ou publicar via **GitHub Pages / Vercel**.
