---
title: "Mapeamento de Formulários"
nav_order: 8
parent: "Módulos"
permalink: /modulos/formularios/
role: encarregado
routes: ["#/forms"]
screenshots: [blgpd-33-mapeamento-formularios]
last_verified: 2026-06-23
status: publicado
---

# Mapeamento de Formulários

O item **Formulários** do menu liga cada formulário do seu site a uma **atividade** do [Inventário (ROPA)](/modulos/inventario-ropa/). É o atalho prático para quem tem muitos formulários: em vez de montar o inventário "de cima para baixo", você parte dos formulários que já existem e diz a que finalidade cada um pertence.

[![Mapeamento de Formulários](/assets/screenshots/blgpd-33-mapeamento-formularios.png)](/assets/screenshots/blgpd-33-mapeamento-formularios.png)
*Cada formulário do site pode ser vinculado a uma atividade do ROPA — ou ficar de fora.*

## Por que vincular formulários a atividades

Todo formulário que coleta dados pessoais (inscrição, contato, doação, voluntariado…) faz parte de **alguma** atividade de tratamento. Vincular o formulário à atividade certa:

- mantém o **Inventário (ROPA)** fiel à realidade do site;
- permite que a **retenção automática** saiba quais entradas expurgar e quando (ver [Retenção & Expurgo](/modulos/retencao/));
- evita que dados fiquem "soltos", sem finalidade nem prazo definidos.

> 💡 **Vários formulários, uma atividade**
>
> O ROPA é organizado **por finalidade**, não por formulário. Se cinco formulários de eventos coletam os mesmos dados para o mesmo fim, eles pertencem à **mesma** atividade. A tela deixa você apontar todos para um único registro do inventário — sem inflar o ROPA.

## Como usar

1. No menu, abra **Formulários**. A tela lista **todos os formulários publicados** do site, detectados a partir dos plugins de formulário instalados (Contact Form 7, Fluent Forms, Forminator, Gravity Forms, WPForms).
2. Para cada formulário, escolha no seletor a **atividade do ROPA** correspondente (pelo nome da atividade).
3. Para tirar o vínculo, escolha **"-- Remover Vínculo --"**.

> ⚠️ **Um vínculo por formulário**
>
> Cada formulário deve pertencer a **uma** atividade. Se você tentar vinculá-lo a duas, a tela avisa — porque o prazo de retenção ficaria ambíguo. Um formulário que mistura finalidades diferentes deveria, idealmente, ser separado; enquanto não for, use a atividade de prazo **mais longo**.

## "Formulários sem atividade"

A tela mostra um contador de **formulários ainda sem atividade vinculada**. Eles **não entram** na política de retenção automática — é um lembrete para você não deixar dados sem finalidade definida. Não há erro em deixar um formulário sem vínculo; é apenas uma escolha consciente que a tela torna visível.

> ✅ **Boas práticas**
>
> Reserve alguns minutos após instalar um novo plugin de formulário ou criar um formulário novo para passar por esta tela. Manter o mapeamento em dia é o que faz o inventário e a retenção trabalharem a seu favor.

➡️ Para configurar **prazos** e ligar a retenção das atividades, veja **[Retenção & Expurgo](/modulos/retencao/)**.
