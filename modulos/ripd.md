---
title: "RIPD (Relatório de Impacto)"
nav_order: 13
parent: "Módulos"
permalink: /modulos/ripd/
role: encarregado
routes: ["#/ripd", "#/ripd/edit/:id", "#/ripd/view/:id"]
screenshots: [ripd-01, ripd-02, ripd-03]
last_verified: 2026-06-25
status: rascunho
---

# Módulo RIPD — Relatório de Impacto à Proteção de Dados

O **RIPD** documenta os riscos de um tratamento de dados e as medidas para mitigá-los. É um recurso **geral da LGPD** (art. 38) e também atende ao ECA Digital (art. 16) quando há dados de menores. Sobre **quando** fazer um RIPD, veja [Relatório de Impacto: quando fazer](/modelos/ripd/).

## Como criar

1. No menu, abra **RIPD** e clique em **+ Novo RIPD**.
   <!-- screenshot: ripd-01 — editor de RIPD com seleção de atividades do ROPA -->
2. **Escopo:** selecione **uma ou mais atividades** do seu Inventário (ROPA). Os dados dessas atividades aparecem para consulta e são **congelados** quando você finalizar.
3. Preencha **necessidade e proporcionalidade**, a **matriz de risco** e o **parecer/decisão**.
4. Na **matriz de risco**, para cada risco escolha **probabilidade** e **severidade**; o **nível** (baixo/médio/alto) é calculado automaticamente. Registre a **mitigação** e o **risco residual**.
   <!-- screenshot: ripd-02 — matriz de risco -->
5. **Salvar Rascunho** guarda sem congelar. **Finalizar Versão** congela uma versão (com a data e o retrato do ROPA daquele momento).
6. Depois de finalizar, você pode **Imprimir / Exportar PDF** e consultar o **histórico de versões**. Editar um RIPD finalizado cria um **novo rascunho**, preservando a versão anterior.
   <!-- screenshot: ripd-03 — RIPD finalizado / impressão -->

> 💡 **Por que isso importa**
>
> O RIPD é a melhor evidência de que a OSC **pensou os riscos antes**. As versões congeladas servem de prova de diligência ao longo do tempo.

> ⚠️ O Bússola estrutura o RIPD; o conteúdo e a decisão são da OSC. Não é parecer jurídico. **[CURADORIA JURÍDICA — RIT]**
