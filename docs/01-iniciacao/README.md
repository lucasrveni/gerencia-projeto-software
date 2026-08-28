# Iniciação

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

O projeto **UneTask** consiste no desenvolvimento de uma aplicação mobile multiplataforma (Web, iOS e Android) voltada para o ambiente escolar e acadêmico. A solução tem como proposta centralizar o gerenciamento de tarefas, atividades e prazos avaliativos em uma única plataforma, proporcionando aos estudantes do ensino básico ao superior uma ferramenta intuitiva e eficiente para organizar sua rotina de estudos.

O UneTask integra funcionalidades de cadastro e categorização de tarefas por matéria, um dashboard com gráficos de acompanhamento de status e um quadro interativo baseado em metodologias ágeis (Scrum/Kanban), permitindo que o aluno visualize, organize e controle todas as suas demandas acadêmicas de forma visual e dinâmica.

## Problema

A rotina dos estudantes, desde a educação básica até o ensino superior, é frequentemente comprometida por uma severa sobrecarga de atividades, dispersão de anotações e grande dificuldade no controle de prazos entre múltiplas disciplinas. Somado a isso, as ferramentas genéricas de produtividade disponíveis atualmente não atendem às especificidades e à dinâmica do ambiente escolar e acadêmico. Esse cenário gera uma constante desorganização, dificuldade na gestão do próprio tempo e, consequentemente, a perda de entregas importantes e o comprometimento do desempenho e da autonomia do aluno.

## Objetivos

**Objetivo Geral**
Desenvolver uma aplicação mobile direcionada ao ambiente escolar e acadêmico que integre o gerenciamento prático de tarefas à visualização ágil de progresso, visando otimizar a produtividade e estimular a autonomia do estudante na gestão do próprio tempo.

**Objetivos Específicos**

* Implementar uma funcionalidade para a categorização precisa das demandas e atividades acadêmicas separadas por matéria.
* Criar painéis de métricas visuais, como gráficos de status, que permitam o acompanhamento claro do ciclo de vida e do fluxo de trabalho de cada atividade.
* Construir um quadro interativo baseado em metodologias ágeis (Scrum/Kanban) para a manipulação dinâmica e o controle efetivo do cumprimento de prazos avaliativos.
* Centralizar a rotina de estudos em uma plataforma única e acessível, reduzindo a dispersão de anotações e a fricção no planejamento diário do aluno.

## Justificativa

O desenvolvimento do UneTask justifica-se pela urgente necessidade de preencher uma lacuna deixada pelas ferramentas genéricas de produtividade, que falham por não atenderem às especificidades e à intensa dinâmica do ambiente escolar e acadêmico. Existe uma clara demanda por uma solução acessível e direcionada que compreenda as dificuldades reais dos estudantes, desde a educação básica até o ensino superior, mitigando os gargalos causados pela sobrecarga de atividades, dispersão de informações e perda de prazos.

Com a construção deste projeto, os benefícios esperados incluem a centralização completa da rotina de estudos em uma única plataforma, a eliminação da dispersão de anotações e a drástica redução da fricção no planejamento diário. O impacto previsto na rotina dos usuários é o aumento significativo da organização pessoal e da produtividade, assegurando o cumprimento pontual de todas as entregas avaliativas. A longo prazo, a iniciativa visa não apenas resolver um problema organizacional, mas impactar positivamente o desenvolvimento pessoal do aluno, estimulando sua autonomia e independência na gestão do seu próprio tempo.

## Critérios de Sucesso

Para avaliar o êxito do projeto UneTask e confirmar se os objetivos estabelecidos foram plenamente alcançados, foram definidos os seguintes critérios de sucesso:

* **Entrega do Escopo e Qualidade do Produto:** Desenvolvimento e disponibilização de uma aplicação mobile totalmente funcional, com interface intuitiva e livre de falhas críticas, contendo todas as funcionalidades principais estipuladas (categorização de demandas por matéria, painéis com gráficos de status e quadro interativo baseado em Scrum/Kanban).
* **Cumprimento do Cronograma:** Conclusão de todas as fases de planejamento, desenvolvimento, testes e implantação dentro dos prazos do calendário acadêmico estabelecido para a equipe.
* **Satisfação e Adoção do Usuário Final:** Obtenção de feedback positivo e validação por parte do público-alvo (estudantes da educação básica ao ensino superior) durante as rodadas de testes, comprovando na prática a redução da fricção no planejamento diário e a facilidade na gestão do tempo.
* **Aprovação das Partes Interessadas:** Aceitação formal de todas as entregas do projeto e aprovação final pela professora responsável, Janecler Foppa, atestando que os requisitos técnicos e as expectativas do projeto foram atendidos com eficiência e qualidade. 

# Partes Interessadas

> ![Ícone](https://img.icons8.com/?size=15&id=2WXhtObwrKRz&format=png&color=51946e)
[Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Identificação das Partes Interessadas

| Nome | Posição / Cargo | Papel no Projeto |
| --- | --- | --- |
| **GUILLERMO GILIOLI DE P. COELHO** | Gerente | Coordena o planejamento, a execução e a entrega |
| **KAIKY MARÇAL FERREIRA** | Desenvolvedor e QA | Cria o código funcional do sistema, garante que esse produto atenda aos padrões de qualidade e esteja livre de erros. |
| **LUCAS DA ROSA** | Designer UI/UX | Garantir que o produto seja funcional, intuitivo, acessível e esteticamente agradável para o usuário final |
| **OTAVIO MANIEZZO MILAN** | Desenvolvedor e QA | Cria o código funcional do sistema, garante que esse produto atenda aos padrões de qualidade e esteja livre de erros. |
| **RYLLER BRITO PEREIRA** | Product Owner e Analista | Define a visão estratégica e o valor do produto, foca no detalhamento técnico e na especificação funcional das necessidades. |

## Avaliação das Partes Interessadas

| Nome | Apoio | Influência | Poder |
| --- | --- | --- | --- |
| **GUILLERMO GILIOLI** | Apoiador | Alta | Alta |
| **KAIKY MARÇAL** | Apoiador | Alta | Média |
| **LUCAS DA ROSA** | Apoiador | Baixa | Baixa |
| **OTAVIO MANIEZZO** | Apoiador | Alta | Média |
| **RYLLER BRITO** | Apoiador | Média | Média |

# Termo de Abertura do Projeto

> ![Ícone](https://img.icons8.com/?size=15&id=mUaiYELHrRew&format=png&color=2d6188)
[Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

| Item de custo | Qtd. horas | Valor / hora | Valor total |
| --- | --- | --- | --- |
| **Recursos Humanos** |  |  |  |
| Guillermo Gilioli (Gerente) | 120h | R$ 80,00 | R$ 9.600,00 |
| Kaiky Marçal (Dev/QA) | 200h | R$ 60,00 | R$ 12.000,00 |
| Lucas da Rosa (Designer) | 120h | R$ 60,00 | R$ 7.200,00 |
| Otavio Milani (Dev/QA) | 200h | R$ 60,00 | R$ 12.000,00 |
| Ryller Brito (PO/Analista) | 160h | R$ 70,00 | R$ 11.200,00 |
| **Hardware** |  |  |  |
| Equipamentos de desenvolvimento (Notebooks/Workstations) | - | - | R$ 0,00 |
| **Rede e serviços de hospedagem (Firebase/AWS)** | - | - | R$ 300,00 |
| **Software de terceiros (Contas Google/Apple)** | - | - | R$ 750,00 |
| **Serviços e treinamento** | - | - | R$ 0,00 |
| **Total Geral** | - | - | **R$ 53.050,00** |

## Estimativa de Prazo

| Descrição | Valor |
| --- | --- |
| **Prazo previsto (horas)** | 800 |
| **Data prevista de início** | 03/08/2026 |
| **Data prevista de término** | 10/09/2026 |

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas.

### Premissas

- O projeto será desenvolvido como aplicativo mobile multiplataforma (Web, iOS e Android)
- A equipe possui conhecimento técnico em desenvolvimento mobile e frameworks como Flutter ou React Native
- Será utilizada infraestrutura em nuvem (Firebase/AWS) para backend e banco de dados
- O público-alvo são estudantes do ensino básico ao superior
- O produto final será publicado nas lojas Google Play Store e Apple App Store
- Será necessária a conformidade com a LGPD para dados de estudantes

## Declaração de Escopo

> Referência:
![Ícone](https://img.icons8.com/?size=15&id=mUaiYELHrRew&format=png&color=2d6188)
[Declaração de Escopo](artefatos/declaracao-escopo.docx)

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto.

|ID    | Descrição do Requisito                                                                 | Prioridade |
|------|----------------------------------------------------------------------------------------|------------|
|RF-001| Permitir cadastro de tarefas com título, descrição, matéria, data de criação e prazo   | ALTA       |
|RF-002| Permitir edição de tarefas cadastradas                                                  | ALTA       |
|RF-003| Permitir exclusão de tarefas                                                            | ALTA       |
|RF-004| Categorizar tarefas por matéria/disciplina                                              | ALTA       |
|RF-005| Exibir lista de tarefas com filtros por matéria, status e prazo                         | ALTA       |
|RF-006| Exibir dashboard com gráficos de status das atividades                                  | ALTA       |
|RF-007| Disponibilizar quadro interativo Kanban/Scrum com colunas de status (A Fazer, Em Andamento, Concluído) | ALTA |
|RF-008| Permitir arrastar e soltar cards entre colunas no quadro Scrum                          | ALTA       |
|RF-009| Autenticar usuário via OAuth (Gmail e Apple ID/iCloud)                                  | ALTA       |
|RF-010| Autenticar usuário via e-mail e senha                                                   | ALTA       |
|RF-011| Exportar listas de tarefas para salvamento externo                                      | MÉDIA      |
|RF-012| Visualizar número do card, status, data de criação e data de envio na listagem          | MÉDIA      |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto.

|ID     | Descrição do Requisito                                                                 | Prioridade |
|-------|----------------------------------------------------------------------------------------|------------|
|RNF-001| Suporte a dispositivos móveis iOS e Android                                            | ALTA       |
|RNF-002| Interface responsiva para diferentes tamanhos de tela                                   | ALTA       |
|RNF-003| Processar requisições do usuário em no máximo 3 segundos                               | MÉDIA      |
|RNF-004| Sincronização em tempo real entre dispositivos                                         | ALTA       |
|RNF-005| Conformidade com a LGPD para dados pessoais de estudantes                              | ALTA       |
|RNF-006| Interface intuitiva e acessível para estudantes do ensino básico ao superior            | ALTA       |
|RNF-007| Disponibilidade mínima de 99,9% do serviço em nuvem                                   | MÉDIA      | 


### Restrições

A tabela a seguir apresenta as restrições do projeto.

|ID    | Descrição do Requisito                                                                 | Prioridade |
|------|----------------------------------------------------------------------------------------|------------|
|RE-001| O projeto deve ser concluído até 10/09/2026                                            | ALTA       |
|RE-002| Orçamento total limitado a R$ 53.050,00                                                | ALTA       |
|RE-003| Equipe composta por 5 membros com papéis específicos                                   | MÉDIA      |
|RE-004| Uso obrigatório de ferramentas de versionamento (Git/GitHub)                           | MÉDIA      |
|RE-005| Publicação nas lojas Google Play Store e Apple App Store                               | ALTA       |
|RE-006| Conformidade com diretrizes de privacidade da Apple e Google                           | MÉDIA      |

### Contra-Escopo

A tabela a seguir apresenta as atividades que não serão executadas no projeto.

|ID    | Descrição do Contra-Escopo                                                          |
|------|-------------------------------------------------------------------------------------|
|CE-001| Integração com Google Classroom ou outros sistemas de gestão escolar                 |
|CE-002| Funcionalidade de chat interno entre estudantes e professores                        |
|CE-003| Treinamento de modelos de Inteligência Artificial para recomendações                |
|CE-004| Suporte a múltiplos idiomas (internacionalização)                                   |
|CE-005| Desenvolvimento de versão para desktop                                      |
|CE-006| Integração com calendarização acadêmica de instituições específicas                  |

### Condições para início do Projeto

A tabela a seguir apresenta as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto                                       |
|------|-------------------------------------------------------------------------------------|
|CI-001| Aprovação do Termo de Abertura do Projeto pelo responsável              |
|CI-002| Confirmação da disponibilidade de todos os membros da equipe                        |
|CI-003| Definição da infraestrutura de desenvolvimento (repositório GitHub, ferramentas)    |
|CI-004| Criação das contas de desenvolvedor nas lojas Google Play e Apple App Store         |

## Marcos Agendados e Entregas

A tabela a seguir identifica os marcos do projeto e os entregáveis previstos.

|ID   | Marco do Projeto                                                                 | Data Prevista |
|-----|----------------------------------------------------------------------------------|---------------|
|M-1  | Aprovação do Termo de Abertura do Projeto                                        | 03/08/2026    |
|M-2  | Conclusão da Prototipação UI/UX das 3 Telas                                      | 10/08/2026    |
|M-3  | Entrega do Sprint 1 - Módulo de Autenticação                                     | 17/08/2026    |
|M-4  | Entrega do Sprint 2 - Módulo de Tarefas & Matérias                               | 24/08/2026    |
|M-5  | Entrega do Sprint 3 - Módulo Interativo Scrum/Kanban                             | 31/08/2026    |
|M-6  | Entrega do Sprint 4 - Testes Integrados e Garantia de Qualidade (QA)             | 07/09/2026    |
|M-7  | Publicação nas lojas Google Play Store e Apple App Store                          | 10/09/2026    |

# Metodologia

O projeto UneTask adota a metodologia ágil **Scrum** como framework de gestão e desenvolvimento. O Scrum foi escolhido por sua flexibilidade, capacidade de adaptação a mudanças de requisitos e por promover entregas incrementais e iterativas, permitindo validação contínua do produto com as partes interessadas.

## Estrutura do Scrum

### Papéis

- **Product Owner (PO):** Responsável por definir a visão do produto, priorizar o Product Backlog e garantir que as entregas atendam às expectativas dos stakeholders.
- **Scrum Master:** Facilita os processos do Scrum, remove impedimentos e garante que a equipe siga as práticas ágeis.
- **Equipe de Desenvolvimento:** multidisciplinar, composta por desenvolvedores mobile, desenvolvedor backend/cloud, designer UI/UX e analista de QA, responsável por entregar o incremento do produto a cada Sprint.

### Eventos

- **Sprint:** Ciclos de desenvolvimento com duração de **1 semana**, totalizando 4 sprints na fase de execução.
- **Sprint Planning:** Reunião no início de cada sprint para planejar as tarefas a serem executadas.
- **Daily Scrum:** Reunião diária de 15 minutos para sincronização da equipe e identificação de impedimentos.
- **Sprint Review:** Reunião ao final de cada sprint para demonstrar o incremento entregue aos stakeholders.
- **Sprint Retrospective:** Reunião de retrospectiva para identificar melhorias nos processos da equipe.

### Artefatos

- **Product Backlog:** Lista priorizada de todas as funcionalidades e requisitos do produto.
- **Sprint Backlog:** Conjunto de tarefas selecionadas para execução na sprint atual.
- **Incremento:** Produto funcional entregue ao final de cada sprint.

## Divisão de Papéis

| Nome                    | Papel no Projeto                  | Principais Responsabilidades                                                                 |
|-------------------------|-----------------------------------|---------------------------------------------------------------------------------------------|
| **GUILLERMO GILIOLI**   | Gerente / Scrum Master            | Coordena o planejamento, execução e entrega; facilita os eventos Scrum e remove impedimentos |
| **RYLLER BRITO**        | Product Owner / Analista          | Define a visão estratégica do produto, prioriza o backlog e especifica requisitos técnicos   |
| **KAIKY MARÇAL**        | Desenvolvedor Mobile / QA         | Desenvolve o código mobile, implementa funcionalidades e garante a qualidade do produto      |
| **OTAVIO MANIEZZO**     | Desenvolvedor Mobile / QA         | Desenvolve o código mobile, implementa funcionalidades e garante a qualidade do produto      |
| **LUCAS DA ROSA**       | Designer UI/UX                    | Projeta a interface do usuário, garante usabilidade, acessibilidade e experiência visual      |

## Ferramentas

| Ambiente                    | Plataforma           | Link de Acesso                      | Justificativa                                                                       |
|-----------------------------|----------------------|-------------------------------------|-------------------------------------------------------------------------------------|
| Quadro Kanban / Sprint Board| GitHub Projects      | https://github.com/users/lucasrveni/projects/5/views/1?system_template=kanban                  | Centralização e organização do projeto no próprio repositório com visualização ágil  |
| Repositório de código       | GitHub               | https://github.com/lucasrveni/gerencia-projeto-software/tree/main/code                  | Controle de versão, colaboração e histórico de alterações no código-fonte            |
| Protótipo Interativo        | Figma                | https://www.figma.com/design/wSAvNL98JkSHNnCq0Lweqw/UneTask?node-id=0-1&t=Nlw634oMXg86fAxf-1                   | Design de interface (UI/UX), criação de protótipos navegáveis e handoff para devs   |
| Documentos Textuais         | Google Docs          | PENDENTE             | Elaboração e colaboração em documentos do projeto (atas, especificações)            |
| Planilhas e Gráficos        | Google Sheets        | PENDENTE             | Gestão de cronograma, estimativas, matriz RACI e análise de custos                   |                 |
| Cronograma do Projeto       | Google Sheets        | PENDENTE             | Acompanhamento visual do cronograma e marcos do projeto                              |
| Matriz RACI                 | Google Sheets        | PENDENTE             | Definição de responsabilidades por atividade entre os membros da equipe              |            |
| Controle de Versão          | Git                  | Github                                 | Versionamento local do código antes do push para o repositório remoto                |

