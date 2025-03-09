# AI Software Engineers Docs

## Visão Geral

Este starter project tem como objetivo gerar documentação automatizada para diferentes papéis dentro da engenharia de software, utilizando **Cursor AI**. A documentação será gerada no formato **README.md** e os diagramas serão criados utilizando **PlantUML**. 

## Papéis e Execução do Projeto

Cada papel desempenhará sua função específica dentro do projeto para resolver os requisitos apresentados.

### **Product Owner (PO)** - Minha documentação neste projeto
- Criar e detalhar os requisitos do sistema de forma clara e objetiva.
- Escrever histórias de usuário bem definidas com critérios de aceitação.
- Priorizar as funcionalidades de acordo com o impacto e necessidade do cliente.

### **Arquiteto de Software**  - Minha documentação neste projeto
- Definir a arquitetura do sistema, garantindo escalabilidade e boas práticas.
- Criar diagramas UML para ilustrar a estrutura e a integração dos componentes.
- Estabelecer diretrizes de desenvolvimento e padrões arquiteturais.

### **Gerente de Projetos** - Minha documentação neste projeto
- Planejar e coordenar a execução do projeto garantindo cumprimento de prazos.
- Definir metodologias ágeis e organizar os times.
- Monitorar riscos e assegurar uma comunicação eficiente entre stakeholders.

### **Analista de Requisitos** - Minha documentação neste projeto
- Documentar os requisitos funcionais e não funcionais do sistema.
- Especificar as regras de negócio e critérios de aceitação.
- Validar e revisar os requisitos com os stakeholders.

### **Desenvolvedor Sênior** - Minha documentação neste projeto
- Definir o design da aplicação e a estrutura dos módulos.
- Criar a base do código e definir padrões de implementação.
- Garantir que a arquitetura seja respeitada e que as melhores práticas sejam seguidas.

### **Desenvolvedor Júnior** - Minha documentação neste projeto
- Implementar funcionalidades de acordo com as diretrizes do desenvolvedor sênior.
- Corrigir bugs e contribuir com melhorias no código.
- Seguir as boas práticas de desenvolvimento estabelecidas pelo time.

### **QA Analyst (Analista de Qualidade)** - Minha documentação neste projeto
- Definir estratégias de testes manuais e automatizados.
- Implementar testes de regressão e validar funcionalidades.
- Garantir que todas as entregas atendam aos critérios de qualidade.

### **Designer UX/UI**  - Minha documentação neste projeto
- Criar protótipos e wireframes para a interface da extensão do Chrome.
- Definir padrões visuais e de experiência do usuário.
- Trabalhar junto aos desenvolvedores para garantir a fidelidade do design.

### **DevOps Engineer** - Minha documentação neste projeto
- Configurar a infraestrutura e pipelines de CI/CD.
- Automatizar processos de deploy e monitoramento do sistema.
- Assegurar estabilidade e segurança dos ambientes de produção.

### **Analista de Segurança** - Minha documentação neste projeto
- Realizar auditorias de segurança e testes de vulnerabilidade.
- Definir e implementar práticas de proteção de dados.
- Garantir conformidade com padrões de segurança.

### **Scrum Master**  - Minha documentação neste projeto
- Facilitar reuniões ágeis e remover impedimentos da equipe.
- Garantir que o time siga as metodologias ágeis.
- Promover melhoria contínua dentro do time.

## Requisitos do Projeto

A documentação será baseada no seguinte cenário de projeto:

Foi pedida uma aplicação onde teremos uma **extensão do Chrome** capaz de incrementar funcionalidades no navegador. Esta extensão integrará via **REST API** com uma ferramenta **low-code** chamada **Flowise**, que gera **agentes de IA** para executar determinadas tarefas.

O **Flowise** utiliza o **Databricks** para fazer chamadas para modelos de linguagem (LLMs). O fluxo do sistema será:

1. A **extensão do Chrome** envia solicitações para o **Flowise**.
2. O **Flowise** processa as solicitações e encaminha para o **Databricks**.
3. O **Databricks** executa chamadas aos modelos de IA e retorna os resultados ao **Flowise**.
4. O **Flowise** retorna os resultados para a **extensão do Chrome**.

## Estrutura da Documentação

Cada papel terá uma seção dedicada contendo:

- **Descrição do Papel**
- **Execução das Responsabilidades no Projeto**
- **Diagrama UML Representativo**
- **Fluxo de Trabalho**
- **Principais Entregáveis**

## Diagramas

Os diagramas serão gerados no formato **PlantUML** e incluirão:

- Diagramas de fluxo entre os componentes
- Diagramas de interação entre os papéis
- Diagramas de arquitetura do sistema

## Execução

O **Cursor AI** será responsável por gerar automaticamente a documentação no arquivo **doc_ai_software.md**, garantindo que:

- Cada papel desempenhe sua função específica para atender aos requisitos do projeto.
- A arquitetura e design do software sejam bem definidos e documentados.
- Diagramas em **PlantUML** ilustrem as interações entre os componentes e papéis.
- As melhores práticas de desenvolvimento e padrões sejam seguidos na documentação.
- Cada papel deve ter um arquivo .md proprio com sua documentação neste projeto.




