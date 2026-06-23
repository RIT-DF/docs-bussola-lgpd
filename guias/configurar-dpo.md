---
title: "Configurar o Encarregado (DPO)"
nav_order: 1
parent: "Guias por tarefa"
permalink: /guias/configurar-dpo/
task: configurar-dpo
role: encarregado
routes: ["#/settings"]
screenshots: [blgpd-08-settings-dpo]
last_verified: 2026-06-23
status: publicado
---

# Configurar o Encarregado (DPO)

O Encarregado é o contato de privacidade da sua OSC. Cadastrá-lo é o **primeiro passo** — esses dados aparecem publicamente na Central de Privacidade.

[![Configurações de identidade do DPO](/assets/screenshots/blgpd-08-settings-dpo.png)](/assets/screenshots/blgpd-08-settings-dpo.png)
*Configurações → Identidade (DPO).*

## Passo a passo

1. No painel, abra **Bússola LGPD → Configurações**.
2. Na aba **Identidade (DPO)**, preencha:
   - **Nome ou Setor** — quem responde pela privacidade (ex.: "Encarregado de Dados" ou "Setor de Privacidade").
   - **E-mail de Contato** — por onde o titular fala com a OSC.
   - **Telefone** (opcional).
   - **Logo da Organização** — aparece nos relatórios PDF e na Central de Privacidade.
   - **Prefixo de Versionamento** — o prefixo usado nas versões das políticas (ex.: "v").
3. Clique em **Salvar Identidade**.

> ✅ **Boas práticas**
>
> Use um e-mail **institucional e monitorado** (ex.: `privacidade@suaosc.org`), não o pessoal de um voluntário. Se a pessoa sair, o contato continua funcionando.

> 💡 Ao salvar, o item **DPO Configurado** do [Índice de Conformidade](/modulos/painel/) passa a contar como verificado.

## Modo de exclusão de políticas

Nesta mesma aba há o **Modo de Exclusão de Políticas**:

- **Soft Delete** (padrão) — mantém os registros e apenas desativa. Recomendado.
- **Hard Delete** — apaga permanentemente do banco.

> ⚠️ **Atenção**
>
> O *Hard Delete* apaga a política definitivamente, sem volta. Mantenha em *Soft Delete* salvo se você tiver um motivo claro para apagar de vez.
