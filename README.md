# NLW Agents

Projeto desenvolvido durante o evento NLW da Rocketseat. Trata-se de um chat interativo com integração à API Gemini.

## Tecnologias e Bibliotecas

- **React 19** – Biblioteca principal para construção da interface.
- **TypeScript** – Tipagem estática para maior segurança.
- **Vite** – Bundler e servidor de desenvolvimento rápido.
- **React Router DOM** – Gerenciamento de rotas SPA.
- **@tanstack/react-query** – Gerenciamento de dados assíncronos.
- **Tailwind CSS** – Utilitário CSS para estilização rápida.
- **class-variance-authority, clsx, tailwind-merge** – Utilitários para composição de classes CSS.
- **Radix UI** – Componentes acessíveis e semânticos.
- **Lucide React** – Ícones SVG.

## Padrões de Projeto

- **Componentização**: Componentes reutilizáveis em `src/components`.
- **Hooks e Utils**: Funções utilitárias em `src/lib`.
- **Rotas**: Definidas em `src/app.tsx` usando React Router.
- **Estilização**: Tailwind CSS com variáveis customizadas e suporte a dark mode.

## Setup e Configuração

1. **Clone o repositório**
   ```sh
   git clone <url-do-repo>
   cd web
Collecting workspace information```md
# NLW Agents

Projeto desenvolvido durante o evento NLW da Rocketseat. Trata-se de um chat interativo com integração à API Gemini.

## Tecnologias e Bibliotecas

- **React 19** – Biblioteca principal para construção da interface.
- **TypeScript** – Tipagem estática para maior segurança.
- **Vite** – Bundler e servidor de desenvolvimento rápido.
- **React Router DOM** – Gerenciamento de rotas SPA.
- **@tanstack/react-query** – Gerenciamento de dados assíncronos.
- **Tailwind CSS** – Utilitário CSS para estilização rápida.
- **class-variance-authority, clsx, tailwind-merge** – Utilitários para composição de classes CSS.
- **Radix UI** – Componentes acessíveis e semânticos.
- **Lucide React** – Ícones SVG.

## Padrões de Projeto

- **Componentização**: Componentes reutilizáveis em `src/components`.
- **Hooks e Utils**: Funções utilitárias em `src/lib`.
- **Rotas**: Definidas em `src/app.tsx` usando React Router.
- **Estilização**: Tailwind CSS com variáveis customizadas e suporte a dark mode.

## Setup e Configuração

1. **Clone o repositório**
   
   git clone <url-do-repo>
   cd web
   

2. **Instale as dependências**
   
   npm install
   

3. **Configure o Tailwind CSS**
   - O arquivo principal de estilos é `src/index.css`.
   - Certifique-se de que o plugin Tailwind está configurado no Vite (`vite.config.ts`).

4. **Inicie o servidor de desenvolvimento**
   
   npm run dev
   

5. **Build de produção**
   
   npm run build
   

## Observações

- O projeto utiliza variáveis CSS para temas e dark mode.
- As rotas principais estão em `src/pages`.
- Certifique-se de que a API backend esteja rodando em `http://localhost:3333`.

---

Desenvolvido durante o evento NLW Agents da Rocketseat.

   