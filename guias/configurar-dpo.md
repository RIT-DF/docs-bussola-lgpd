---
title: "Configurar o Encarregado"
nav_order: 1
parent: "Guias por tarefa"
permalink: /guias/configurar-dpo/
task: configurar-dpo
role: encarregado
routes: ["#/settings"]
screenshots: [blgpd-08-settings-dpo]
last_verified: 2026-06-24
status: publicado
---

# Configurar o Encarregado

O Encarregado é o contato de privacidade da sua OSC. Cadastrá-lo é o **primeiro passo** — esses dados aparecem publicamente na Central de Privacidade.

[![Configurações de identidade do Encarregado](/assets/screenshots/blgpd-08-settings-dpo.png)](/assets/screenshots/blgpd-08-settings-dpo.png)
*Configurações → Identidade.*

## Passo a passo

1. No painel, abra **Bússola LGPD → Configurações**.
2. Na aba **Identidade**, preencha:
   - **Nome ou Setor** — quem responde pela privacidade (ex.: "Encarregado de Dados" ou "Setor de Privacidade").
   - **E-mail de Contato** — por onde o titular fala com a OSC.
   - **Telefone** (opcional).
   - **Logo da Organização** — aparece nos relatórios PDF e na Central de Privacidade.
   - **Prefixo de Versionamento** — o prefixo usado nas versões das políticas (ex.: "v").
3. Clique em **Salvar Identidade**.

> ✅ **Boas práticas**
>
> Use um e-mail **institucional e monitorado** (ex.: `privacidade@suaosc.org`), não o pessoal de um voluntário. Se a pessoa sair, o contato continua funcionando.

> 💡 Ao salvar, o item **Encarregado Configurado** do [Índice de Conformidade](/modulos/painel/) passa a contar como verificado.

## Modo de exclusão de políticas

Nesta mesma aba há o **Modo de Exclusão de Políticas**, que define o que o botão **Excluir** (na lista de Políticas) faz:

- **Soft Delete** (padrão) — **arquiva**: a política some do painel e do site, mas o registro e o histórico de versões são preservados (para auditoria). Recomendado.
- **Hard Delete** — **apaga em definitivo** a política e todo o seu histórico de versões do banco, sem volta.

> ⚠️ **Atenção**
>
> O *Hard Delete* apaga a política definitivamente — você **perde a rastreabilidade** de qual texto esteve no ar. Mantenha em *Soft Delete* salvo se tiver um motivo claro para apagar de vez. (Os consentimentos já coletados são preservados nos dois modos.)

> ✅ **Quer só tirar do ar, não apagar?** Não use a exclusão — use **[Inativar](/modulos/politicas/#inativar-e-reativar-uma-politica)** na lista de Políticas. Inativar é reversível e preserva tudo; excluir (acima) é outra coisa.
