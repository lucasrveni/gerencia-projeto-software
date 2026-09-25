# Ata de Reunião — 31/08/2026

| Campo | Informação |
|-------|------------|
| Projeto | UneTask |
| Tipo de reunião | Sprint Review 3 (marco M-5), Retrospectiva e Sprint Planning 4 |
| Data e horário | 31/08/2026, das 19h00 às 20h30 |
| Local | Videoconferência |
| Redigida por | Guillermo Gilioli de P. Coelho |

## Participantes

| Nome | Papel | Presença |
|------|-------|----------|
| Guillermo Gilioli de P. Coelho | Gerente / Scrum Master | Presente |
| Ryller Brito Pereira | Product Owner / Analista | Presente |
| Lucas da Rosa | Designer UI/UX | Presente |
| Kaiky Marçal Ferreira | Desenvolvedor / QA | Presente |
| Otavio Maniezzo Milan | Desenvolvedor / QA | Presente |
| Janecler Foppa | Professora responsável | Presente |

## Pauta

1. Demonstração do incremento da Sprint 3 (marco M-5).
2. Decisão sobre a solicitação de mudança SM-05.
3. Retrospectiva da Sprint 3.
4. Sprint Planning 4 — Testes, usabilidade e correção de defeitos.

## Discussões e Decisões

- **Incremento aceito.** Foram demonstrados o dashboard com gráfico de status, sequência de dias e progresso por matéria, o quadro Kanban com arrastar e soltar entre as três colunas e o Modo foco vinculado à tarefa. O marco M-5 foi formalizado.
- **Itens transportados.** Dos 31 pontos planejados, 29 foram entregues. O gesto de arrastar e soltar apresentou comportamento inconsistente em telas menores que 5,5 polegadas, e os 2 pontos referentes a esse ajuste foram transportados para a Sprint 4.
- **Alternativa de acessibilidade.** Como medida complementar, ficou decidido que o quadro também aceitará um toque simples sobre o card para avançar o status, garantindo o uso por estudantes com dificuldade motora e em telas pequenas (RNF-002 e RNF-006).
- **SM-05 rejeitada.** A inclusão de notificações push de lembrete de prazo na versão 1.0, solicitada em 26/08, foi rejeitada. A análise apontou impacto de 40 horas e de 5 dias no cronograma, sem compensação possível que não implicasse remover um requisito de prioridade ALTA. O item foi encaminhado para a versão 1.1, com registro no backlog do produto.
- **Indicadores.** IDP de 0,98 e IDC de 0,98 na semana, dentro da tolerância. O acumulado do custo real segue R$ 700,00 acima do valor agregado, diferença atribuída às horas adicionais das Sprints 1 e 3.
- **Retrospectiva.** Ponto positivo: a decisão de manter as regras de negócio fora da camada de interface permitiu testar o cálculo das métricas sem depender das telas. Ponto de melhoria: a validação em dispositivos físicos ocorreu tarde demais na sprint. Ação de melhoria: incluir teste em pelo menos dois dispositivos físicos distintos na Definição de Pronto.
- **Sprint 4 planejada.** Selecionados 20 pontos, cobrindo o plano e os casos de teste, os testes automatizados, os testes de usabilidade, o ajuste do arrastar e soltar e a correção dos defeitos identificados.

## Ações Acordadas

| ID | Ação | Responsável | Prazo | Situação |
|----|------|-------------|-------|----------|
| A-21 | Ajustar o arrastar e soltar em telas menores e implementar o avanço por toque | Otavio | 02/09/2026 | Concluída |
| A-22 | Elaborar o plano e os casos de teste por requisito | Otavio | 01/09/2026 | Concluída |
| A-23 | Implementar a suíte de testes automatizados em CI | Kaiky | 03/09/2026 | Concluída |
| A-24 | Conduzir os testes de usabilidade com cinco estudantes | Lucas | 02/09/2026 | Concluída |
| A-25 | Registrar SM-05 no backlog da versão 1.1 | Ryller | 01/09/2026 | Concluída |
| A-26 | Incluir teste em dois dispositivos físicos na Definição de Pronto | Guillermo | 01/09/2026 | Concluída |

## Próxima reunião

07/09/2026, às 19h00 — Sprint Review 4 (marco M-6) e planejamento da implantação.
