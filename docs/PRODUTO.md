# Produto — Contábil 4.0

## Proposta
Criar uma plataforma viva para o contador aprender, aplicar e acompanhar a transformação tecnológica da profissão. A assinatura dá acesso a uma base continuamente atualizada, em vez de vender apenas cursos isolados.

## Público
Contadores, auxiliares, analistas, gestores e escritórios contábeis, inclusive usuários com pouca experiência em IA e automação.

## Catálogo
1. Cursos e treinamentos.
2. Prompts prontos e explicados.
3. Automações e playbooks.
4. Conteúdo por software: Domínio, Questor, Jettax e outros homologados.
5. Atualizações contábeis, tributárias e tecnológicas.
6. Templates, checklists e materiais para download.
7. Trilhas por função e nível.
8. Produtos avulsos comercializáveis quando fizer sentido.
9. Conteúdo premium/exclusivo.
10. Certificados e histórico de progresso, quando implementados.

## Arquitetura comercial
A aplicação deve separar:
- produto;
- plano;
- preço;
- ciclo de cobrança;
- assinatura;
- entitlement/permissão;
- usuário;
- organização/escritório;
- conteúdo.

Assim, preços e nomes de planos podem mudar sem reescrever regras de acesso.

## Stack inicial
- Base44: aplicação.
- GitHub: fonte da verdade para requisitos, documentação e evolução.
- Asaas: checkout/cobrança recorrente.
- contabil40.com.br: domínio comercial.

## Métricas mínimas
MRR, ARR estimado, assinantes ativos, trials, conversão, churn, ticket médio, receita por plano, consumo de conteúdo, conclusão de trilhas e produtos mais utilizados.
