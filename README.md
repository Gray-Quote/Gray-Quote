# Gray Quote | Web Studio & B2B Solutions

## 🎯 Proposta de Valor

- **Propósito:** Plataformas e catálogos B2B de alta performance para aceleração de vendas.
- **Segmentos:** Construção Civil, Imóveis e Indústria.
- **Diferencial:** Carregamento instantâneo + Conversão direta via WhatsApp.

## ⚡ Manifesto & Arquitetura

Desenvolvemos ecossistemas web modernos projetados para velocidade extrema, arquitetura escalável e conversão direta de vendas (B2B). Eliminamos o overhead de CMSs legados e arquiteturas pesadas para entregar produtos focados no Core Web Vitals e na melhor experiência mobile.
- 🚀 **Performance First:** Aplicações com tempo de carregamento < 1s, SSR/ISR e otimização avançada de ativos.
- 📦 **Zero-Hassle Infrastructure:** Painéis administrativos nativos em TypeScript para o cliente final gerenciar conteúdos sem quebrar o layout.
- 🎯 **Foco em Resultados:** Interfaces limpas, minimalistas e otimizadas para roteamento de leads B2B (WhatsApp/CRM).

## 🛠️ Core Tech Stack

Nossa stack é selecionada para garantir máxima margem de performance, segurança e usabilidade:
- **Front-end & Framework:** Next.js (App Router), React, TypeScript, Tailwind CSS
- **CMS & Back-end:** Payload CMS 3.0 (Self-hosted/Serverless), FastAPI
- **Database & Storage:** PostgreSQL (Neon), Uploadthing, S3
- **Deploy & Infra:** Vercel, Cloudflare, Docker

## 📂 Estrutura de Ecossistema (Gray Quote Core)

```
grayquote/
├── apps/
│   ├── web/          # Aplicação principal e vitrine corporativa (Next.js)
│   └── admin/        # Core do Payload CMS e schemas de coleções
└── packages/
    ├── ui/           # Design System & componentes desacoplados
    └── config/       # Configurações compartilhadas de TS, ESLint e Tailwind
```
