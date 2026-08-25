# Vorto Studio

> Produto e engenharia de software para operações industriais configuráveis.

A **Vorto Studio** é uma iniciativa independente, em estágio inicial, dedicada a projetar software operacional para fabricantes de produtos sob medida e suas redes de revendas, parceiros e equipes de campo.

Estamos desenvolvendo uma plataforma modular para conectar configuração técnica, medição, cotação, pedidos, produção, estoque, qualidade, instalação e assistência. O trabalho atual está em **descoberta, validação de domínio e prototipação**; não representa uma solução pronta para produção.

## Direção do produto

- Domínio e processo real antes de telas ou escolhas de tecnologia.
- Migração incremental por capacidade, sem substituição integral do legado de uma só vez.
- Rastreabilidade da configuração ao produto instalado.
- Isolamento entre organizações e autorização verificada no servidor.
- Integração com serviços fiscais, contábeis, bancários e de folha, em vez de reconstruí-los.
- Web, mobile, chão de fábrica e integrações locais tratados conforme seus contextos de uso.

## Superfícies em definição

| Nome de trabalho | Finalidade | Estado |
| --- | --- | --- |
| **Vorto Gestão** | Administração, engenharia, PCP e coordenação operacional | Protótipo web |
| **Vorto Rede** | Revendas, lojas, arquitetos e parceiros | Protótipo web |
| **Vorto Campo** | Medição, instalação, assistência e vistorias | Planejamento |
| **Vorto Produção** | Chão de fábrica, estoque, qualidade e expedição | Planejamento |
| **Vorto Painel** | Indicadores e filas operacionais | Planejamento |
| **Vorto Conecta** | Integrações locais, máquinas, arquivos e sistemas legados | Planejamento |
| **Vorto Núcleo** | APIs, regras de negócio, identidade, dados e sincronização | Fundação técnica |

Os nomes acima são nomenclaturas de trabalho. A arquitetura comercial definitiva da suíte ainda será validada.

## Tecnologia atual

- Monorepo com pnpm e Turborepo.
- Aplicação web em Next.js, React e TypeScript.
- API em Fastify e TypeScript.
- Regras de domínio e componentes compartilhados em pacotes independentes.
- SQLite no desenvolvimento e PostgreSQL como alvo de produção.

Go e Flutter são possibilidades futuras para integrações e aplicações de campo. Não fazem parte da stack principal atual e somente serão adotados após requisitos e contratos estáveis.

## Repositórios

- [vorto-landing](https://github.com/vorto-studio/vorto-landing) — presença institucional em evolução.
- O núcleo do produto permanece privado enquanto domínio, segurança e estratégia são consolidados.

## Estado do projeto

A Vorto Studio não anuncia clientes, integrações ou capacidades como concluídos antes de validação e evidência no produto. Novidades públicas serão adicionadas conforme os módulos avancem de protótipo para piloto.
