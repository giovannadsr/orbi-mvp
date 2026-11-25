# Quadro e backlog do GitHub

## Configuração do GitHub Project
Criem um Project vinculado ao repositório `orbi-mvp`, preferencialmente no formato Board, com estas colunas/status:
- **Backlog:** ideias ainda não priorizadas.
- **A fazer:** tarefas selecionadas para a iteração atual.
- **Em andamento:** trabalho iniciado.
- **Em revisão:** aguardando revisão/teste do colega.
- **Concluído:** critérios de aceite atendidos e alteração integrada.

Campos úteis: Status, Assignee, Priority, Iteration e Size. Não é necessário criar campos demais para uma dupla.

## Backlog inicial sugerido
Criem uma Issue por item que decidirem executar. Atribuam uma pessoa responsável e mantenham o outro integrante como revisor.

| Ordem | Issue sugerida | Responsável inicial | Prioridade |
|---|---|---|---|
| 1 | [SETUP] Subir MVP atual e documentar execução | Giovanna | Alta |
| 2 | [TEST] Validar cadastro, login e interesses | Marcos | Alta |
| 3 | [TEST] Validar catálogo, busca e filtros | Giovanna | Alta |
| 4 | [TEST] Validar leitura e persistência do progresso | Marcos | Alta |
| 5 | [FIX] Corrigir falhas encontradas nos testes | Ambos, por subtarefa | Alta |
| 6 | [UX] Melhorar mensagens, estados vazios e feedback | Giovanna | Média |
| 7 | [A11Y] Revisar teclado, contraste e responsividade | Giovanna | Média |
| 8 | [DOC] Registrar resultados dos testes e limitações | Marcos | Média |
| 9 | [DEMO] Preparar roteiro e evidências da apresentação | Ambos | Alta |

## Rótulos sugeridos
`feature`, `bug`, `documentation`, `design`, `testing`, `priority: high`, `priority: medium`, `priority: low`.

## Milestones / iterações
Para manter transparência, usem milestones correspondentes ao trabalho real:
- **Iteração 1 — Estrutura e fluxo básico**
- **Iteração 2 — Validação e correções**
- **Iteração 3 — Entrega e apresentação**

Se o tempo da disciplina não permitir três iterações completas, registrem apenas as que de fato ocorrerem. Não criem atividades retroativas fictícias.

## Definition of Done
Uma Issue só deve ir para Concluído quando:
- O critério de aceite foi verificado.
- A alteração foi testada no navegador.
- O colega revisou o código ou os resultados.
- O PR foi integrado à `main`, quando houver alteração de código.
- A documentação foi atualizada quando necessário.
