# Web App

Aplicação web moderna construída com React, TypeScript e Vite.

## 🛠️ Tecnologias

### Core
- **React 19** - Biblioteca para interfaces de usuário
- **TypeScript** - Tipagem estática para JavaScript
- **Vite** - Build tool e dev server

### Styling & UI
- **Tailwind CSS 4** - Framework CSS utilitário
- **shadcn/ui** - Componentes UI reutilizáveis
- **Lucide React** - Ícones
- **class-variance-authority** - Variantes de componentes
- **clsx & tailwind-merge** - Utilitários para classes CSS

### State Management & Data
- **TanStack Query** - Gerenciamento de estado do servidor
- **React Router DOM** - Roteamento

### Development Tools
- **Biome** - Linter e formatter
- **Ultracite** - Configuração de linting

## 📁 Estrutura do Projeto

```
src/
├── app.tsx          # Componente principal
├── main.tsx         # Entry point
├── index.css        # Estilos globais
├── pages/           # Páginas da aplicação
│   ├── create-room.tsx
│   └── room.tsx
└── lib/
    └── utils.ts     # Utilitários
```

## 🚀 Setup

### Pré-requisitos
- Node.js (versão 18 ou superior)
- pnpm (recomendado) ou npm

### Instalação

1. Clone o repositório
```bash
git clone <repository-url>
cd web
```

2. Instale as dependências
```bash
pnpm install
```

3. Execute o servidor de desenvolvimento
```bash
pnpm dev
```

A aplicação estará disponível em `http://localhost:5173`

## 📜 Scripts Disponíveis

- `pnpm dev` - Inicia o servidor de desenvolvimento
- `pnpm build` - Gera build de produção
- `pnpm preview` - Visualiza o build de produção

## ⚙️ Configurações

- **Aliases**: Configurado `@` para apontar para `./src`
- **Tailwind**: Configurado com tema "zinc" e variáveis CSS
- **Biome**: Configurado com Ultracite para linting e formatação
- **shadcn/ui**: Configurado com estilo "new-york" e Lucide icons

## 🎨 Padrões de Projeto

- Componentes funcionais com hooks
- TypeScript para tipagem estática
- Tailwind CSS para estilização
- shadcn/ui para componentes reutilizáveis
- Roteamento com React Router
- Gerenciamento de estado com TanStack Query 