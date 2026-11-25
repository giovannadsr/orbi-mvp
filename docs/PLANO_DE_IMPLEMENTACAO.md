# Plano de implementação — Orbi

## Objetivo
Consolidar o MVP acadêmico, validar o fluxo principal com usuários e registrar evidências reais de trabalho ágil no GitHub.

## Situação inicial
Já existe uma versão front-end com cadastro/login demonstrativos, interesses, catálogo, leitura de conteúdo e acompanhamento de progresso. O foco agora é validar, corrigir e demonstrar esse fluxo — não recomeçar o projeto.

## Sequência recomendada
### Etapa 1 — Preparar o repositório
- Criar o repositório público `orbi-mvp`.
- Subir o código atual para a branch `main`.
- Criar um GitHub Project com as colunas indicadas em `QUADRO_E_BACKLOG.md`.
- Criar Issues para as tarefas que realmente serão executadas.
- Adicionar Giovanna e Marcos como colaboradores.

### Etapa 2 — Estabilizar o fluxo principal
- Testar cadastro e login demonstrativos.
- Testar seleção e persistência dos interesses após recarregar.
- Testar busca, filtros e abertura de conteúdo.
- Testar atualização do progresso e retomada.
- Corrigir erros encontrados e registrar evidências nas Issues.

### Etapa 3 — Melhorar a experiência
- Revisar mensagens de validação e estados vazios.
- Verificar navegação por teclado, contraste e legibilidade.
- Conferir layout em celular e desktop.
- Garantir que os botões tenham comportamento coerente e feedback claro.

### Etapa 4 — Validar e apresentar
- Pedir a 2–3 pessoas que executem tarefas sem orientação, se houver tempo.
- Registrar dificuldades, observações e mudanças feitas.
- Preparar roteiro de demonstração do problema, proposta de valor, fluxo, MVP, limitações e próximos passos.
- Capturar evidências reais: Project, Issues, commits, PRs, revisão e versão executando.

## Cronograma de trabalho sugerido
Ajustem as datas ao calendário real da disciplina. Para a entrega final prevista para 26/11/2026, priorizem nesta ordem:
1. 24/11: repositório, quadro, upload da versão existente e teste rápido de ponta a ponta.
2. 25/11: correções prioritárias, revisão cruzada e validação com usuários.
3. 26/11: conferência final e apresentação; evitem adicionar funcionalidades grandes neste dia.

## Papéis iniciais
| Integrante | Foco inicial | Entregáveis |
|---|---|---|
| Giovanna | Interface e experiência | Revisão visual, responsividade, acessibilidade e fluxo de telas |
| Marcos | Lógica e qualidade | Testes de persistência, regras de progresso, correções e integração |
| Ambos | Produto e Scrum | Refinamento, revisão de PR, validação e apresentação |

## Regra para priorizar
Uma tarefa é prioridade alta se impedir o usuário de concluir o fluxo principal: entrar, escolher interesses, encontrar um conteúdo, abrir a lição e registrar progresso. Melhorias cosméticas e funcionalidades novas ficam depois.
