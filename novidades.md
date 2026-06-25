---
title: "Novidades"
nav_order: 11
permalink: /novidades/
---

# Novidades

O que mudou no Bússola LGPD, em linguagem leve. Para o histórico técnico completo, fale com a equipe de implantação.

## Versões 1.11 a 1.17 — Conformidade com o ECA Digital

Chegou o apoio ao **ECA Digital** (Lei 15.211/2025), a lei que protege crianças e adolescentes na internet — especialmente relevante para OSCs que trabalham com esse público. Veja a nova seção [ECA Digital](/eca-digital/).

- **Descubra se a lei te alcança** — uma triagem rápida no [Mapa de Conformidade](/eca-digital/enquadramento/) mostra só os deveres que se aplicam ao seu caso (e avisa quando seu site, por ter controle editorial, está dispensado da verificação de idade).
- **Consentimento dos pais** para dados de menores, com registro de prova ([saiba mais](/eca-digital/consentimento-parental/)).
- **Privacidade por padrão** e **transparência aos pais** na sua Central de Privacidade.
- **Aviso** contra publicidade/perfilamento dirigido a menores na configuração de cookies.
- **Novo módulo [RIPD](/modulos/ripd/)** — avalie os riscos de um tratamento com uma matriz simples e gere o relatório em PDF.
- **Novo módulo [Denúncias](/modulos/denuncias/)** — canal público para reportar conteúdo que viole direitos de crianças e adolescentes, com triagem no painel.

> O ECA Digital é uma lei **diferente** da LGPD: esses deveres aparecem **à parte** e **não** alteram o seu Índice de Conformidade da LGPD. O conteúdo ajuda a se situar e **não substitui orientação jurídica**.

## Versão 1.7 — Tamanho da imagem das políticas

- **Imagem em pequeno, médio, grande ou extra grande** — agora dá para ajustar o tamanho da imagem/ícone das políticas externas no card da Central. Defina um padrão em Configurações → Páginas & Integração ou ajuste caso a caso pelo atributo `tamanho` do shortcode (ex.: `[bussola_lgpd_politica id="3" tamanho="extra-grande"]`). O padrão (pequeno) mantém o visual atual. Veja [as opções de exibição](/modulos/central-privacidade/#opcoes-de-exibicao-das-politicas).

## Versão 1.6 — Excluir políticas (com cuidado)

- **Excluir política** — além de **inativar** (que só tira do site e é reversível), agora dá para **excluir** uma política de vez. O comportamento segue o **Modo de Exclusão** configurado em Configurações → Identidade (DPO): *arquivar* (mantém o registro para auditoria, mas some do painel) ou *excluir em definitivo* (apaga também o histórico de versões — **perde-se a rastreabilidade** de qual texto esteve no ar e quando). Antes de excluir, o sistema mostra um aviso claro e recomenda usar **Inativar** quando o objetivo é apenas tirar do site. Os **consentimentos já coletados nunca são apagados**, em nenhuma modalidade. Veja [Políticas › Excluir](/modulos/politicas/#excluir-uma-politica).
- **Correção visual (1.6.1)** — políticas externas (por link) deixaram de exibir, na lista, os avisos de "versões publicadas / nenhuma versão ativa" (que só fazem sentido para políticas internas) — evitando a impressão de que estariam incompletas.

## Versão 1.5 — Ative e desative políticas sem apagar nada

- **Inativar e reativar política** — depois de publicada, uma política pode ser **inativada** quando foi incorporada a outra, substituída ou deixou de valer. A política inativa **some da Central e dos shortcodes**, mas nada é apagado: conteúdo, histórico de versões e consentimentos ficam preservados, e você pode **reativar** quando quiser. Na lista, as inativas mostram um selo **"INATIVA"**. Vale para políticas internas e externas. Se a política inativada for a de Privacidade, o Índice de Conformidade avisa — reative-a para o indicador voltar. Veja [Políticas](/modulos/politicas/#inativar-e-reativar-uma-politica).

## Versão 1.4 — Políticas externas e exibição sob medida

- **Política por link (externa)** — agora dá para cadastrar uma política apontando para um documento que já existe (um PDF, uma página de wiki), em vez de reescrevê-la no plugin. Ela aparece na Central como um card com resumo, imagem/ícone e um botão "Ler a política completa". O número da versão é informado à mão (e mantê-lo atualizado é responsabilidade da sua OSC).
- **Resumo nas políticas** — políticas internas também ganharam um campo de resumo, usado quando você opta por exibir só o resumo.
- **Opções de exibição** — você decide como as políticas aparecem: texto integral, só o resumo ou só o título; e se mostra título, link e imagem. Configure um padrão global em Configurações → Páginas & Integração ou ajuste caso a caso pelos atributos do shortcode (ex.: `[bussola_lgpd_politicas modo="titulo"]`).
- **Escolher a página da Central** — montou sua própria página da Central com os shortcodes? Agora você pode indicá-la como a página oficial, e o Índice de Conformidade e o banner de cookies passam a apontar para ela.
- **Avisos mais suaves no painel** (1.4.1) — as confirmações e alertas do painel deixaram de usar os pop-ups do navegador e passaram a aparecer como notificações discretas no próprio plugin; ações sensíveis (como exclusões) pedem confirmação em uma janela padronizada.

Veja em [Políticas](/modulos/politicas/) e [Central de Privacidade](/modulos/central-privacidade/).

## Versão 1.3 — Central de Privacidade personalizável

Antes, a Central de Privacidade era uma página única gerada automaticamente. Agora você pode **montar a sua própria página**, posicionando cada elemento onde quiser (inclusive em construtores como o Elementor):

- **Shortcodes por elemento** — `[bussola_lgpd_dpo]` (contato do Encarregado), `[bussola_lgpd_politicas]` (suas políticas ativas), `[bussola_lgpd_cookies]` (preferências de cookies), além do `[bussola_lgpd_politica id="N"]` (uma política específica) e do `[bussola_lgpd_privacidade]` (a Central completa).
- **Continua simples para quem quer o pronto** — a página completa autogerada segue disponível e é o caminho recomendado.
- **Aviso de responsabilidade** — ao montar a página à mão, a tela de Configurações lembra que você precisa manter o contato do Encarregado e o canal de pedidos, para não deixar buracos de conformidade.
- **Acesso rápido ao manual** — agora há um link "📖 Manual / Guia LGPD" sempre visível no topo do painel.

Veja os shortcodes em [Central de Privacidade](/modulos/central-privacidade/).

## Versão 1.2 — Primeiros passos guiados, banner opcional e políticas mais seguras

- **Assistente de Primeiros Passos** — um roteiro guiado (card no Painel + tela própria) que detecta sozinho o que já está feito e leva direto à tela que resolve cada pendência, com convite de revisão periódica. Veja [Primeiros Passos](/primeiros-passos/).
- **Banner de cookies opcional** — você decide se exibe o banner; ao desativá-lo, os scripts de análise/marketing deixam de carregar (sem consentimento, não carrega).
- **Políticas mais seguras** — não é mais possível publicar uma política **vazia**; ao abrir uma política, o texto já aparece para revisão e dá para **reaproveitar versões anteriores**; e há um shortcode para exibir uma política em qualquer página.
- **Interface mais confortável** — o painel aproveita melhor a largura da tela (com limite em telas muito grandes), o menu do Bússola LGPD aparece no início do admin junto da família Bússola, e a navegação no celular ficou mais fluida.

## Versão 1.1 — Retenção & ciclo de vida dos dados

A LGPD pede que dado pessoal não fique guardado para sempre. Esta versão automatiza o **fim** desse ciclo:

- **Expurgo automático com janela de aviso** — ao fim do prazo que você define, o plugin **anonimiza** o registro; antes disso, avisa o Encarregado (7 dias por padrão), que pode **cancelar ou adiar**.
- **Anonimização que preserva a prova** — em vez de apagar tudo, remove-se o que identifica a pessoa e mantém-se o comprovante de que a obrigação foi cumprida.
- **Prazos onde fazem sentido** — dados do próprio plugin (atendimentos concluídos, consentimentos revogados) nas Configurações; dados do site, **por atividade** no Inventário (ROPA), sempre com **opt-in** (nada entra sem você ligar).
- **Conectores prontos** para WordPress (usuários, comentários), WooCommerce e os principais plugins de formulário (CF7, Fluent Forms, Forminator, Gravity Forms, WPForms) — e um encaixe extensível para novas origens.
- **Mapeamento de Formulários** — uma tela que liga cada formulário do site a uma atividade do inventário, atalho para quem tem muitos formulários.
- **Fila de Retenção** no menu e **alerta no Painel** dos registros que vão expirar em breve.
- **Revogação de consentimento de verdade** — ao concluir um pedido de revogação, os consentimentos daquele e-mail passam a contar prazo para expurgo.

Veja o passo a passo em [Retenção & Expurgo](/modulos/retencao/).

## Versão 1.0 (MVP)

A primeira versão do produto entrega a base da conformidade para OSCs:

- **Painel de conformidade** com Índice (verificado + autodeclarado), indicadores de atendimentos (DSAR) e visualizações das políticas.
- **Gestão de políticas** com versionamento, aceite por versão, editor com checklist da LGPD, **Assistente** que pré-preenche a partir do DPO e do inventário, e **Galeria de Modelos**.
- **Central de Privacidade pública** gerada automaticamente, com políticas ativas, identidade do DPO e formulário de pedidos.
- **Atendimentos (DSAR)** com duplo opt-in, controle de prazo (SLA), **execução assistida** (localizar, exportar e eliminar sob comando do Encarregado) e **auto-atendimento** para pedidos simples.
- **Consentimento**: banner de cookies (scripts só carregam com consentimento) e conectores para formulários populares.
- **Incidentes**: registro e comunicação rastreável aos titulares afetados.
- **Inventário (ROPA)**: registro das operações de tratamento, com finalidade e base legal.
- **Relatórios**: relatório de conformidade em PDF e **backup/exportação total** dos dados (ZIP com CSV/JSON e checksums).
- **Webhooks** para integrar eventos essenciais a ferramentas como n8n e Zapier.
- **Manual integrado** no painel, com link para este guia completo.

> 💡 Os ajustes de performance, segurança e robustez seguem sendo aprimorados a cada ciclo. Veja o que vem por aí em [Roadmap](/roadmap/).
