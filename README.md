# AluraTube 📺

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Styled Components](https://img.shields.io/badge/Styled--Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)

O AluraTube é uma plataforma de compartilhamento de vídeos, similar ao YouTube, desenvolvida durante a **Imersão React da Alura**. O projeto foi construído utilizando uma stack moderna de front-end com **Next.js** e **React**, focando na criação de componentes reutilizáveis e em uma arquitetura escalável.

A aplicação exibe perfis de usuários, suas playlists de vídeos favoritas e permite a busca de conteúdo, tudo com base em um arquivo de configuração que simula uma fonte de dados.

---

## ✨ Funcionalidades

-   **Página Inicial Dinâmica**: Exibe o banner do canal, informações do usuário e seções de playlists de vídeos.
-   **Componentização com React**: A interface é construída com componentes reutilizáveis, como `Header`, `Timeline` e `Favorites`.
-   **Estilização com Styled Components**: Garante um estilo visualmente consistente e encapsulado por componente.
-   **Busca de Vídeos**: Uma funcionalidade de filtro permite que o usuário busque vídeos por título dentro das playlists.
-   **Estrutura com Next.js**: Aproveita os benefícios de renderização e roteamento do framework Next.js.

---

## 🛠️ Tecnologias Utilizadas

-   **Next.js**: Framework React para renderização no lado do servidor (SSR) e geração de sites estáticos (SSG).
-   **React**: Biblioteca para a construção de interfaces de usuário baseadas em componentes.
-   **Styled Components**: Para a estilização dos componentes, permitindo CSS-in-JS com escopo local.

---

## 🚀 Como Executar o Projeto

Para rodar o AluraTube em seu ambiente de desenvolvimento, siga os passos abaixo.

### Pré-requisitos
-   [Node.js](https://nodejs.org/) (versão 16 ou superior)
-   [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

### Instalação e Execução

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd aluratube
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    # ou
    yarn dev
    ```

5.  **Abra o navegador**: A aplicação estará disponível em `http://localhost:3000`.

---

## 📂 Estrutura de Dados

Os dados dos vídeos e usuários são carregados a partir do arquivo `imersao-config.json`, que simula a resposta de uma API. Isso permite o desenvolvimento do front-end de forma desacoplada de um back-end.

```json
{
  "name": "Michael Marin",
  "job": "Front-End Student",
  "github": "michaelwmarin",
  "playlists": {
    "jogos": [
      {
        "title": "Frostpunk - Review",
        "url": "[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)...",
        "thumb": "[https://img.youtube.com/vi/.../hqdefault.jpg](https://img.youtube.com/vi/.../hqdefault.jpg)"
      }
    ]
  }
}
