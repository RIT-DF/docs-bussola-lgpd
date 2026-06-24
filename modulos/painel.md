---
title: "Painel"
nav_order: 1
parent: "Módulos"
permalink: /modulos/painel/
role: encarregado
routes: ["#/", "#/wizard"]
screenshots: [blgpd-01-dashboard, blgpd-09-wizard]
last_verified: 2026-06-24
status: publicado
---

# Painel

O **Dashboard** é a primeira tela do Bússola LGPD: o cockpit onde o Encarregado vê, de relance, como anda a conformidade da OSC e o que falta fazer.

[![Dashboard do Bússola LGPD](/assets/screenshots/blgpd-01-dashboard.png)](/assets/screenshots/blgpd-01-dashboard.png)
*Visão geral com Índice de Conformidade, indicadores de atendimentos e visualizações das políticas.*

## Índice de Conformidade (MVP)

Um percentual que resume o progresso, dividido em dois grupos:

- **Verificados pelo Sistema** — o plugin confere sozinho: Política de Privacidade ativa, DPO configurado, banner de cookies ativo, inventário preenchido.
- **Autodeclarados (via Wizard)** — dependem da sua resposta: bases legais mapeadas, inventário concluído.

> ℹ️ Se você **[inativar](/modulos/politicas/#inativar-e-reativar-uma-politica)** a Política de Privacidade, o item "Política de Privacidade ativa" deixa de contar aqui — reative-a para o indicador voltar.

> ⚠️ **Atenção**
>
> O Índice é um **indicador de progresso interno**, não um certificado de conformidade. O próprio painel reforça: *"não constitui garantia jurídica de conformidade com a LGPD"*. Veja o [Aviso legal](/disclaimer/).

## Indicadores de atendimentos (DSAR)

Quatro números acompanham a saúde do atendimento aos titulares:

- **Pendentes (No Prazo)** e **Pendentes (Atrasadas)** — quantos pedidos aguardam e se estão dentro do SLA.
- **Concluídas** — pedidos já resolvidos.
- **Tempo Médio de Resposta** — quanto sua OSC costuma levar.

Há ainda o **Ranking de Solicitações** (quais tipos de pedido mais aparecem) e as **Visualizações das Políticas** (quantas vezes o público acessou suas políticas).

> 💡 **Por que isso importa**
>
> Esses números são ótimos para **prestar contas**: mostram a financiadores e ao conselho que a OSC atende titulares com agilidade e que suas políticas são efetivamente lidas. É accountability na prática — você demonstra cuidado com dados, não só afirma.

## Alertas e pendências

O painel sinaliza pontos de atenção — por exemplo, **consentimentos órfãos** (registros de consentimento que não estão ligados a uma versão de política). São pistas do que organizar a seguir.

## Ações rápidas

No alto do painel:

- **Exportar Relatório** — abre o [Relatório de Conformidade](/modulos/relatorios/) em PDF.
- **Revisar Autodeclaração** — abre o Wizard para responder às perguntas que alimentam o Índice.

[![Wizard de autodeclaração](/assets/screenshots/blgpd-09-wizard.png)](/assets/screenshots/blgpd-09-wizard.png)
*O Wizard de Onboarding LGPD coleta as respostas autodeclaradas (ex.: bases legais definidas?).*

## Veja também

- [O passo a passo da conformidade](/passo-a-passo-conformidade/)
- [Relatórios & Backup](/modulos/relatorios/)
