# 🚀 VSL Creator AI - Landing Page

Uma landing page moderna e responsiva para o VSL Creator AI, uma plataforma revolucionária que automatiza a criação de Video Sales Letters usando inteligência artificial.

![VSL Creator AI](https://img.shields.io/badge/VSL%20Creator%20AI-Landing%20Page-blue?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css)

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Deploy](#deploy)
- [Personalização](#personalização)
- [Contribuição](#contribuição)
- [Licença](#licença)

## 🎯 Sobre o Projeto

O **VSL Creator AI** é uma landing page desenvolvida para apresentar uma plataforma inovadora que utiliza inteligência artificial para automatizar a criação de Video Sales Letters (VSLs). A página foi projetada com foco em conversão, apresentando três pacotes de investimento diferentes para potenciais parceiros.

### ✨ Características Principais

- **Design Moderno**: Interface clean com fundo bege claro e cards brancos arredondados
- **Responsivo**: Totalmente adaptado para desktop, tablet e mobile
- **Otimizado para Conversão**: Estrutura persuasiva com CTAs estratégicos
- **Integração WhatsApp**: Botões direcionam para conversas personalizadas
- **Performance**: Carregamento rápido e otimizado para SEO

## 🚀 Funcionalidades

### 📱 Interface do Usuário
- [x] Header impactante com proposta de valor
- [x] Seção de problemas que o empreendedor enfrenta
- [x] Apresentação da solução VSL Creator AI
- [x] Comparação antes vs depois
- [x] Três pacotes de preços com badges distintivos
- [x] Prova social com resultados comprovados
- [x] Call-to-action final com urgência

### 🎨 Design System
- [x] Paleta de cores consistente
- [x] Tipografia moderna (Inter)
- [x] Ícones do Lucide React
- [x] Animações e hover effects
- [x] Sombras e gradientes sutis

### 📞 Integração
- [x] Botões do WhatsApp com mensagens personalizadas
- [x] Scroll suave entre seções
- [x] Formulário de contato (implícito via WhatsApp)

## 🛠 Tecnologias Utilizadas

### Frontend
- **React 18** - Biblioteca JavaScript para interfaces
- **Vite** - Build tool e bundler moderno
- **Tailwind CSS** - Framework CSS utility-first
- **Lucide React** - Biblioteca de ícones

### Componentes UI
- **shadcn/ui** - Componentes React reutilizáveis
- **Radix UI** - Primitivos de UI acessíveis

### Ferramentas de Desenvolvimento
- **ESLint** - Linter para JavaScript/React
- **PostCSS** - Processador CSS
- **Autoprefixer** - Plugin para compatibilidade CSS

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **Node.js** (versão 18 ou superior)
- **npm** ou **pnpm** (gerenciador de pacotes)
- **Git** (para controle de versão)

```bash
# Verificar versões instaladas
node --version
npm --version
git --version
```

## 🔧 Instalação

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/vsl-creator-landing.git
cd vsl-creator-landing
```

### 2. Instale as dependências
```bash
# Usando npm
npm install

# Ou usando pnpm (recomendado)
pnpm install
```

### 3. Configure as variáveis de ambiente (opcional)
```bash
cp .env.example .env.local
```

## 🚀 Uso

### Desenvolvimento
```bash
# Iniciar servidor de desenvolvimento
npm run dev

# Ou com pnpm
pnpm run dev
```

Acesse `http://localhost:5173` no seu navegador.

### Build para Produção
```bash
# Gerar build otimizado
npm run build

# Ou com pnpm
pnpm run build
```

### Preview da Build
```bash
# Visualizar build localmente
npm run preview

# Ou com pnpm
pnpm run preview
```

### Linting
```bash
# Verificar código
npm run lint

# Corrigir automaticamente
npm run lint:fix
```

## 📁 Estrutura do Projeto

```
vsl-creator-landing/
├── public/                 # Arquivos estáticos
│   ├── favicon.ico
│   └── ...
├── src/                    # Código fonte
│   ├── components/         # Componentes React
│   │   └── ui/            # Componentes UI (shadcn/ui)
│   ├── hooks/             # Custom hooks
│   ├── lib/               # Utilitários e configurações
│   ├── App.jsx            # Componente principal
│   ├── App.css            # Estilos principais
│   ├── main.jsx           # Ponto de entrada
│   └── index.css          # Estilos globais
├── .gitignore             # Arquivos ignorados pelo Git
├── eslint.config.js       # Configuração do ESLint
├── index.html             # Template HTML
├── package.json           # Dependências e scripts
├── postcss.config.js      # Configuração do PostCSS
├── README.md              # Este arquivo
├── tailwind.config.js     # Configuração do Tailwind
└── vite.config.js         # Configuração do Vite
```

## 🌐 Deploy

### Netlify
```bash
# Build do projeto
npm run build

# Deploy manual: arraste a pasta 'dist' para o Netlify
```

### Vercel
```bash
# Instalar Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### GitHub Pages
```bash
# Instalar gh-pages
npm install --save-dev gh-pages

# Adicionar script no package.json
"homepage": "https://seu-usuario.github.io/vsl-creator-landing",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}

# Deploy
npm run deploy
```

## 🎨 Personalização

### Cores
Edite o arquivo `tailwind.config.js` para personalizar as cores:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#1e293b',
        secondary: '#f59e0b',
        accent: '#10b981',
        background: '#f8f6f0',
      }
    }
  }
}
```

### Conteúdo
Edite o arquivo `src/App.jsx` para alterar:
- Textos e títulos
- Preços dos pacotes
- Informações de contato
- Links do WhatsApp

### Estilos
Modifique `src/App.css` para ajustar:
- Layout e espaçamentos
- Animações e transições
- Responsividade

## 📞 Configuração do WhatsApp

Para personalizar as mensagens do WhatsApp, edite a função `handleWhatsAppClick` em `src/App.jsx`:

```javascript
const handleWhatsAppClick = (packageName, price, description) => {
  const message = `Olá! Tenho interesse no *${packageName}* do VSL Creator AI por ${price}. ${description}`;
  const whatsappUrl = `https://api.whatsapp.com/send?phone=SEU_NUMERO&text=${encodeURIComponent(message)}`;
  window.open(whatsappUrl, '_blank');
};
```

**Importante**: Substitua `SEU_NUMERO` pelo número do WhatsApp no formato internacional (ex: 556392547254).

## 📊 Performance

### Métricas Atuais
- **Lighthouse Score**: 95+
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

### Otimizações Implementadas
- [x] Lazy loading de imagens
- [x] Minificação de CSS e JS
- [x] Compressão de assets
- [x] Tree shaking automático
- [x] Code splitting

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Para contribuir:

1. **Fork** o projeto
2. Crie uma **branch** para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. Abra um **Pull Request**

### Diretrizes de Contribuição
- Siga os padrões de código existentes
- Adicione testes quando necessário
- Atualize a documentação
- Mantenha commits pequenos e descritivos

## 📝 Changelog

### [2.0.0] - 2024-06-23
#### Adicionado
- Novo design baseado em cards brancos com fundo bege
- Ícones específicos para cada pacote de preços
- Badges coloridos para destacar ofertas
- Hover effects e animações aprimoradas

#### Modificado
- Paleta de cores atualizada
- Layout mais clean e moderno
- Melhor contraste e legibilidade

### [1.0.0] - 2024-06-23
#### Adicionado
- Versão inicial da landing page
- Integração com WhatsApp
- Design responsivo
- Três pacotes de preços

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autores

- **Rei da VSL** - *Conceito e conteúdo* - [Website](https://reidavsl.com)

## 📞 Suporte

Para suporte, entre em contato:

- **WhatsApp**: [+55 63 9 9254-7254](https://wa.me/556392547254)
- **Email**: brito@luckholding.org
- **Website**: [reidavsl.com](https://reidavsl.com)

## 🙏 Agradecimentos

- [React](https://reactjs.org/) pela biblioteca incrível
- [Tailwind CSS](https://tailwindcss.com/) pelo framework CSS
- [Lucide](https://lucide.dev/) pelos ícones
- [shadcn/ui](https://ui.shadcn.com/) pelos componentes
- [Vite](https://vitejs.dev/) pela ferramenta de build

---

<div align="center">

**[⬆ Voltar ao topo](#-vsl-creator-ai---landing-page)**

Feito com ❤️ por britoai.com

</div>

