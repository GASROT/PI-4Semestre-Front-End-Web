 Projeto Front-end Web

Este é o repositório do front-end da aplicação, construído com tecnologias modernas para garantir alta performance e uma excelente experiência de desenvolvimento.

## 🚀 Tecnologias Utilizadas

Este projeto utiliza a seguinte stack:

- **[Vite](https://vitejs.dev/)**: Uma ferramenta de build extremamente rápida que substitui o Webpack ou o Create React App. Ele oferece um servidor de desenvolvimento com Hot Module Replacement (HMR) instantâneo e builds otimizados.
- **[React](https://react.dev/)**: Biblioteca JavaScript para a construção de interfaces de usuário (UI) baseadas em componentes reutilizáveis.
- **[React Router](https://reactrouter.com/)**: A biblioteca padrão para roteamento no React. Permite a navegação entre diferentes páginas/visões da aplicação (Single Page Application - SPA) sem recarregar a página no navegador.

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)

## 🛠️ Como iniciar o projeto

Siga os passos abaixo para rodar a aplicação no seu ambiente local:

**1. Clone o repositório**
```bash
git clone https://github.com/GASROT/PI-4Semestre-Front-End-Web.git
cd PI-4Semestre-Front-End-Web
```

**2. Instale as dependências**
Usando npm:
```bash
npm install
```
*(Ou use `yarn install` / `pnpm install` dependendo da sua preferência)*


**3. Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

Após executar o comando acima, o Vite iniciará um servidor local. Basta abrir o navegador e acessar a URL informada no terminal (geralmente `http://localhost:5173`).

## 📦 Scripts Disponíveis

No diretório do projeto, você pode rodar os seguintes comandos:

- `npm run dev`: Inicia a aplicação em modo de desenvolvimento.
- `npm run build`: Cria uma versão otimizada da aplicação para produção na pasta `dist`.
- `npm run preview`: Inicia um servidor web local para visualizar o build de produção gerado.

## 📂 Estrutura de Diretórios Recomendada

Uma sugestão inicial de estrutura para projetos usando Vite + React Router:

```text
├── public/            # Arquivos estáticos (favicon, etc) que não passam pelo build
├── src/
│   ├── assets/        # Imagens, fontes, etc.
│   ├── components/    # Componentes reutilizáveis (Botões, Inputs, etc.)
│   ├── pages/         # Componentes que representam as páginas/rotas da aplicação
│   ├── routes/        # Configuração das rotas do React Router
│   ├── App.jsx        # Componente raiz
│   └── main.jsx       # Ponto de entrada do React e renderização no DOM
├── index.html         # Template HTML principal (onde o Vite injeta os scripts)
├── package.json       # Dependências e scripts do projeto
└── vite.config.js     # Configurações do Vite
```