# ADR-001 — Preparação do repositório e rastreabilidade no Azure DevOps

- **Situação:** aceita
- **Data:** 2026-11-01
- **Participantes:** Ricardo, Elis e Maria Eduarda

## Contexto

Antes de iniciar a Sprint 1, é necessário preparar o repositório da equipe e validar a integração entre Azure Boards e Azure Repos.

A preparação deve permitir a rastreabilidade entre tarefas, commits e pull requests, garantindo que as alterações no código possam ser associadas aos respectivos itens de trabalho.

A atividade possui duração estimada de 40 minutos e não deve fazer parte da Sprint 1, pois corresponde à configuração inicial do projeto.

## Decisão

Criar uma Task no Azure Boards chamada `Preparar o repositório da equipe`, fora da Sprint 1.

Utilizar essa Task para validar o vínculo entre work item, commit e pull request, garantindo a rastreabilidade das alterações realizadas no repositório.

## Alternativas consideradas

| Alternativa | Por que não foi escolhida |
|---|---|
| Incluir a Task na Sprint 1 | A preparação é uma atividade inicial, anterior ao desenvolvimento planejado para a Sprint. |
| Preparar o repositório sem criar uma Task | Não permitiria validar completamente a rastreabilidade entre work item, commit e pull request. |
| Registrar a atividade apenas na documentação | Não permitiria acompanhar diretamente a atividade pelo Azure Boards. |

## Consequências

- **Positivas:** Repositório preparado antes da Sprint 1, rastreabilidade das alterações e validação antecipada da integração entre Azure Boards e Azure Repos.
- **Negativas:** Tempo adicional para registrar e vincular os itens de trabalho, commits e pull requests.
- **Como verificar:** Confirmar que a Task foi criada fora da Sprint 1 e que o Azure DevOps apresenta corretamente os vínculos entre o work item, o commit e o pull request correspondente.
