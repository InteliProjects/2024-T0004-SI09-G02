# Documentação do Diagrama de Componentes Sistema de Controle de Dados Gerenciais da Volkswagen

## Introdução

O desenvolvimento de sistemas complexos exige uma compreensão detalhada de sua arquitetura e interações no sistema. Nesse contexto, o diagrama de componentes, nos proporciona uma visão estrutural boa, destacando as dependências entre os elementos do sistema. O seu foco se concentra na representação gráfica dos componentes e suas interconexões, fornecendo possíveis insights sobre a execução e reutilização do sistema.

No contexto do nosso projeto, a aplicação do diagrama de componentes será para mapear os módulos independentes e compreender a infraestrutura do sistema. Este texto explorará alguns dos componentes fundamentais do nosso sistema, delineando suas funções específicas e relacionamento.

# Estrutura do Diagrama de Componentes

## 1. Componentes
   - **Definição:**
     - Os componentes representam unidades independentes e modularizadas do sistema. Cada componente é encarregado de realizar uma função específica, contribuindo para o funcionamento geral da aplicação.

## 2. Interfaces
   - **Definição:**
     - As interfaces representam os pontos de comunicação entre os componentes. Elas especificam como os componentes interagem uns com os outros, definindo os métodos ou serviços disponíveis.
   - **Representação Gráfica:**
     - As interfaces são geralmente simbolizadas por linhas conectando os componentes, indicando a direção da comunicação e os serviços disponíveis.

## 3. Relacionamentos
   - **Definição:**
     - Os relacionamentos entre os componentes descrevem as dependências e conexões entre eles. Essas relações podem incluir associações, dependências ou até mesmo heranças.
   - **Representação Gráfica:**
     - Linhas e setas indicam a direção do relacionamento.

## 4. Notações Adicionais
   - **Definição:**
     - Para facilitar a compreensão, componentes relacionados podem ser agrupados em pacotes, destacando áreas específicas de funcionalidade.
   - **Notas e Restrições:**
     - Elementos de texto, notas e restrições podem ser adicionados ao diagrama para fornecer informações adicionais sobre determinados componentes ou relações.

## Diagrama de Componentes

O diagrama de componentes é uma ferramenta muito útil para entender as peculiaridades de um sistema completa. Por definição o diagrama de componentes, é um tipo de modelagem estrutural do sistema e as suas dependências de componentes. Isto se deve pelo fato de que o diagrama de componentes descreve os aspectos de execução e reutilização do sistema, com a identificação de componentes de possíveis subsistemas ou classes embutidas. Em termos mais simples, um componente é uma unidade independente que integra uma parte específica do sistema, e o diagrama de componentes mostra como esses componentes se interagem.

A aplicação do diagrama de componentes, em nosso projeto, representará os módulos independentes do nosso sistema, levando em consideração à infraestrutura em si. Neste caso, separamos aqui alguns dos componentes essenciais em nosso diagrama:

![Diagrama_Componentes](https://github.com/Inteli-College/2024-T0004-SI09-G02/assets/99209356/d6dad975-091a-4740-ba6e-b0d404098824)

1. Microsserviço de busca dos dados incial, será responsável pelo carregamento dos dados que foram provisionados pelo cliente e será armazenado no banco de dados. Após este carregamento haverá a conexão com Backend (.NET) via uma conexão Node.js.

2. Backend (.NET): Este é o servidor central onde os dados são processados antes de serem entregues ao Frontend (Angular).

    a. O backend também recebe dados de um script através de Microsserviço em Python, que é responsável pela Análise de padrões e tendências.

    b. Outra informação que alimentará este backend será o Registro de logs armazenados em outro banco de dados.

    c. A partir desses dados haverá a alimentação de informações para o frontend.

3. Frontend (Angular): Representa a interface do usuário onde os dados são apresentados visualmente.

    a. Requisições HTTP: Protocolo usado para comunicação entre o backend e o frontend.

5. Microserviço Python: Dedicado à análise de padrões e tendências nos dados armazenados.

## Conclusão

Nesta documentação, pudemos entender um pouco mais da arquitetura do nosso sistema utilizando o Diagrama de Componentes. Ao entender a estrutura, componentes, interfaces, relacionamentos, ganhamos uma base sólida para o desenvolvimento do projeto, principalmente para o criar o sistema. Aqui também, obtivemos a visualização do diagrama completo em termos gráficos, A representação visual dos componentes e suas interações auxilia na identificação de potenciais problemas e na otimização da eficiência do sistema.

Em resumo, esta documentação sobre diagrama de componentes servirá como um recurso valioso ao longo do ciclo de vida do projeto, orientando as decisões de arquitetura do sistema e facilitando a colaboração da equipe.