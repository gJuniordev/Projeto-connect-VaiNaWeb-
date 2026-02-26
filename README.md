<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
</div>

🚀 # **Plataforma Connect**
A Plataforma Connect é um ecossistema digital desenvolvido com React para centralizar e facilitar ações de impacto social. O projeto conecta usuários a oportunidades de mentoria, voluntariado e fluxos de doação, utilizando uma arquitetura moderna focada em performance e manutenibilidade.

---

🛠️ # **Stack Tecnológica**
O projeto foi construído utilizando as melhores práticas do ecossistema Front-end:

React: Biblioteca core para construção de interfaces baseadas em componentes.
Sass (SCSS Modules): Utilizado para estilização modular, garantindo que o CSS de um componente (ex: header.module.scss) não afete outros elementos da página.
JavaScript (ES6+): Lógica moderna para manipulação de estados e efeitos.

---

📂 # **Organização e Arquitetura**
A estrutura de pastas reflete uma preocupação com a escalabilidade do código:

components/: UI dividida em unidades atômicas (Header, Footer, InfoCard).
pages/: Views principais que compõem a navegação (Home, Doação, Mentoria, etc.).
hook/: Centralização de lógicas customizadas para manter os componentes limpos.
assets/: Organização de ativos estáticos divididos entre ícones e imagens.

---

🔍 # **Destaques Técnicos**
Nesta seção, detalho algumas soluções implementadas que demonstram o domínio de lógica e reutilização de código:

🪝 Custom Hook: useClickOutside
Implementei este hook para gerenciar interações de fechamento de menus e modais de forma inteligente.
Função: Detecta cliques fora de um elemento específico (referenciado via useRef) para disparar uma ação (como fechar um dropdown).
Benefício: Melhora a experiência do usuário (UX) e evita repetição de lógica em múltiplos componentes.

---

🍱 # **Componente: InfoCard**
Um componente versátil e estilizado via SCSS Modules.
Flexibilidade: Projetado para receber diferentes conteúdos e ícones, sendo utilizado em diversas áreas da plataforma (Mentoria, Voluntariado, etc).
Encapsulamento: O uso de .module.scss garante que o design do card seja consistente e imune a vazamentos de estilo globais.

---

🚀 # **Como Executar o Projeto**
Clone o repositório:
```bash
git clone https://github.com/seu-usuario/plataforma-connect.git
```

Instale as dependências:
```bash
npm install
```

Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

---

🤝 # **Autor**
Desenvolvido por Gilcélio Júnior – Aula Vai na Web
