---
title: "Central de Privacidade"
nav_order: 3
parent: "Módulos"
permalink: /modulos/central-privacidade/
role: titular
routes: ["/central-de-privacidade/"]
screenshots: [blgpd-22-dsar-form, blgpd-08d-settings-paginas]
last_verified: 2026-06-23
status: publicado
---

# Central de Privacidade

A **Central de Privacidade** é a página **pública** do seu site onde o titular faz tudo o que a LGPD lhe garante: ler as políticas, conhecer o Encarregado, ajustar cookies e abrir pedidos sobre seus dados.

[![Central de Privacidade pública](/assets/screenshots/blgpd-22-dsar-form.png)](/assets/screenshots/blgpd-22-dsar-form.png)
*A página reúne o formulário de direitos, a identidade do DPO e a Política de Privacidade ativa.*

## O que o titular vê

- **Exercício de Direitos** — um formulário para abrir pedidos (acesso, correção, exclusão, portabilidade, revogação, informação sobre compartilhamento, outro).
- **Identidade de Privacidade (DPO)** — nome/setor, e-mail e telefone do Encarregado, para contato direto.
- **Política de Privacidade** — a **versão ativa**, exibida na íntegra. Só políticas marcadas como ativas aparecem.
- **Banner de cookies** — na primeira visita (veja [Consentimento & Cookies](/modulos/consentimento/)).

## Como publicar

[![Páginas & Integração](/assets/screenshots/blgpd-08d-settings-paginas.png)](/assets/screenshots/blgpd-08d-settings-paginas.png)
*Em Configurações → Páginas & Integração, gere a página automaticamente ou use os shortcodes.*

Há duas formas:

1. **Gerar Página Automaticamente** — em **Configurações → Páginas & Integração**, um clique cria a página completa no WordPress.
2. **Shortcodes** — para inserir em qualquer página (inclusive construtores como Elementor):
   - `[bussola_lgpd_privacidade]` — a Central **completa** (recomendado).
   - `[bussola_lgpd_solicitacao]` — só o formulário de pedidos (útil numa página de Contato).
   - `[bussola_lgpd_politica id="1"]` — uma política específica (ver [Políticas](/modulos/politicas/)).
   - `[bussola_lgpd_dpo]` — o contato/identidade do Encarregado.
   - `[bussola_lgpd_politicas]` — todas as suas políticas ativas.
   - `[bussola_lgpd_cookies]` — as preferências de cookies (aparece só se o banner estiver ativo).

> ⚠️ **Página montada à mão é responsabilidade sua**
>
> A Central **completa** autogerada já inclui tudo que a LGPD exige (Encarregado, políticas e canal de pedidos). Se você montar uma página personalizada com os shortcodes individuais, **garanta que o contato do Encarregado e o formulário de solicitação não fiquem de fora** — senão a página fica incompleta perante a lei.

➡️ Passo a passo em **[Publicar a Central de Privacidade](/guias/publicar-central-privacidade/)**.

> 💡 **Por que isso importa**
>
> A Central concentra, num lugar só, tudo o que a LGPD exige que esteja acessível ao titular. Ter esse endereço público e fácil de achar é metade do caminho da transparência — e evita que pedidos cheguem por canais informais (WhatsApp, recado) que você não consegue rastrear.

## Como o titular usa

➡️ Veja **[Como o titular exerce seus direitos](/guias/titular-exercer-direitos/)**.
