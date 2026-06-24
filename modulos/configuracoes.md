---
title: "Configurações"
nav_order: 11
parent: "Módulos"
permalink: /modulos/configuracoes/
role: encarregado
routes: ["#/settings"]
screenshots: [blgpd-08-settings-dpo, blgpd-08b-settings-cookies, blgpd-08c-settings-webhooks, blgpd-08d-settings-paginas, blgpd-08e-settings-saida]
last_verified: 2026-06-24
status: publicado
---

# Configurações

A tela **Configurações** reúne, em um só lugar, os ajustes gerais do Bússola LGPD — do contato do Encarregado à exibição das políticas e à exportação dos dados. Ela é organizada em **seis abas**.

> 💡 **Por que isso importa**
>
> A maioria dos itens de configuração afeta diretamente o que o público vê (Central, cookies, políticas) e como a sua conformidade é medida. Vale conhecer cada aba antes de publicar a Central.

## As seis abas

| Aba | Para que serve | Aprofunde em |
|---|---|---|
| **Identidade (DPO)** | Dados do Encarregado, logo da organização, prefixo de versão e modo de exclusão de políticas. | [Configurar o Encarregado](/guias/configurar-dpo/) |
| **Banner de Cookies** | Ativar/desativar o banner e gerenciar os scripts por categoria. | [Consentimento & Cookies](/modulos/consentimento/) |
| **Webhooks** | Enviar eventos (nova solicitação, alteração de política, incidente, consentimento) para automações externas. | (abaixo) |
| **Retenção & Expurgo** | Regras globais de descarte/anonimização e a fila de retenção. | [Retenção & Expurgo](/modulos/retencao/) |
| **Páginas & Integração** | Escolher a página da Central, definir a exibição padrão das políticas e copiar os shortcodes. | [Central de Privacidade](/modulos/central-privacidade/) |
| **Saída de Dados** | Exportar um backup completo dos dados da organização. | [Relatórios & Backup](/modulos/relatorios/) |

## Identidade (DPO)

[![Configurações — Identidade do DPO](/assets/screenshots/blgpd-08-settings-dpo.png)](/assets/screenshots/blgpd-08-settings-dpo.png)
*Dados do Encarregado, logo, prefixo de versão e modo de exclusão de políticas.*

Aqui você cadastra o **Encarregado (DPO)** — nome/setor, e-mail e telefone, que aparecem publicamente na Central. Também define a **logo** (usada nos relatórios e na Central), o **prefixo de versionamento** das políticas (ex.: "v") e o **Modo de Exclusão de Políticas** (soft delete, que mantém logs, ou hard delete, que apaga em definitivo).

➡️ Passo a passo em **[Configurar o Encarregado](/guias/configurar-dpo/)**.

> ✅ **Inativar ≠ excluir.** Para tirar uma política do ar **sem apagá-la**, use **Inativar** na lista de Políticas (reversível). O *Modo de Exclusão* acima rege o botão **Excluir** da lista: *soft* arquiva (preserva o registro) e *hard* apaga em definitivo (perde a rastreabilidade). Veja [Políticas › Excluir](/modulos/politicas/#excluir-uma-politica).

## Banner de Cookies

[![Configurações — Banner de Cookies](/assets/screenshots/blgpd-08b-settings-cookies.png)](/assets/screenshots/blgpd-08b-settings-cookies.png)

Você decide **se** exibe o banner e cadastra os scripts por categoria (necessários, análise, marketing). Com o banner **desativado**, os scripts não essenciais **não são carregados** (sem consentimento, nada carrega). Detalhes em [Consentimento & Cookies](/modulos/consentimento/).

## Webhooks

[![Configurações — Webhooks](/assets/screenshots/blgpd-08c-settings-webhooks.png)](/assets/screenshots/blgpd-08c-settings-webhooks.png)

Os **webhooks** notificam sistemas externos (n8n, Zapier, Make etc.) quando acontecem eventos importantes — nova solicitação de titular, alteração/ativação de política, incidente, consentimento. Informe a URL de destino para integrar o Bússola ao seu fluxo de automação.

## Retenção & Expurgo

A aba concentra as regras **globais** de retenção (prazos para anonimizar/excluir dados de solicitações e consentimentos) e dá acesso à **fila** de ações programadas. O detalhamento — conectores, motor e fila — está em [Retenção & Expurgo](/modulos/retencao/).

## Páginas & Integração

[![Configurações — Páginas & Integração](/assets/screenshots/blgpd-08d-settings-paginas.png)](/assets/screenshots/blgpd-08d-settings-paginas.png)
*Seletor da página da Central, exibição padrão das políticas e a lista de shortcodes.*

Esta aba tem três blocos:

- **Selecione a página da Central** — aponte qualquer página publicada como a sua Central de Privacidade (ou gere a página padrão com um clique). A página escolhida passa a valer para o [Índice de Conformidade](/modulos/painel/) e para o link do banner de cookies.
- **Exibição Padrão das Políticas** — define como as políticas aparecem por padrão (modo integral/resumo/só título; mostrar título, link e imagem). Cada shortcode pode sobrescrever esse padrão com atributos.
- **Shortcodes Disponíveis** — a lista pronta para copiar e colar em qualquer página.

➡️ Tudo sobre montar a página em **[Central de Privacidade](/modulos/central-privacidade/)**.

> ⚠️ **Página montada à mão é responsabilidade sua.** A Central completa autogerada já inclui Encarregado, políticas e canal de pedidos. Ao montar a sua, não deixe esses elementos de fora.

## Saída de Dados

[![Configurações — Saída de Dados](/assets/screenshots/blgpd-08e-settings-saida.png)](/assets/screenshots/blgpd-08e-settings-saida.png)

Gera um **backup completo** (ZIP) com os dados da organização — políticas, incidentes, consentimentos, ROPA, solicitações e auditoria — em formato aberto, para migração ou guarda. O arquivo contém **dados pessoais reais**: armazene em local seguro. Veja [Relatórios & Backup](/modulos/relatorios/).
