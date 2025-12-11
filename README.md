📱 Zingen – Página Responsiva | Projeto de Estudos

O Zingen é um projeto desenvolvido com foco total em responsividade, boas práticas de CSS, mobile-first, componentização e uso eficiente de variáveis CSS.
O objetivo do projeto é aprimorar habilidades essenciais no front-end moderno, explorando:

Arquitetura CSS escalável

Flexbox e CSS Grid

Design responsivo a partir do mobile

Separação modular de estilos

Criação de componentes reutilizáveis (botões, cards, containers, utilidades…)

Este projeto foi construído reproduzindo a landing page de um app fictício de karaokê chamado Zingen, aplicando técnicas reais usadas no mercado.

🚀 Tecnologias Utilizadas
HTML5

Estrutura semântica bem definida

Navegação por âncoras

Organização em seções claras (Hero, About, Features, Pricing, Download, Footer)
→ Código base em: 

index

CSS3

Com separação de arquivos para facilitar manutenção e escalabilidade:

global.css — Reset, variáveis, tipografia e estilos globais 

global

index.css — Importa todos os módulos CSS do projeto 

index

utility.css — Classes utilitárias (container, espaçamentos, grid/flex helpers) 

utility

buttons.css — Sistema de botões totalmente estilizado via variáveis 

buttons

cards.css — Estilo base dos componentes de card 

cards

Outras folhas importadas incluem header, hero, features, pricing, download e footer.


✔ Consolidar conceitos essenciais de CSS:

Mobile-First

Variáveis CSS para cores, tamanhos, espaçamentos e fontes

Flexbox

Grid Layout

Modularização e reutilização de estilos

Responsividade em grandes breakpoints (ex.: 80em)

✔ Treinar organização e escalabilidade:

Separação de estilos por função (botões, cards, layout, seções)

Reaproveitamento de componentes

Utilização de classes utilitárias para agilizar o desenvolvimento

✔ Aprender padrões de landing pages modernas:

Hero atrativa

Seções com grids responsivos

Cards informativos

CTAs destacados

Layout limpo e moderno

📐 Conceitos de CSS Aplicados
🟣 Mobile-First

Todo o layout começa com estilos para telas pequenas e só depois recebe ajustes para desktops usando media queries — como visto em utility.css e global.css.

🟣 Variáveis CSS

O projeto utiliza um design system completo:

:root {
  --bg-color: #09090B;
  --brand-color-primary: #F7B733;
  --fs-xl: 1.5rem;
  --py-xl: 3rem;
  ...
}


Isso facilita a manutenção e garante consistência visual.
Fonte: 

global

🟣 Flexbox e Grid

Utilizados em:

Navegação

Hero

Cards de funcionalidades

Layout de preços

Footer

Fonte das utilidades: 

utility

🟣 Componentização

Sistema de botões com estados de hover e gradient

Cards universais para seções

Containers padronizados

📂 Estrutura do Projeto
/
├── index.html
├── styles/
│   ├── global.css
│   ├── index.css
│   ├── utility.css
│   ├── buttons.css
│   ├── cards.css
│   ├── social.css
│   ├── sections.css
│   ├── header.css
│   ├── hero.css
│   ├── about.css
│   ├── features.css
│   ├── pricing.css
│   ├── download.css
│   └── footer.css
└── assets/

🖼 Preview do Projeto


DESKTOP:
![Imagem do WhatsApp de 2025-12-11 à(s) 11 39 16_20373d58](https://github.com/user-attachments/assets/441e6223-8f71-4eaf-8195-dbccbb908293)
![Imagem do WhatsApp de 2025-12-11 à(s) 11 39 38_7a4dabab](https://github.com/user-attachments/assets/7eeea321-d82c-4a5c-9416-c14bb91a4eb7)
![Imagem do WhatsApp de 2025-12-11 à(s) 11 40 31_dbc7e487](https://github.com/user-attachments/assets/6d36034a-7099-467c-96b3-8cc879a497db)
![Imagem do WhatsApp de 2025-12-11 à(s) 11 41 00_1b3d1644](https://github.com/user-attachments/assets/d02edf53-2c6d-4691-8542-7e008763d1d5)





MOBILE:


![Imagem do WhatsApp de 2025-12-11 à(s) 11 44 58_32a0bdbb](https://github.com/user-attachments/assets/d63a7462-f504-4e33-8b98-18b8411ac48b)

![Imagem do WhatsApp de 2025-12-11 à(s) 11 44 57_60aa9a2f](https://github.com/user-attachments/assets/cb144ed6-4dac-4f56-b40b-69ae0709d339)

![Imagem do WhatsApp de 2025-12-11 à(s) 11 44 57_634d9ce7](https://github.com/user-attachments/assets/9a0e28b5-d4ce-4e94-81b8-655314f3d52b)

![Imagem do WhatsApp de 2025-12-11 à(s) 11 44 56_6ae971e8](https://github.com/user-attachments/assets/69b82da1-4e4e-45c2-b9f3-5af0fad60a46)



🛠 Como Executar

Baixe ou clone o repositório

Abra o arquivo index.html no navegador

Pronto! Não há dependências externas nem build
