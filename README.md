# 📚 Projeto Concurso

[![GitHub stars](https://img.shields.io/github/stars/iagodevtech/projeto-concurso?style=social)](https://github.com/iagodevtech/projeto-concurso/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/iagodevtech/projeto-concurso?style=social)](https://github.com/iagodevtech/projeto-concurso/network)
[![GitHub last commit](https://img.shields.io/github/last-commit/iagodevtech/projeto-concurso?style=flat)](https://github.com/iagodevtech/projeto-concurso/commits)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=flat)](#)

Plataforma educacional voltada para concurseiros, focada em resolver questões de concursos anteriores para maximizar o aprendizado e preparação.

## ✨ Funcionalidades

- **Banco de Questões**: Milhares de questões de concursos anteriores
- **Simulados**: Testes cronometrados para prática
- **Análise de Performance**: Relatórios detalhados de desempenho
- **Categorização**: Questões organizadas por matéria e banca
- **Progressão**: Sistema de níveis e conquistas
- **Comunidade**: Fórum para discussão de questões

## 🛠️ Stack Tecnológica

### Frontend
- **React** - Biblioteca de interface
- **TypeScript** - Tipagem estática
- **Material-UI** - Componentes de interface
- **Chart.js** - Gráficos de performance
- **React Router** - Navegação SPA

### Backend & Database
- **Node.js** - Runtime JavaScript
- **Express** - Framework web
- **PostgreSQL** - Banco de dados relacional
- **Prisma** - ORM para banco de dados
- **JWT** - Autenticação

### Deploy
- **Docker** - Containerização
- **Vercel** - Deploy frontend
- **Railway** - Deploy backend

## 🚀 Quickstart

### Pré-requisitos
- Node.js 18+
- PostgreSQL 14+
- npm ou yarn

### 1. Clone o repositório
```bash
git clone https://github.com/iagodevtech/projeto-concurso.git
cd projeto-concurso
```

### 2. Instale as dependências
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

### 3. Configure o banco de dados
```bash
# Crie um banco PostgreSQL
createdb projeto_concurso

# Execute as migrações
cd backend
npx prisma migrate dev
npx prisma db seed
```

### 4. Configure as variáveis de ambiente
```bash
# Backend - .env
DATABASE_URL="postgresql://user:password@localhost:5432/projeto_concurso"
JWT_SECRET="your_jwt_secret"
PORT=5000

# Frontend - .env
REACT_APP_API_URL=http://localhost:5000
```

### 5. Execute o projeto
```bash
# Backend
cd backend
npm run dev

# Frontend (em outro terminal)
cd frontend
npm start
```

### 6. Acesse
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5000

## 📊 Funcionalidades Principais

### Sistema de Questões
- **Importação**: Importe questões de PDFs e arquivos
- **Categorização**: Organize por matéria, banca e nível
- **Filtros**: Busque por palavras-chave e tags
- **Estatísticas**: Veja taxa de acerto por matéria

### Simulados
- **Cronômetro**: Tempo real para cada questão
- **Modo Offline**: Faça simulados sem internet
- **Relatórios**: Análise detalhada de performance
- **Ranking**: Compare com outros usuários

### Dashboard
- **Progresso**: Acompanhe evolução nos estudos
- **Gráficos**: Visualize performance ao longo do tempo
- **Metas**: Defina e acompanhe objetivos
- **Lembretes**: Notificações de estudo

## 🎯 Matérias Disponíveis

- **Direito Constitucional**
- **Direito Administrativo**
- **Direito Penal**
- **Direito Civil**
- **Português**
- **Matemática**
- **Raciocínio Lógico**
- **Informática**

## 📱 Responsivo

- **Mobile First**: Otimizado para dispositivos móveis
- **PWA**: Funciona como app nativo
- **Offline**: Simulados funcionam sem internet
- **Sincronização**: Dados sincronizados entre dispositivos

## 🔧 Scripts Disponíveis

```bash
# Desenvolvimento
npm run dev          # Backend em modo dev
npm run start        # Frontend em modo dev

# Build
npm run build        # Build de produção
npm run test         # Executar testes

# Banco de dados
npm run db:migrate   # Executar migrações
npm run db:seed      # Popular banco com dados
npm run db:reset     # Resetar banco
```

## 📊 Estrutura do Projeto

```
projeto-concurso/
├── frontend/         # Aplicação React
├── backend/          # API Node.js
├── database/         # Scripts SQL e migrações
├── docs/             # Documentação
└── shared/           # Tipos compartilhados
```

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

- **LinkedIn**: [Iago Alves](https://www.linkedin.com/in/iago-alves-b502a518b/)
- **GitHub**: [@iagodevtech](https://github.com/iagodevtech)
- **Email**: iagodevtech@gmail.com

---

Desenvolvido com ❤️ por [Iago Alves](https://github.com/iagodevtech) 
