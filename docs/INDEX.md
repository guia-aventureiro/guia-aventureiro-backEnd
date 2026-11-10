# 📚 Documentação - Guia Aventureiro

**Hub central da documentação do projeto**

---

## 📋 Visão Geral

Bem-vindo à documentação do **Guia Aventureiro**! Este é o ponto central para toda a informação do projeto.

### 🎯 O que é o Guia Aventureiro?

Plataforma mobile e web para criação, planejamento e compartilhamento de roteiros de viagem personalizados, com sistema de assinatura premium, gamificação e integração com Stripe.

---

## 🗂️ Navegação Rápida

### 📖 Para Começar

- [README Principal](../README.md) - Visão geral do projeto
- [Guia de Contribuição](../CONTRIBUTING.md) - Como contribuir
- [FAQ](../FAQ.md) - Perguntas frequentes
- [Roadmap](../ROADMAP.md) - Planejamento e milestones
- [Plano de MVP e custos de IA](./business/MVP_LANCAMENTO_E_CONTROLE_DE_CUSTOS.md) - Direção atual do produto e do lançamento
- [Archive](../archive/) - Documentação histórica

### 🏗️ Arquitetura

- [Visão Geral da Arquitetura](./architecture/OVERVIEW.md)

### 🌐 API & Integrações

- [Documentação da API](../API.md) - Endpoints e schemas
- [Integração Stripe](./STRIPE.md) - Pagamentos e assinaturas

### 📱 Mobile (React Native)

- [Best Practices](../mobile/MOBILE_BEST_PRACTICES.md) - Padrões mobile
- [Design System](../mobile/src/theme/) - Theme tokens

### ⚙️ Backend (Node.js)

- [Best Practices](../backend/BACKEND_BEST_PRACTICES.md) - Padrões backend
- [Constants](../backend/src/constants/) - Códigos de erro, limites
- [Helpers](../backend/src/helpers/) - Funções utilitárias
- [Validators](../backend/src/validators/) - Schemas Joi

### 🚀 Deploy & Produção

- [Deploy Checklist](./deployment/DEPLOY_CHECKLIST.md)
- [Stripe Go-Live](./deployment/STRIPE_GO_LIVE_CHECKLIST.md)
- [App Store Descriptions](./deployment/APP_STORE_DESCRIPTIONS.md)

### 🧪 Testes & Automação

- [Testing Best Practices](../automation/TESTING_BEST_PRACTICES.md)
- [Guia de Automação](../automation/README.md)

### 💰 Orçamento & Custos

- [Orçamento](./business/ORCAMENTO.md) - Custos AWS, Stripe, etc.
- [MVP, planos e controle de custos](./business/MVP_LANCAMENTO_E_CONTROLE_DE_CUSTOS.md)

---

## 📂 Estrutura da Documentação

```
docs/
├── INDEX.md                 # 📍 Você está aqui
├── STRIPE.md                # Integração Stripe
├── privacy.html             # Política de Privacidade
├── terms.html               # Termos de Uso
├── index.html               # Landing page docs legais
├── architecture/            # Arquitetura do sistema
│   └── OVERVIEW.md
├── deployment/              # Deploy e produção
│   ├── DEPLOY_CHECKLIST.md
│   ├── STRIPE_GO_LIVE_CHECKLIST.md
│   └── APP_STORE_DESCRIPTIONS.md
└── business/                # Negócio, MVP e orçamento
    ├── MVP_LANCAMENTO_E_CONTROLE_DE_CUSTOS.md
    └── ORCAMENTO.md
```

---

## 🔍 Busca Rápida por Tópico

### Autenticação

- [API - Rotas de Auth](../API.md#autenticação)
- [JWT & SecureStore](../mobile/MOBILE_BEST_PRACTICES.md#state-management)
- [Middleware de Auth](../backend/BACKEND_BEST_PRACTICES.md#middleware)

### Pagamentos (Stripe)

- [Integração Stripe](./STRIPE.md)
- [Webhooks](./STRIPE.md#webhooks)

### Upload de Imagens

- [Guia de integração mobile](../mobile/INTEGRATION_GUIDE.md)
- [Limites de Arquivo](../backend/src/constants/limits.js)

### Notificações

- [Setup Mobile](../mobile/INTEGRATION_GUIDE.md)

### Testes

- [Testing Best Practices](../automation/TESTING_BEST_PRACTICES.md)

### Deploy

- [Checklist Completo](./deployment/DEPLOY_CHECKLIST.md)
- [Stripe Go-Live](./deployment/STRIPE_GO_LIVE_CHECKLIST.md)
- [App Store Upload](./deployment/APP_STORE_DESCRIPTIONS.md)

---

## 🆘 Precisa de Ajuda?

1. **Antes de começar**: Leia o [README Principal](../README.md)
2. **Problemas comuns**: Confira o [FAQ](../FAQ.md)
3. **Contribuindo**: Veja o [Guia de Contribuição](../CONTRIBUTING.md)
4. **Dúvidas técnicas**: Consulte os [Best Practices](../backend/BACKEND_BEST_PRACTICES.md) ou [Mobile](../mobile/MOBILE_BEST_PRACTICES.md)

---

## 📊 Status do Projeto

- **Backend**: ✅ Produção (Node.js + MongoDB + Stripe)
- **Mobile**: ✅ Produção (React Native + Expo)
- **Testes**: ✅ CI automatizado; consultar o workflow para o resultado atual
- **Documentação**: ✅ Índice consolidado; documentos históricos em `archive/`

---

## 🎯 Próximos Passos

Veja o [Roadmap completo](../ROADMAP.md) para features planejadas.

---

**📝 Última atualização**: Agosto 2026
**👤 Mantenedor**: Equipe Guia Aventureiro
**📧 Contato**: [adicionar email]
