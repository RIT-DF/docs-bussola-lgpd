---
title: "Painel"
nav_order: 1
parent: "Módulos"
permalink: /modulos/painel/
role: encarregado
routes: ["#/", "#/wizard"]
screenshots: [blgpd-01-dashboard, blgpd-50-mapa-conformidade]
last_verified: 2026-06-24
status: publicado
---

# Painel

O **Dashboard** é a primeira tela do Bússola LGPD: o cockpit onde o Encarregado vê, de relance, como anda a conformidade da OSC e o que falta fazer.

[![Dashboard do Bússola LGPD](/assets/screenshots/blgpd-01-dashboard.png)](/assets/screenshots/blgpd-01-dashboard.png)
*Visão geral com Índice de Conformidade, indicadores de atendimentos e visualizações das políticas.*

## Índice de Conformidade (MVP)

O card mostra, de um lado, a **lista do que é verificado pelo sistema** (Política de Privacidade ativa, DPO configurado, Consentimento/Cookies, Central de Privacidade, Inventário) — cada item com o **artigo da LGPD** correspondente; do outro, um **anel** com o **percentual verificado** e, separado e em roxo, o indicador **"Atestado: X de 4"** (a parte autodeclarada, que **não** infla o percentual).

O selo **"ⓘ Por que isto importa (LGPD)"** abre uma explicação curta com o artigo da Lei e links para o Manual, o texto oficial (Planalto) e a ANPD.

> ℹ️ Os **atestados** (autodeclaração) e o detalhamento artigo a artigo ficam no **[Mapa de Conformidade](#mapa-de-conformidade)** — acesse pelo botão **"Ver mapa completo"** ou pelo menu.

> ℹ️ Se você **[inativar](/modulos/politicas/#inativar-e-reativar-uma-politica)** a Política de Privacidade, o item "Política de Privacidade Ativa" deixa de contar aqui — reative-a para o indicador voltar.

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

O painel sinaliza pontos de atenção — por exemplo, **nenhuma política de privacidade vigente** (com atalho para criar uma). São pistas do que organizar a seguir.

## Ações rápidas

No alto do painel:

- **Exportar Relatório** — abre o [Relatório de Conformidade](/modulos/relatorios/) em PDF.
- **Ver mapa completo** — abre o [Mapa de Conformidade](#mapa-de-conformidade) (detalhe artigo a artigo + autodeclaração).

## Mapa de Conformidade

Acessível pelo menu **"Mapa de Conformidade"** (ou pelo botão "Ver mapa completo"), é a tela-síntese que organiza a conformidade em **três camadas**, cada item ligado ao artigo da LGPD:

[![Mapa de Conformidade](/assets/screenshots/blgpd-50-mapa-conformidade.png)](/assets/screenshots/blgpd-50-mapa-conformidade.png)
*As três seções: o que o sistema verifica, o que você atesta e o que é responsabilidade sua fora da ferramenta.*

- ✅ **Verificado pelo sistema** — o que a ferramenta confere automaticamente, com status e atalho para resolver.
- 📝 **Você atesta** — as 4 autodeclarações sob responsabilidade da OSC (contrato com operadores, treinamento, dados sensíveis, transferência internacional). Marque **Sim / Não / Não se aplica**.
- ⚪ **Sob sua responsabilidade** — deveres que acontecem **fora** do plugin (comunicar incidente à ANPD, avaliar o RIPD, responder a fiscalizações).

## Veja também

- [O passo a passo da conformidade](/passo-a-passo-conformidade/)
- [Relatórios & Backup](/modulos/relatorios/)
