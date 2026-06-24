---
title: "Políticas"
nav_order: 2
parent: "Módulos"
permalink: /modulos/politicas/
role: encarregado
routes: ["#/policies", "#/policies/edit/:id", "#/policy-wizard", "#/templates"]
screenshots: [blgpd-02-policies, blgpd-03-policy-editor, blgpd-11-templates]
last_verified: 2026-06-23
status: publicado
---

# Políticas

O módulo **Políticas** é onde sua OSC cria, versiona e publica os documentos que explicam ao público como trata os dados — Política de Privacidade, Termos de Uso, Política de Cookies e o que mais precisar.

[![Lista de políticas](/assets/screenshots/blgpd-02-policies.png)](/assets/screenshots/blgpd-02-policies.png)
*Cada política mostra quantas versões publicadas tem e qual está ativa.*

> 💡 **Por que isso importa**
>
> Transparência é um pilar da LGPD: o titular tem o direito de saber o que você faz com os dados dele. Uma política clara e publicada é a forma mais direta de cumprir esse dever — e a primeira coisa que um financiador ou a ANPD vão procurar.

## Ambiente genérico de políticas

O Bússola LGPD **não entrega políticas prontas**. Ele dá a estrutura para você criar **quantas quiser** — e só a **Política de Privacidade** vem com um checklist e modelo-base, por ser exigência direta da LGPD.

## Política interna ou externa (link)

Ao criar uma política, escolha a **origem**:

- **Interna** — você redige o texto no editor do plugin, com versionamento automático (o caminho tradicional).
- **Externa** — você aponta um **link** para uma política que já existe fora do plugin (um PDF, uma página de wiki, um documento numa intranet). Útil para OSCs que já têm a política publicada e não querem reescrevê-la.

Para a política **externa**, você informa: a **URL** do documento, um **resumo/descrição**, uma **imagem ou ícone** (escolha um dos ícones prontos, envie uma imagem, ou deixe sem) e o **número da versão** (preenchido **manualmente**).

> ⚠️ **Versão da política externa é você quem atualiza**
>
> Como o texto mora fora do plugin, o Bússola não controla as versões dela. **Atualize o número da versão sempre que publicar uma nova** — manter isso em dia é responsabilidade da sua organização.

Na Central, a política externa aparece como um **card** com a imagem/ícone, o título, o resumo e um botão **"Ler a política completa"** que abre o documento em uma nova aba.

> 💡 **Resumo também nas internas**
>
> As políticas **internas** também têm um campo de **resumo** (opcional). Ele é usado quando você exibe as políticas no modo "resumo" (veja as [opções de exibição](/modulos/central-privacidade/#opcoes-de-exibicao-das-politicas)). Se você deixar o resumo em branco, o plugin gera um trecho automático a partir do texto.

## Versionamento e aceite

Toda alteração relevante gera uma **nova versão**. O histórico fica registrado, e você define qual versão está **ativa** (é a que o público vê). Esse versionamento é o que permite provar, mais tarde, **qual texto estava no ar em determinada data** — essencial para accountability.

## O editor

[![Editor de política](/assets/screenshots/blgpd-03-policy-editor.png)](/assets/screenshots/blgpd-03-policy-editor.png)
*Editor com formatação rica, histórico de versões e o Checklist LGPD ao lado.*

O editor tem:

- **Formatação rica** (negrito, itálico, títulos, listas, links) com opção de **ver o código HTML**.
- **Histórico de Versões**, com a versão ativa destacada.
- **Checklist LGPD**: um guia visual dos itens que uma Política de Privacidade deve contemplar — identificação do controlador, contato do Encarregado, finalidades, bases legais (Art. 7º), direitos do titular (Art. 18), tempo de retenção e compartilhamento de dados.

> ✅ **Boas práticas**
>
> Use o checklist como roteiro enquanto escreve. Ele não preenche o texto por você, mas garante que nenhum item obrigatório fique de fora.

## O Assistente (Wizard de Política)

Em vez de começar da folha em branco, use o **🪄 Assistente**: ele pré-preenche um rascunho com os dados do **DPO** e do **Inventário (ROPA)**, monta a estrutura e abre no editor para você revisar e publicar.

> 💡 **Por que isso importa**
>
> O Assistente conecta o que você já cadastrou (DPO, inventário) ao texto da política. Isso reduz erro e retrabalho: se a finalidade e a base legal já estão no inventário, elas entram na política sem você redigitar.

## A Galeria de Modelos

[![Galeria de modelos](/assets/screenshots/blgpd-11-templates.png)](/assets/screenshots/blgpd-11-templates.png)
*Modelos-semente de políticas e cláusulas, prontos para pré-preencher e abrir no editor.*

A **📚 Galeria de Modelos** traz modelos-base (políticas e cláusulas) para acelerar a redação.

> ⚠️ **Atenção**
>
> Os modelos são **ponto de partida de caráter geral**, não texto juridicamente validado para o seu caso. Adapte ao contexto da sua OSC e, sempre que possível, valide com apoio jurídico. Veja o [Aviso legal](/disclaimer/).

## Exibir uma política em qualquer página (shortcode)

Além de a política aparecer na [Central de Privacidade](/modulos/central-privacidade/), você pode incorporar **uma política específica** em qualquer página do site (inclusive em construtores como Elementor) com o shortcode:

```
[bussola_lgpd_politica id="1"]
```

Ele exibe o conteúdo da **versão ativa** daquela política (ou o **card** com o link, se a política for externa). Na **lista de Políticas**, cada política mostra o seu **ID** (e um atalho para copiar o shortcode pronto) — é o número que você coloca em `id="..."`.

Você ainda pode controlar **como** a política aparece com atributos (`modo`, `titulo`, `link`, `imagem`) — por exemplo `[bussola_lgpd_politica id="1" modo="resumo"]`. Veja a tabela completa em [Opções de exibição das políticas](/modulos/central-privacidade/#opcoes-de-exibicao-das-politicas).

> 💡 **Quando usar**
>
> Útil quando você quer a Política de Privacidade (ou os Termos de Uso) numa página própria do site, separada da Central. Se a política não tiver uma versão ativa, o shortcode mostra um aviso discreto em vez de quebrar a página.

## Como fazer

➡️ Passo a passo em **[Publicar uma política](/guias/publicar-politica/)**.
