# Ata de Reunião — 10/08/2026

| Campo | Informação |
|-------|------------|
| Projeto | UneTask |
| Tipo de reunião | Revisão da prototipação (marco M-2) e Sprint Planning 1 |
| Data e horário | 10/08/2026, das 19h00 às 20h20 |
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

1. Demonstração do protótipo navegável (marco M-2).
2. Homologação da solicitação de mudança SM-01.
3. Apresentação do plano do projeto (EAP, cronograma, orçamento e planos de gerenciamento).
4. Sprint Planning 1 — Infraestrutura e Módulo de Autenticação.

## Discussões e Decisões

- **Protótipo aprovado.** O protótipo navegável foi demonstrado e aceito, formalizando o marco M-2. Ficou registrado que a publicação por GitHub Pages permite validação com estudantes sem instalação.
- **SM-01 homologada.** A ampliação do protótipo de 3 para 9 telas, solicitada em 05/08 por Lucas, foi confirmada na reunião. A justificativa aceita foi a de que três telas não permitiam validar o fluxo completo do estudante. Como a pesquisa com usuários (pacote 1.2.1) terminou antes do previsto, as 10 horas adicionais foram absorvidas sem impacto em prazo ou custo.
- **Plano do projeto aprovado.** EAP com 21 pacotes de trabalho, cronograma de 6 semanas, orçamento detalhado e os quatro planos de gerenciamento foram apresentados e aprovados.
- **Conta Apple.** O cadastro no Apple Developer Program foi submetido em 04/08 e continua em análise. A conta do Google Play Console já está ativa. Decidiu-se seguir com a contingência prevista em R-02: distribuição interna por TestFlight assim que a conta for liberada, sem bloquear o desenvolvimento.
- **Sprint 1 planejada.** Selecionados 23 pontos de história, cobrindo a configuração de infraestrutura (repositório, CI, projeto Flutter e Firebase) e o módulo de autenticação (RF-009 e RF-010).
- **Pareamento.** Diante do risco R-07, ficou acordado que Kaiky e Otavio trabalharão pareados nas duas primeiras tarefas da sprint.

## Ações Acordadas

| ID | Ação | Responsável | Prazo | Situação |
|----|------|-------------|-------|----------|
| A-06 | Configurar o projeto Flutter e os serviços Firebase | Kaiky / Otavio | 11/08/2026 | Concluída |
| A-07 | Implementar autenticação por e-mail e senha | Kaiky | 12/08/2026 | Concluída |
| A-08 | Implementar OAuth Google e Apple | Otavio | 14/08/2026 | Concluída com atraso (17/08) |
| A-09 | Acompanhar diariamente a aprovação da conta Apple | Ryller | Contínua | Concluída (13/08) |
| A-10 | Publicar o protótipo navegável no GitHub Pages | Lucas | 11/08/2026 | Concluída |

## Próxima reunião

17/08/2026, às 19h00 — Sprint Review 1 (marco M-3), Retrospectiva e Sprint Planning 2.
