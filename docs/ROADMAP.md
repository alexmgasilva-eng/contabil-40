# Roadmap de lançamento

## Fase 0 — Fundação
Documentação, catálogo inicial, modelo de dados, autenticação, RBAC, entitlements e ambientes.

## Fase 1 — Produto vendável
Landing, planos, checkout Asaas, webhooks idempotentes, assinatura, liberação/revogação de acesso e área do assinante.

## Fase 2 — Conteúdo
CMS/catálogo, cursos, prompts, automações, trilhas por assunto e por sistema, busca e downloads.

## Fase 3 — Experiência
Progresso, favoritos, certificados, recomendações, onboarding e comunicação.

## Fase 4 — Escritórios
Organizações, seats, convites, gestão de equipe e faturamento apropriado.

## Fase 5 — Gestão e escala
Analytics, churn, conversão, auditoria, observabilidade, LGPD, backups e operação editorial contínua.

## Gate de lançamento
Não liberar cobrança real antes de validar: autenticação/autorização, tenant isolation quando aplicável, webhook Asaas, idempotência, estados de assinatura, cancelamento/inadimplência, auditoria e testes E2E do fluxo de compra-acesso-revogação.
