---
title: "Equipe / Acessos"
nav_order: 13
parent: "Módulos"
permalink: /modulos/equipe-acessos/
role: admin
routes: ["#/access"]
screenshots: [blgpd-60-equipe-acessos, blgpd-61-equipe-toast, blgpd-62-auditor-menu, blgpd-63-auditor-ropa, blgpd-64-auditor-settings, blgpd-65-atendente-menu, blgpd-66-atendente-dsar, blgpd-67-atendente-incidentes, blgpd-68-admin-menu-completo, blgpd-71-acessos-distincao]
last_verified: 2026-06-30
status: publicado
---

# Equipe / Acessos

A tela **Equipe / Acessos** permite que o administrador do WordPress defina, para cada usuário do painel, qual papel ele exerce no Bússola LGPD — e, com isso, a quais módulos e ações esse usuário tem acesso.

> 💡 **Por que isso importa**
>
> A LGPD pede que cada pessoa tenha acesso apenas ao que precisa para o seu trabalho (princípio da necessidade, art. 6º). Na prática: quem atende os pedidos dos titulares não precisa mexer nas configurações; quem só audita não precisa excluir registros. Separar essas responsabilidades reduz erros e facilita a prestação de contas.

> ⚠️ **Quem pode usar esta tela**
>
> Apenas o **administrador do WordPress** vê o item "Equipe / Acessos" no menu. Os demais papéis não acessam esta tela.

---

## Como funciona

Antes, era tudo-ou-nada: só quem era administrador do WordPress entrava no Bússola LGPD. Agora, o administrador pode **dar acesso ao plugin a outras pessoas da equipe sem torná-las administradoras do site** — basta escolher um papel para cada uma.

São **três papéis** atribuíveis (mais o administrador do WordPress, que tem acesso total):

| Papel | Para quem serve | Resumo do acesso |
|---|---|---|
| **Administrador do WordPress** | Quem instala e mantém o site | Acesso irrestrito, incluindo Equipe / Acessos, Configurações e a Migração/Desinstalação |
| **Encarregado** | A pessoa responsável pela proteção de dados na OSC | Acesso completo à conformidade (Políticas, ROPA, RIPD, Atendimentos, Incidentes, Consentimentos, Configurações…); **não** faz migração/importação nem desinstalação |
| **Atendente** | Quem cuida do dia a dia com os titulares | Atendimentos (DSAR), Consentimentos, Denúncias e Incidentes — sem ações irreversíveis (exclusão de dados, notificação de incidente) |
| **Auditor** | Quem precisa conferir sem alterar nada | **Somente leitura** em todos os módulos |

> ✅ **Boas práticas**
>
> Em OSCs pequenas, onde uma pessoa acumula funções, o papel **Encarregado** cobre tudo que o trabalho de privacidade exige, sem precisar dar a ela acesso de administrador do site. Reserve o administrador do WordPress para quem realmente faz manutenção técnica.

> ⚠️ **"Encarregado" aqui é o papel de acesso, não a designação formal**
>
> O papel **Encarregado** desta tela concede **permissões** no painel. Ele **não** é a designação formal do Encarregado da organização (art. 41) — essa, o contato publicado aos titulares, fica em [Configurações → Encarregado](/modulos/configuracoes/#encarregado). Costuma ser a mesma pessoa, mas são cadastros diferentes. A própria tela traz esse aviso:

[![Aviso da distinção em Equipe / Acessos](/assets/screenshots/blgpd-71-acessos-distincao.png)](/assets/screenshots/blgpd-71-acessos-distincao.png)
*Equipe / Acessos: nota que distingue o papel de acesso da designação formal do Encarregado.*

---

## Como atribuir um papel a um usuário

[![Tela Equipe / Acessos](/assets/screenshots/blgpd-60-equipe-acessos.png)](/assets/screenshots/blgpd-60-equipe-acessos.png)
*Tela Equipe / Acessos: lista dos usuários do WordPress com o papel atual de cada um.*

1. No menu lateral, abra **Equipe / Acessos** (visível só para administradores).
2. A tela mostra os usuários do WordPress. Use o campo de **busca** para encontrar alguém pelo nome ou e-mail (útil em sites com muitos usuários) — ou marque **"Somente com acesso"** para ver só quem já tem papel.
3. No seletor ao lado do usuário, escolha o papel: **Sem acesso**, **Encarregado**, **Atendente** ou **Auditor**.
4. A alteração é salva na hora e uma confirmação aparece no canto da tela.

[![Confirmação de papel atualizado](/assets/screenshots/blgpd-61-equipe-toast.png)](/assets/screenshots/blgpd-61-equipe-toast.png)
*O aviso confirma que o papel foi atualizado.*

> O administrador do WordPress aparece na lista como **"Acesso total (administrador)"**, sem seletor — ele sempre tem acesso completo e não recebe papel.

---

## O que cada papel vê

### Administrador do WordPress

[![Menu completo do administrador](/assets/screenshots/blgpd-68-admin-menu-completo.png)](/assets/screenshots/blgpd-68-admin-menu-completo.png)
*Menu com todos os módulos, incluindo Equipe / Acessos.*

Vê e usa todos os módulos do Bússola LGPD.

### Atendente

[![Menu do Atendente](/assets/screenshots/blgpd-65-atendente-menu.png)](/assets/screenshots/blgpd-65-atendente-menu.png)
*O Atendente vê um menu reduzido, voltado ao atendimento.*

O Atendente é o papel do dia a dia de receber e responder os titulares. No menu, vê **Painel, Consentimentos, Atendimentos, Denúncias e Incidentes**. Não vê ROPA, Políticas, RIPD, Retenção, Mapa, Ações do Encarregado nem Configurações.

Duas ações irreversíveis ficam reservadas ao Encarregado:

[![Atendimentos sem exclusão](/assets/screenshots/blgpd-66-atendente-dsar.png)](/assets/screenshots/blgpd-66-atendente-dsar.png)
*O Atendente responde os pedidos, mas o botão de exclusão/anonimização de dados não aparece.*

[![Incidentes sem notificação](/assets/screenshots/blgpd-67-atendente-incidentes.png)](/assets/screenshots/blgpd-67-atendente-incidentes.png)
*O Atendente registra incidentes, mas "Notificar Titulares" é exclusivo do Encarregado.*

### Auditor

[![Menu do Auditor](/assets/screenshots/blgpd-62-auditor-menu.png)](/assets/screenshots/blgpd-62-auditor-menu.png)
*O Auditor vê os módulos, mas em modo somente leitura.*

O Auditor tem **acesso de leitura a todos os módulos** (exceto Equipe / Acessos). É o papel indicado para um financiador, conselheiro ou revisor externo que precisa conferir o trabalho da OSC sem risco de alterar nada.

[![Inventário somente leitura](/assets/screenshots/blgpd-63-auditor-ropa.png)](/assets/screenshots/blgpd-63-auditor-ropa.png)
*O Inventário (ROPA) aparece completo, mas sem botões de criar, editar ou excluir.*

[![Configurações somente leitura](/assets/screenshots/blgpd-64-auditor-settings.png)](/assets/screenshots/blgpd-64-auditor-settings.png)
*Em Configurações, o Auditor vê um aviso de somente leitura e os botões de salvar ficam desabilitados.*

---

## Tabela resumida de permissões

| O que pode fazer | Admin WP | Encarregado | Atendente | Auditor |
|---|:---:|:---:|:---:|:---:|
| Ver o Painel | Sim | Sim | Sim | Sim |
| Atender pedidos (DSAR) | Sim | Sim | Sim | Não |
| Excluir/anonimizar dados (DSAR) | Sim | Sim | Não | Não |
| Registrar incidentes | Sim | Sim | Sim | Não |
| Notificar titulares (incidente) | Sim | Sim | Não | Não |
| Gerenciar Consentimentos e Denúncias | Sim | Sim | Sim | Não |
| Gerenciar Políticas / ROPA / RIPD | Sim | Sim | Não | Não |
| Configurações | Sim | Sim | Não | Não |
| Visualizar tudo (somente leitura) | Sim | Sim | — | Sim |
| Migração / Importação / Desinstalação | Sim | Não | Não | Não |
| Gerenciar Equipe / Acessos | Sim | Não | Não | Não |

> 💡 **O Bússola LGPD ajuda, mas a responsabilidade é da OSC**
>
> Definir bem os papéis é uma boa prática de segurança e conformidade, mas não garante, por si só, a conformidade com a LGPD. Veja o [Aviso legal](/disclaimer/).
