---
title: "Publicar a Central de Privacidade"
nav_order: 3
parent: "Guias por tarefa"
permalink: /guias/publicar-central-privacidade/
task: publicar-central-privacidade
role: encarregado
routes: ["#/settings"]
screenshots: [blgpd-08d-settings-paginas]
last_verified: 2026-06-23
status: publicado
---

# Publicar a Central de Privacidade

A Central de Privacidade é a página pública onde o titular lê suas políticas, ajusta cookies e abre pedidos. Publicá-la é rápido.

[![Páginas & Integração](/assets/screenshots/blgpd-08d-settings-paginas.png)](/assets/screenshots/blgpd-08d-settings-paginas.png)
*Configurações → Páginas & Integração.*

## Forma rápida (recomendada)

1. No painel, abra **Bússola LGPD → Configurações → Páginas & Integração**.
2. Clique em **Gerar Página Automaticamente**.
3. O plugin cria (ou recupera) a página **Central de Privacidade** no WordPress, já publicada.
4. Pronto: ela fica acessível em um endereço como `seusite.org/central-de-privacidade/`.

> 💡 Você pode editar a página normalmente pelo menu **Páginas** do WordPress (título, posição no menu etc.) — o conteúdo dinâmico continua vindo do plugin.

## Usando shortcodes (avançado)

Para inserir a Central (ou só o formulário) em outra página, inclusive em construtores como Elementor, use os shortcodes:

- `[bussola_lgpd_privacidade]` — a Central completa (políticas + DPO + formulário + cookies).
- `[bussola_lgpd_solicitacao]` — apenas o formulário de pedidos (ideal numa página de Contato).
- `[bussola_lgpd_politica id="1"]` — uma política específica, pelo seu ID (mostrado na lista de [Políticas](/modulos/politicas/)).

## Depois de publicar

1. Adicione o link da Central ao **menu** e/ou ao **rodapé** do site, para o titular achar com facilidade.
2. Confira que sua **Política de Privacidade** está **ativa** (senão a Central aparece sem política).
3. Ative o **banner de cookies** se o site usa análise/marketing (veja [Consentimento & Cookies](/modulos/consentimento/)).

> ✅ **Boas práticas**
>
> Um link de "Privacidade" no rodapé de todas as páginas é o padrão que o público espera. Facilita o exercício de direitos e demonstra transparência.
