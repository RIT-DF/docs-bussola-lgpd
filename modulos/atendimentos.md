---
title: "Atendimentos (DSAR)"
nav_order: 4
parent: "Módulos"
permalink: /modulos/atendimentos/
role: encarregado
routes: ["#/dsar"]
screenshots: [blgpd-04-dsar]
last_verified: 2026-06-23
status: publicado
---

# Atendimentos (DSAR)

Aqui chegam os **pedidos dos titulares** sobre os próprios dados — o que a lei chama de direitos do Art. 18 e o mercado chama de *DSAR* (*Data Subject Access Request*). É um dos momentos mais importantes da LGPD: a hora de responder a quem confiou seus dados à sua OSC.

[![Lista de atendimentos](/assets/screenshots/blgpd-04-dsar.png)](/assets/screenshots/blgpd-04-dsar.png)
*Cada pedido mostra e-mail, tipo, data-limite (SLA) e status. "Ver / Executar" abre a execução assistida.*

## O ciclo de um pedido

1. **O titular abre o pedido** na Central de Privacidade, informando o e-mail e o direito desejado.
2. **Duplo opt-in** — o plugin envia um link de confirmação para o e-mail. O pedido só entra na fila depois que a pessoa clica e confirma. Isso evita pedidos falsos e prova que o e-mail é de quem pediu.
3. **O pedido aparece nesta lista**, com a **data-limite (SLA)** calculada.
4. **O Encarregado atende** — consultando, exportando ou eliminando os dados conforme o tipo.
5. **O titular é avisado** por e-mail quando o pedido é concluído ou recusado.

> 💡 **Por que isso importa**
>
> O prazo de referência é de **15 dias**. Perder o prazo é um dos erros mais comuns — e mais facilmente evitáveis. A lista separa **pendentes no prazo** de **pendentes atrasadas** para que nada passe despercebido.

## Auto-atendimento (self-service)

Para pedidos **simples e seguros**, o titular resolve sozinho, sem esperar o Encarregado:

- **Acesso e Confirmação**, **Portabilidade** e **Informação sobre Compartilhamento** são atendidos **automaticamente** assim que o titular confirma o e-mail — ele já recebe o resultado (inclusive o download dos dados em JSON, no caso da portabilidade).

> ⚠️ **Atenção — exclusão NÃO é self-service**
>
> Pedidos de **eliminação/anonimização** e **revogação** **continuam passando pelo Encarregado**. Exclusão é irreversível: o plugin exige confirmação humana e justificativa antes de apagar qualquer coisa. É uma trava de segurança proposital.

## Execução assistida

Ao clicar em **Ver / Executar**, o Encarregado conta com a execução assistida: o plugin **localiza** os dados ligados àquele e-mail nos sistemas conectados, permite **exportar** e, quando o pedido autoriza, **eliminar**.

> ⚠️ **Atenção — eliminação é definitiva**
>
> A eliminação de dados é **irreversível**. O plugin pede uma **justificativa** e registra a ação numa **assinatura auditável** (com encadeamento à prova de adulteração). Tenha certeza antes de confirmar — e lembre-se de que alguns dados podem ter de ser **retidos** por obrigação legal, mesmo diante de um pedido de exclusão.

## Auditoria

Toda ação relevante (criação, mudança de status, execução) é registrada num **log de auditoria imutável**. É isso que permite, depois, demonstrar **quem fez o quê e quando** — a essência da accountability.

## Como fazer

➡️ Passo a passo em **[Atender uma solicitação](/guias/atender-solicitacao/)** e, do lado do titular, em **[Como o titular exerce seus direitos](/guias/titular-exercer-direitos/)**.
