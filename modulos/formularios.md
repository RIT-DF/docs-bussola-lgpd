---
title: "Verificador de Formulários"
nav_order: 8
parent: "Módulos"
permalink: /modulos/formularios/
role: encarregado
routes: ["#/forms"]
screenshots: [blgpd-33-mapeamento-formularios, blgpd-34-verificador-relatorio]
last_verified: 2026-06-28
status: publicado
---

# Verificador de Formulários

O item **Verificador de Formulários** do menu faz duas coisas: **analisa os campos** de cada formulário do seu site para apontar possíveis problemas de conformidade, e liga cada formulário a uma **atividade** do [Inventário (ROPA)](/modulos/inventario-ropa/).

[![Verificador de Formulários](/assets/screenshots/blgpd-33-mapeamento-formularios.png)](/assets/screenshots/blgpd-33-mapeamento-formularios.png)
*A lista mostra cada formulário do site, com um status de conformidade e os botões para verificar e mapear.*

## Por que verificar os formulários

É comum uma OSC acumular formulários no site — alguns antigos, anteriores à LGPD — que coletam dados pessoais **sem consentimento**, ficam **fora do inventário** ou tratam dados de **crianças/adolescentes** sem o cuidado devido. O verificador ajuda você a **encontrar esses casos** para tratá-los.

> ⚠️ **A ferramenta aponta, não corrige — e é consultiva**
>
> A análise é **automática e baseada em pistas** (o nome e o tipo de cada campo): ela diz que um campo *parece* dado pessoal, e cabe a **você confirmar e tratar**. Ela **não corrige** os formulários e **não substitui** orientação jurídica.

## Verificar a conformidade

[![Relatório do verificador](/assets/screenshots/blgpd-34-verificador-relatorio.png)](/assets/screenshots/blgpd-34-verificador-relatorio.png)
*O relatório lista os campos identificados como dados pessoais (com selo de "sensível") e os problemas para o Encarregado tratar.*

1. Na tela, clique em **Verificar** num formulário (ou em **🔎 Verificar todos**).
2. O **relatório** abre mostrando:
   - **Campos com dados pessoais identificados** — os campos que *parecem* dado pessoal, com um selo **SENSÍVEL** quando o campo sugere dado de categoria especial (saúde, religião etc.).
   - **Problemas identificados** — entre eles:
     - **Sem checkbox de consentimento** — o formulário coleta dados pessoais e não tem um campo de consentimento.
     - **Fora do Inventário (ROPA)** — o formulário não está mapeado a uma atividade com base legal (use o seletor da linha para mapear).
     - **Indícios de dados de menores** sem campo/consentimento de pais ou responsáveis.
     - **Indícios de dados sensíveis**, que exigem cuidado e consentimento específico.
3. O **status** de cada formulário na lista mostra ✅ sem pendências, ⚠️ com pendências, ou ⏳ não verificado.

### Marcar um achado como revisado

Avaliou um apontamento e concluiu que está tudo certo (ou é um falso alarme)? Clique em **Marcar como revisado** (com uma nota opcional). O achado fica **esmaecido** e deixa de contar como pendência. Você pode **Desfazer** quando quiser.

> 💡 **A revisão "expira" se o formulário mudar**
>
> A revisão vale para a **versão atual** dos campos do formulário. Se alguém **editar** o formulário (adicionar ou trocar campos), a revisão é **descartada** e o achado reaparece — para você conferir de novo, já que o formulário não é mais o mesmo.

## Mapear o formulário ao Inventário (ROPA)

Todo formulário que coleta dados pessoais faz parte de **alguma** atividade de tratamento. Vincular o formulário à atividade certa mantém o [Inventário (ROPA)](/modulos/inventario-ropa/) fiel à realidade e permite que a **retenção automática** saiba o que expurgar e quando (ver [Retenção & Expurgo](/modulos/retencao/)).

1. Para cada formulário, escolha no seletor a **atividade do ROPA** correspondente.
2. Para tirar o vínculo, escolha **"-- Remover Vínculo --"**.

> 💡 **Vários formulários, uma atividade**
>
> O ROPA é organizado **por finalidade**, não por formulário. Se vários formulários coletam os mesmos dados para o mesmo fim, eles pertencem à **mesma** atividade — aponte todos para um único registro, sem inflar o inventário.

> ⚠️ **Um vínculo por formulário**
>
> Cada formulário deve pertencer a **uma** atividade (senão o prazo de retenção fica ambíguo). Um formulário que mistura finalidades deveria ser separado; enquanto não for, use a atividade de prazo **mais longo**.

> ✅ **Boas práticas**
>
> Ao instalar um plugin de formulário novo ou criar um formulário, reserve alguns minutos para **verificar** e **mapear** aqui. Manter isso em dia é o que faz o inventário, a retenção e a conformidade trabalharem a seu favor.

➡️ Para configurar **prazos** e ligar a retenção, veja **[Retenção & Expurgo](/modulos/retencao/)**.
