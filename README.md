# 🔴 Lista de Pokémon - Web React
Um aplicativo front-end simples e temático desenvolvido em **React** para listar pokémons. O projeto foi projetado como um exercício prático para aplicação de conceitos fundamentais da biblioteca React, incluindo componentização, passagem de propriedades (*props*), reset de CSS e encapsulamento de estilos utilizando **CSS Modules**.

---
## 🎯 Principais Recursos
- **Componentização Reutilizável:** Encapsulamento da exibição do Pokémon em um componente isolado `<Pokemon />`.
- **Passagem de Propriedades (Props):** O nome do Pokémon é enviado dinamicamente via propriedade para o card (`<Pokemon name="Pikachu" />`).
- **CSS Modules:** Utilização de arquivos `.module.css` para isolar a estilização de componentes e páginas, prevenindo conflitos globais de seletores.
- **Efeitos Visuais Interativos:** Cards temáticos (estilo amarelo Pokébola) que respondem à interação do usuário, alterando a cor de fundo para cinza e o texto para vermelho com transição suave ao passar o cursor (*hover*).
- **Fundo Temático:** Estilização global com background vermelho sólido e logotipo centralizado do universo Pokémon.
---
## 📂 Estrutura do Projeto
Abaixo está o mapeamento dos arquivos que compõem o ecossistema do aplicativo:
```bash
lista-de-pokemon-web-react/
├── public/
│   ├── favicon.ico          # Ícone de aba do navegador
│   └── index.html           # Documento HTML base
├── src/
│   ├── components/
│   │   └── Pokemon/
│   │       ├── index.jsx           # Componente de exibição do card do Pokémon
│   │       └── styles.module.css   # Estilos isolados do card (amarelo, hover e transições)
│   ├── img/
│   │   └── pokemon_logo.png # Logotipo oficial do Pokémon carregado na home
│   ├── pages/
│   │   └── Home/
│   │       ├── index.jsx           # Página principal que carrega os pokémons
│   │       └── styles.module.css   # Estilos da estrutura da Home (titulos, grids e alinhamentos)
│   ├── styles/
│   │   └── global.css       # Regras gerais de reset de CSS e definição do fundo vermelho
│   ├── index.js             # Ponto de entrada do React que inicializa a aplicação
│   └── [arquivos adicionais]
├── package.json             # Dependências de bibliotecas e scripts do projeto (CRA)
└── README.md                # Documentação do projeto
```
---
## 🛠️ Tecnologias Utilizadas
- [React v18](https://react.dev/) (Biblioteca JavaScript para interfaces de usuário)
- **CSS Modules:** Técnica nativa de importação de estilos isolados.
- **CSS3 (Customizado):** Estilização de hover e animações.
- **Create React App:** Ferramenta de inicialização do projeto e orquestrador de build.
---
## ⚙️ Pokémons Cadastrados Atualmente
Os seguintes pokémons são exibidos na listagem atual:
- ⚡ Pikachu
- 🔥 Charmander
- 🦖 Charizard
- 🐢 Squirtle
- 🧬 Ditto
---
## 💻 Como Rodar o Projeto
### Requisitos:
Certifique-se de possuir o [Node.js](https://nodejs.org/) instalado em sua máquina.
### Passo a Passo:
1. Abra o terminal na pasta raiz do projeto.
2. Instale as dependências declaradas no projeto executando o comando:
   ```bash
   npm install
   ```
3. Inicialize o servidor de desenvolvimento local:
   ```bash
   npm start
   ```
4. O navegador abrirá automaticamente o endereço: [http://localhost:3000](http://localhost:3000). Caso não abra, acesse manualmente pelo navegador.
