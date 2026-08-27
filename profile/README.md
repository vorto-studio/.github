# Vorto

<p align="left">
  <img src="https://img.shields.io/badge/Architecture-Hexagonal_%2F_Ports_%26_Adapters-38BDF8?style=for-the-badge&logoColor=white" alt="Hexagonal Architecture" />
  <img src="https://img.shields.io/badge/Multi--Tenant-Native_Context_Isolation-34D399?style=for-the-badge&logoColor=white" alt="Multi Tenant" />
  <img src="https://img.shields.io/badge/Backend-Go_1.22+-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Frontend-Next.js_15_(App_Router)-black?style=for-the-badge&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL_16_(pgx)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

> **Engenharia de software de alta precisão, sistemas operacionais industriais e infraestrutura digital para manufatura sob medida e supply chain B2B.**

A **Vorto Studio** desenvolve soluções de tecnologia focadas em eliminar atritos operacionais entre indústrias manufatureiras, chão de fábrica e suas redes de parceiros comerciais homologados. Combinamos cálculo de engenharia de produto (BOM), rastreabilidade física por QR Code, gestão de docas e faturamento B2B em uma arquitetura unificada.

---

### 🏭 Ecossistema de Produtos

```text
                             ┌──────────────────────────────┐
                             │         VORTO STUDIO         │
                             │   (Núcleo de Engenharia)     │
                             └──────────────┬───────────────┘
                                            │
         ┌──────────────────────────────────┼──────────────────────────────────┐
         ▼                                  ▼                                  ▼
 ┌──────────────────────┐        ┌──────────────────────┐        ┌──────────────────────┐
 │  VORTO INDUSTRIAL    │        │    VORTO PARTNER     │        │     VORTO LABS       │
 │                      │        │                      │        │                      │
 │ • ERP/PCP Matriz     │        │ • Modo A: Extranet   │        │ • VoiceStock         │
 │ • Motor de Corte/BOM │        │   B2B (Sem atrito)   │        │   (Voz & Estoque)    │
 │ • Rastreio QR Code   │        │ • Modo B: Retail OS  │        │ • ZapProposta        │
 │ • Dispatch Hub Doca  │        │   (Gestão da Loja)   │        │   (Orçamentos Ágeis) │
 └──────────────────────┘        └──────────────────────┘        └──────────────────────┘
