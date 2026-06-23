---
title: "Inventário (ROPA)"
nav_order: 7
parent: "Módulos"
permalink: /modulos/inventario-ropa/
role: encarregado
routes: ["#/ropa", "#/ropa/report"]
screenshots: [blgpd-06-ropa]
last_verified: 2026-06-23
status: publicado
---

# Inventário (ROPA)

O **Inventário de Tratamento** — também chamado de **ROPA** (*Records of Processing Activities*) — é o registro de **todas as operações** em que sua OSC trata dados pessoais. É a espinha dorsal da conformidade.

[![Inventário ROPA](/assets/screenshots/blgpd-06-ropa.png)](/assets/screenshots/blgpd-06-ropa.png)
*Cada registro descreve a atividade, os dados pessoais, a base legal e se há transferência internacional.*

## O que registrar em cada atividade

- **Atividade** — o que sua OSC faz (ex.: "Cadastro de voluntários", "Newsletter de doadores").
- **Dados Pessoais** — quais dados são coletados (nome, CPF, telefone, e-mail…).
- **Base Legal** — o fundamento que autoriza o tratamento (execução de contrato, consentimento, obrigação legal…). Veja [Conceitos](/conceitos-lgpd/#as-bases-legais-art-7º-e-11).
- **Transferência Internacional** — se os dados saem do Brasil (ex.: um serviço hospedado no exterior).

> 💡 **Por que isso importa**
>
> O inventário é o documento que **mais** trabalha a seu favor. É dele que sai a resposta a "quais dados você tem sobre mim?", a justificativa de um tratamento perante a ANPD e o conteúdo automático da Política de Privacidade. **Se sua OSC fizer só uma coisa da LGPD, que seja manter o inventário.**

## Modele por finalidade, não por formulário

Este é o segredo para o inventário **não virar um monstro**. O ROPA registra **atividades de tratamento** — definidas pela **finalidade** —, e **não** cada formulário, planilha ou tela isoladamente.

> 💡 **Por que isso importa**
>
> Uma OSC com 20 formulários no site não precisa de 20 registros no inventário. **Vários formulários que coletam os mesmos dados para a mesma finalidade são uma única atividade** — logo, **um único registro**. Isso é, ao mesmo tempo, o jeito **correto** de fazer o ROPA e o que torna o trabalho viável.

> 📖 **Exemplo (grupo escoteiro)**
>
> | Atividade no ROPA (1 registro) | Cobre quais formulários | Base legal · retenção |
> |---|---|---|
> | Inscrição em eventos | todos os forms de acampamento/atividade | consentimento ou contrato · prazo curto |
> | Solicitação de reembolso | todos os forms de reembolso | obrigação legal/contrato · ~5 anos |
> | Protocolos administrativos | todos os forms de protocolo | conforme o caso |
> | Pesquisas de satisfação | todas as pesquisas | legítimo interesse · curtíssimo |
>
> De ~20 formulários para **~4-6 atividades**. Um evento novo? Você só **acrescenta o formulário à atividade que já existe** — sem criar registro novo.

> ⚠️ **A única regra de fidelidade**
>
> Só agrupe formulários que de fato compartilham **dados + finalidade + base legal**. Se um formulário coletar **dado a mais** — por exemplo, informação de **saúde** (dado sensível) num evento —, ele vira uma **atividade própria**, com base e retenção próprias.

## O inventário alimenta as políticas

Quando você usa o **Assistente** em [Políticas](/modulos/politicas/), ele puxa as atividades do inventário para montar a Política de Privacidade. Inventário bem feito = política mais fácil e mais fiel à realidade.

## Relatório do inventário

O botão **Gerar Relatório** exporta o inventário em PDF — útil para anexar a prestações de contas ou apresentar a um financiador.

> ✅ **Boas práticas**
>
> Construa o inventário **aos poucos**, uma atividade por vez, e **revise** quando algo mudar: nova campanha, novo sistema, novo tipo de dado. Inventário desatualizado dá falsa sensação de segurança.

> ⚠️ **Atenção a dados sensíveis**
>
> Ao registrar, marque mentalmente as atividades que envolvem **dados sensíveis** (saúde, religião, etnia, opinião política). Elas exigem bases legais específicas e cuidado redobrado — é onde o risco aos titulares é maior.
