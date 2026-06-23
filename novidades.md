---
title: "Novidades"
nav_order: 11
permalink: /novidades/
---

# Novidades

O que mudou no Bússola LGPD, em linguagem leve. Para o histórico técnico completo, fale com a equipe de implantação.

## Versão 1.1 — Retenção & ciclo de vida dos dados

A LGPD pede que dado pessoal não fique guardado para sempre. Esta versão automatiza o **fim** desse ciclo:

- **Expurgo automático com janela de aviso** — ao fim do prazo que você define, o plugin **anonimiza** o registro; antes disso, avisa o Encarregado (7 dias por padrão), que pode **cancelar ou adiar**.
- **Anonimização que preserva a prova** — em vez de apagar tudo, remove-se o que identifica a pessoa e mantém-se o comprovante de que a obrigação foi cumprida.
- **Prazos onde fazem sentido** — dados do próprio plugin (atendimentos concluídos, consentimentos revogados) nas Configurações; dados do site, **por atividade** no Inventário (ROPA), sempre com **opt-in** (nada entra sem você ligar).
- **Conectores prontos** para WordPress (usuários, comentários), WooCommerce e os principais plugins de formulário (CF7, Fluent Forms, Forminator, Gravity Forms, WPForms) — e um encaixe extensível para novas origens.
- **Mapeamento de Formulários** — uma tela que liga cada formulário do site a uma atividade do inventário, atalho para quem tem muitos formulários.
- **Fila de Retenção** no menu e **alerta no Painel** dos registros que vão expirar em breve.
- **Revogação de consentimento de verdade** — ao concluir um pedido de revogação, os consentimentos daquele e-mail passam a contar prazo para expurgo.

Veja o passo a passo em [Retenção & Expurgo](/modulos/retencao/).

## Versão 1.0 (MVP)

A primeira versão do produto entrega a base da conformidade para OSCs:

- **Painel de conformidade** com Índice (verificado + autodeclarado), indicadores de atendimentos (DSAR) e visualizações das políticas.
- **Gestão de políticas** com versionamento, aceite por versão, editor com checklist da LGPD, **Assistente** que pré-preenche a partir do DPO e do inventário, e **Galeria de Modelos**.
- **Central de Privacidade pública** gerada automaticamente, com políticas ativas, identidade do DPO e formulário de pedidos.
- **Atendimentos (DSAR)** com duplo opt-in, controle de prazo (SLA), **execução assistida** (localizar, exportar e eliminar sob comando do Encarregado) e **auto-atendimento** para pedidos simples.
- **Consentimento**: banner de cookies (scripts só carregam com consentimento) e conectores para formulários populares.
- **Incidentes**: registro e comunicação rastreável aos titulares afetados.
- **Inventário (ROPA)**: registro das operações de tratamento, com finalidade e base legal.
- **Relatórios**: relatório de conformidade em PDF e **backup/exportação total** dos dados (ZIP com CSV/JSON e checksums).
- **Webhooks** para integrar eventos essenciais a ferramentas como n8n e Zapier.
- **Manual integrado** no painel, com link para este guia completo.

> 💡 Os ajustes de performance, segurança e robustez seguem sendo aprimorados a cada ciclo. Veja o que vem por aí em [Roadmap](/roadmap/).
