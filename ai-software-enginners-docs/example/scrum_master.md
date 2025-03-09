# Documentação do Scrum Master

## Descrição do Papel
O Scrum Master é responsável por facilitar o processo Scrum, remover impedimentos da equipe e promover práticas ágeis efetivas para maximizar a produtividade e qualidade das entregas.

## Execução das Responsabilidades no Projeto

### 1. Framework Scrum

```plantuml
@startuml
rectangle "Sprint" {
  card "Planning" as SP
  card "Daily" as SD
  card "Review" as SR
  card "Retrospective" as ST
}

SP -> SD
SD -> SR
SR -> ST
ST -> SP : Próximo Sprint
@enduml
```

### 2. Rituais Ágeis

#### Sprint Planning
```plantuml
@startuml
start
:Revisar Product Backlog;
:Definir Objetivo do Sprint;
:Estimar User Stories;
:Criar Sprint Backlog;
:Planejar Capacidade;
stop
@enduml
```

#### Daily Scrum
```plantuml
@startuml
actor "Time" as TM
actor "Scrum Master" as SM

TM -> SM: O que fez ontem?
TM -> SM: O que fará hoje?
TM -> SM: Há impedimentos?

note right of SM
  - Timeboxing: 15 min
  - Mesmo horário
  - Mesmo local
end note
@enduml
```

### 3. Gestão de Impedimentos

```plantuml
@startuml
rectangle "Impedimentos" {
  card "Identificação" as ID
  card "Análise" as AN
  card "Resolução" as RS
  card "Acompanhamento" as AC
}

ID --> AN
AN --> RS
RS --> AC
@enduml
```

## Ferramentas e Práticas

### 1. Quadro Kanban
```plantuml
@startuml
package "Quadro Kanban" {
  [Backlog] as BL
  [To Do] as TD
  [In Progress] as IP
  [Review] as RV
  [Done] as DN
}

BL -> TD
TD -> IP
IP -> RV
RV -> DN
@enduml
```

### 2. Métricas Ágeis
```plantuml
@startuml
rectangle "Métricas" {
  card "Velocity" as VL
  card "Burndown" as BD
  card "Cycle Time" as CT
  card "Lead Time" as LT
}

VL --> BD
BD --> CT
CT --> LT
@enduml
```

### 3. Facilitação de Reuniões
```plantuml
@startuml
start
:Preparar Agenda;
:Definir Objetivos;
:Gerenciar Tempo;
:Garantir Participação;
:Documentar Decisões;
stop
@enduml
```

## Práticas de Melhoria Contínua

### 1. Retrospectivas
```markdown
## Template de Retrospectiva

### 1. O que foi bem?
- Pontos positivos
- Conquistas
- Práticas efetivas

### 2. O que pode melhorar?
- Desafios
- Obstáculos
- Oportunidades

### 3. Ações
- Responsável
- Prazo
- Métricas
```

### 2. Health Check
```plantuml
@startuml
scale 1
rectangle "Saúde do Time" {
  card "Comunicação" as CM
  card "Colaboração" as CL
  card "Qualidade" as QL
  card "Velocidade" as VL
}

CM --> CL
CL --> QL
QL --> VL
@enduml
```

## Comunicação e Documentação

### 1. Relatórios
```markdown
## Status Report

### Sprint Overview
- Sprint Goal:
- Start Date:
- End Date:
- Velocity:

### Progress
- Completed Stories:
- Story Points Delivered:
- Blockers Resolved:

### Team Health
- Moral:
- Productivity:
- Quality:
```

### 2. Documentação Ágil
```plantuml
@startuml
package "Documentação" {
  [Definition of Ready] as DR
  [Definition of Done] as DD
  [Team Agreements] as TA
  [Working Agreements] as WA
}

DR --> DD
DD --> TA
TA --> WA
@enduml
```

## Principais Responsabilidades

### 1. Com o Time
- Facilitar eventos Scrum
- Remover impedimentos
- Proteger o time
- Promover auto-organização
- Coaching ágil

### 2. Com a Organização
- Promover práticas ágeis
- Auxiliar transformação
- Treinar outros times
- Compartilhar conhecimento
- Melhorar processos

## Principais Entregáveis
1. Facilitação de eventos Scrum
2. Relatórios de progresso
3. Documentação de processos
4. Métricas de agilidade
5. Planos de melhoria

## Métricas de Sucesso
- Velocidade do time
- Satisfação da equipe
- Previsibilidade de entregas
- Qualidade do produto
- Maturidade ágil 