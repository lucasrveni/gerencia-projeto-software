# Encerramento

# Estrutura do Documento

- [Fase de Encerramento](#encerramento)
- [Encerramento do Projeto](#encerramento-do-projeto)
  - [Entregas Realizadas](#entregas-realizadas)
  - [Desempenho Final](#desempenho-final)
  - [Verificação dos Critérios de Aceitação](#verificação-dos-critérios-de-aceitação)
  - [Pendências e Recomendações](#pendências-e-recomendações)
  - [Aceite Formal e Liberação de Recursos](#aceite-formal-e-liberação-de-recursos)
- [Lições Aprendidas](#lições-aprendidas)
- [Auto-avaliação](#auto-avaliação)
- [Sugestões e Críticas](#sugestões-e-críticas)

# Encerramento do Projeto

O projeto **UneTask** foi formalmente encerrado em **10/09/2026**, na reunião de encerramento registrada na [ata de 10/09/2026](/docs/04-monitoramento/artefatos/ata-reuniao_2026-09-10.md). O objetivo estabelecido no Termo de Abertura — desenvolver uma aplicação mobile multiplataforma que integrasse o gerenciamento prático de tarefas acadêmicas à visualização ágil do progresso — foi alcançado dentro do prazo e do orçamento aprovados.

Ao longo de seis semanas, a equipe de cinco integrantes executou 800 horas de trabalho distribuídas em 21 pacotes de trabalho, entregou quatro sprints semanais, processou cinco solicitações de mudança e publicou o produto na Google Play Store. O escopo final do produto contempla todos os requisitos funcionais de prioridade ALTA previstos, além de duas funcionalidades incorporadas por mudança aprovada durante a execução.

## Entregas Realizadas

| Entrega | Descrição | Situação | Evidência |
|---------|-----------|----------|-----------|
| E-01 | Documentação de Iniciação | Entregue e aprovada | [Fase de Iniciação](/docs/01-iniciacao) |
| E-02 | Plano de Gerenciamento do Projeto | Entregue e aprovado | [Fase de Planejamento](/docs/02-planejamento) |
| E-03 | Protótipo Navegável | Entregue com escopo ampliado de 3 para 9 telas (SM-01) | [Protótipo publicado](https://lucasrveni.github.io/gerencia-projeto-software/) |
| E-04 | Módulo de Autenticação | Entregue (RF-009 e RF-010) | Sprint Review 1 — marco M-3 |
| E-05 | Módulo de Tarefas e Matérias | Entregue (RF-001 a RF-005, RF-011 e RF-012) | Sprint Review 2 — marco M-4 |
| E-06 | Dashboard e Quadro Kanban | Entregue (RF-006 a RF-008 e RF-013) | Sprint Review 3 — marco M-5 |
| E-07 | Produto Verificado | Entregue: cobertura de 76%, usabilidade de 93% e nenhum defeito crítico ou alto em aberto | Sprint Review 4 — marco M-6 |
| E-08 | Produto Publicado | Entregue parcialmente: publicado na Google Play; submetido e em revisão na App Store | Marco M-7 |

## Desempenho Final

| Dimensão | Planejado | Realizado | Variação | Situação |
|----------|-----------|-----------|----------|----------|
| Prazo | 03/08/2026 a 10/09/2026 | 03/08/2026 a 10/09/2026 | 0 dia | Cumprido |
| Custo | R$ 53.050,00 | R$ 52.900,00 | −R$ 150,00 (−0,3%) | Abaixo do orçamento |
| Esforço | 800 h | 800 h | 0 h | Cumprido |
| Escopo | 12 requisitos funcionais | 14 requisitos funcionais (RF-013 e RF-014 incorporados) | +2 requisitos | Ampliado sem impacto |
| Índice de desempenho de prazos (IDP) | 1,00 | 1,00 | — | Cumprido |
| Índice de desempenho de custos (IDC) | 1,00 | 1,00 | — | Cumprido |
| Defeitos críticos e altos em aberto | 0 | 0 | — | Cumprido |
| Marcos entregues no prazo | 7 | 7 | — | Cumprido |

O detalhamento semanal dos indicadores encontra-se na [Fase de Monitoramento](/docs/04-monitoramento#indicadores-de-prazo-e-custo).

## Verificação dos Critérios de Aceitação

| ID | Critério | Resultado verificado | Situação |
|----|----------|----------------------|----------|
| CA-01 | 100% dos requisitos de prioridade ALTA implementados | 100% implementados e demonstrados em Sprint Review | Atendido |
| CA-02 | Nenhum defeito crítico ou alto em aberto | 2 críticos e 5 altos registrados, todos corrigidos | Atendido |
| CA-03 | Tempo de resposta menor ou igual a 3 segundos | Mediana de 1,4 segundo nas operações de tarefa | Atendido |
| CA-04 | Taxa de sucesso maior ou igual a 90% nos testes de usabilidade | 93% com cinco estudantes | Atendido |
| CA-05 | Conformidade com a LGPD | Política de privacidade publicada, exportação e exclusão de conta implementadas | Atendido |
| CA-06 | Aplicação publicada nas duas lojas | Publicada na Google Play; submetida e em revisão na App Store | Atendido parcialmente, com aceite condicional |
| CA-07 | Aceite formal da professora responsável | Declarado na reunião de encerramento de 10/09/2026 | Atendido |

## Pendências e Recomendações

| ID | Pendência | Origem | Responsável após o encerramento | Encaminhamento |
|----|-----------|--------|----------------------------------|----------------|
| P-01 | Revisão do aplicativo na Apple App Store | Prazo de revisão da Apple, externo ao projeto | Otavio Maniezzo | Acompanhar até a liberação e comunicar as partes interessadas |
| P-02 | Defeito de severidade baixa no rótulo de prazo com fonte ampliada acima de 150% | Testes da Sprint 4 | Kaiky Marçal | Backlog da versão 1.1 |
| P-03 | Notificações push de lembrete de prazo (SM-05) | Solicitação de mudança rejeitada | Ryller Brito | Backlog da versão 1.1 |

**Recomendações para projetos futuros semelhantes:**

- Tratar a obtenção de contas de desenvolvedor e certificados das plataformas como atividade do caminho crítico, iniciada no primeiro dia, e não como tarefa administrativa paralela.
- Manter a regra de compensação no controle de mudanças desde o início: ela foi o mecanismo que permitiu incorporar duas funcionalidades novas sem comprometer prazo nem orçamento.
- Reservar explicitamente parte da capacidade da sprint (a equipe usou 10%) em projetos com sprints curtas e sem folga entre entregas.
- Programar a validação em dispositivos físicos desde a primeira sprint, e não apenas na fase de testes.

## Aceite Formal e Liberação de Recursos

Em 10/09/2026, a professora responsável **Janecler Foppa**, na qualidade de principal parte interessada do projeto, declarou o aceite das entregas relacionadas neste documento e a aprovação da documentação das cinco fases publicada no repositório, com a ressalva registrada no critério CA-06.

Com o aceite, os cinco integrantes da equipe foram formalmente liberados de suas alocações no projeto. Os acessos ao repositório e ao projeto Firebase foram mantidos para a manutenção da versão 1.1; os demais acessos foram revisados e os artefatos do projeto arquivados no repositório, que permanece como registro histórico da iniciativa.

| Recurso | Destinação após o encerramento |
|---------|-------------------------------|
| Equipe do projeto | Liberada em 10/09/2026 |
| Repositório GitHub e documentação | Mantido como ativo organizacional e base da versão 1.1 |
| Projeto Firebase | Mantido em operação para os usuários da versão publicada |
| Contas nas lojas | Mantidas sob responsabilidade da equipe, com renovação anual da conta Apple |
| Arquivo de design no Figma | Mantido como referência do design system |

# Lições Aprendidas

As lições abaixo foram consolidadas a partir das quatro retrospectivas de sprint e da reunião de encerramento.

| # | Categoria | Situação observada | Lição aprendida | Recomendação |
|---|-----------|--------------------|-----------------|--------------|
| 1 | Estimativas | A Sprint 1 subestimou o tempo de configuração de certificados e contas das plataformas, resultando em 2 pontos transportados | Tarefas de configuração de ambiente têm custo real e precisam ser estimadas como itens próprios | Registrar configuração de ambiente, contas e certificados como itens do Sprint Backlog |
| 2 | Aquisições | A conta Apple Developer levou 9 dias para ser aprovada, prazo que quase afetou o marco final | Dependências externas com prazo não controlável devem ser iniciadas no primeiro dia do projeto | Classificar aquisições externas como atividades do caminho crítico |
| 3 | Controle de mudanças | A regra de compensação permitiu incorporar RF-013 e RF-014 sem impacto em prazo ou custo | Um critério objetivo de decisão evita tanto o engessamento quanto o descontrole do escopo | Adotar a regra de compensação desde o planejamento, e não após a primeira solicitação |
| 4 | Arquitetura | Manter as regras de negócio fora da camada de interface permitiu testá-las sem dispositivo ou rede | Decisões de arquitetura tomadas cedo reduzem o custo dos testes ao longo de todo o projeto | Isolar o domínio das dependências de infraestrutura, mesmo em projetos pequenos |
| 5 | Qualidade | Os dois defeitos críticos só apareceram na Sprint 4, ao testar em dispositivos físicos variados | Emuladores não substituem dispositivos reais na verificação de aplicações móveis | Incluir teste em dispositivos físicos na Definição de Pronto desde a primeira sprint |
| 6 | Comunicação | Dois itens ficaram bloqueados por falta de resposta sobre uma regra de negócio | Sprints de uma semana não toleram decisões pendentes por mais de um dia | Estabelecer prazo máximo de resposta da Product Owner para dúvidas de regra de negócio |
| 7 | Design | Ampliar o protótipo de 3 para 9 telas antecipou a descoberta de problemas de navegação | O protótipo tem retorno maior quando cobre o fluxo completo, e não apenas telas isoladas | Prototipar o fluxo de ponta a ponta antes de iniciar o desenvolvimento |
| 8 | Planejamento | A reserva de 10% da capacidade da sprint absorveu os 4 pontos transportados sem deslocar marcos | Em cronogramas sem folga entre entregas, a contingência precisa estar dentro da sprint | Reservar parte da capacidade, e não do calendário, quando o prazo é rígido |
| 9 | Equipe | O pareamento na Sprint 1 acelerou a superação da curva de aprendizado da plataforma | Investir em pareamento no início reduz o risco de concentração de conhecimento | Parear nas primeiras tarefas de qualquer tecnologia nova para a equipe |
| 10 | Gestão de riscos | Dos 12 riscos mapeados, 5 se materializaram, todos com contramedida já definida | O valor do plano de riscos está na resposta pronta, não na previsão exata | Revisar a lista de riscos em toda Sprint Review, com responsável nominal para os riscos altos |

# Auto-avaliação

> **Esta seção normalmente não existe em projetos. Foi adicionada neste documento apenas no contexto da disciplina.**

**Guillermo Gilioli de P. Coelho — Gerente / Scrum Master.** Assumir simultaneamente a gerência e a função de Scrum Master exigiu separar com clareza dois papéis que puxam em direções diferentes: cobrar prazo e proteger a equipe. O maior aprendizado foi perceber que o controle de um projeto não está nos documentos produzidos, mas na frequência com que se compara o planejado com o real — a medição semanal por valor agregado mostrou os dois desvios antes que virassem atraso. Poderia ter sido mais rigoroso na condução das Dailies, que em algumas semanas ficaram superficiais.

**Ryller Brito Pereira — Product Owner / Analista.** O papel me obrigou a decidir o que não fazer, que se mostrou mais difícil do que definir o que fazer. A decisão de restringir a exportação ao CSV para viabilizar o Modo foco foi a mais importante do projeto, e só foi possível porque o valor de cada item havia sido discutido com os estudantes na pesquisa inicial. Como ponto de melhoria, demorei a responder dúvidas de regra de negócio na Sprint 2, o que bloqueou dois itens e gerou uma ação de melhoria na retrospectiva.

**Lucas da Rosa — Designer UI/UX.** Trabalhar com o protótipo como artefato de validação, e não como entregável estético, mudou minha forma de projetar: as nove telas existiram para responder perguntas sobre o fluxo, e cada ajuste veio de uma dificuldade observada em sessão com estudante. Aprendi também que decisões de acessibilidade — como oferecer o toque simples além do arrastar — precisam entrar no design desde o começo, porque acrescentá-las depois custa retrabalho de desenvolvimento. Posso melhorar na documentação do design system, que ficou menos detalhada do que a equipe precisava.

**Kaiky Marçal Ferreira — Desenvolvedor / QA.** A maior lição foi técnica e de processo ao mesmo tempo: manter as regras de negócio fora da interface tornou a escrita dos testes viável dentro do prazo curto das sprints. Subestimei o tempo de configuração de certificados na Sprint 1, erro que a equipe transformou em uma prática nova de estimativa. Também percebi que revisar o código de outra pessoa ensina tanto quanto escrever o próprio, e passei a tratar o code review como atividade de aprendizado, não como formalidade.

**Otavio Maniezzo Milan — Desenvolvedor / QA.** Acumular desenvolvimento e liderança de qualidade me mostrou o valor de escrever os casos de teste antes de corrigir os defeitos: sem eles, a correção vira tentativa. O quadro Kanban com arrastar e soltar foi a tarefa mais complexa que já implementei, principalmente pelo comportamento inconsistente em telas pequenas, e resolvê-la exigiu admitir que a solução inicial estava errada. Preciso melhorar na validação em dispositivos físicos ao longo da sprint, e não apenas ao final dela.

# Sugestões e Críticas

> **Esta seção normalmente não existe em projetos. Foi adicionada neste documento apenas no contexto da disciplina.**

**Sugestões**

- O formato de documentar cada fase diretamente no repositório, versionada junto ao produto, foi o aspecto mais valioso da disciplina: ao final, a própria história dos commits conta a evolução do projeto, o que não aconteceria com documentos soltos.
- Seria proveitoso que a disciplina dedicasse uma aula à análise de um projeto real que tenha fracassado por falhas de gerenciamento, e não apenas de casos bem-sucedidos. Os erros ensinam de forma mais concreta os mecanismos de controle.
- A simulação da execução por protótipo funciona bem, mas ganharia realismo se o cronograma previsse uma mudança de escopo obrigatória imposta pelo professor a meio do projeto, obrigando as equipes a exercitar de fato o controle integrado de mudanças.
- Disponibilizar exemplos preenchidos dos artefatos (matriz RACI, plano de riscos, EAP) ao lado dos modelos em branco reduziria o tempo gasto para entender o formato esperado.

**Críticas**

- O volume de artefatos exigidos na fase de planejamento concentra grande esforço em uma única semana, o que se distancia da prática ágil que a própria disciplina ensina. Distribuir a entrega dos planos de gerenciamento ao longo das fases seguintes tornaria o exercício mais coerente.
- Os modelos de documento fornecidos misturam instruções e conteúdo no mesmo arquivo, o que exige um trabalho de limpeza que não agrega aprendizado. Separar instruções em um guia próprio deixaria os modelos prontos para uso.
