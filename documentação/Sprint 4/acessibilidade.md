# Teste de Acessibilidade - Critério de Sucesso 1.3.3 - Características Sensoriais - Perceptível

Este documento descreve os testes de acessibilidade realizados conforme os Critérios de Sucesso da WCAG (Web Content Accessibility Guidelines) versão 2.1.

## Sumário

1. [Teste 1: Critério de Sucesso 1.3.3 - Características Sensoriais](#teste-1-critério-de-sucesso-133---características-sensoriais)
2. [Teste 2: Critério de Sucesso 2.4.4 - Finalidade do Link](#teste-2-critério-de-sucesso-244---finalidade-do-link)
3. [Teste 3: Critério de Sucesso 3.1.1 - Idioma da Página](#teste-3-critério-de-sucesso-311---idioma-da-página)
4. [Teste 4: Critério de Sucesso 3.2.1 - Em Foco](#teste-4-critério-de-sucesso-321---em-foco)

## Tabela de Testes

| Teste                     | Descrição                  | Tipo          |
| ------------------------- | -------------------------- | ------------- |
| Critério de Sucesso 1.3.3 | Características Sensoriais | Perceptível   |
| Critério de Sucesso 2.4.4 | Finalidade do Link         | Operável      |
| Critério de Sucesso 3.1.1 | Idioma da Página           | Compreensível |
| Critério de Sucesso 3.2.1 | Em Foco                    | Compreensível |

---

## Usuários

| Usuário           | Descrição                                                      |
| ----------------- | -------------------------------------------------------------- |
| Mulher de 29 anos | Gestora com leve deficiência visual                            |
| Mulher de 35 anos | Especialista em interpretação de dados e gráficos complexos    |
| Homem de 23 anos  | Usuário comum com experiência em navegação na web em português |

## Metodologia

Nesta seção, descrevemos o processo de teste utilizado, os critérios de seleção dos participantes, as ferramentas e os métodos aplicados.

## Processo de Teste

Utilizamos uma abordagem prática de testes com usuários para avaliar a acessibilidade e usabilidade do site. Durante esta fase, os participantes foram convidados a interagir com o site e realizar uma série de micro-tarefas representativas das atividades usuais.

### Principais Etapas do Processo:

1. **Seleção dos Participantes:**

   - Escolhemos uma amostra diversificada de usuários, incluindo aqueles com diferentes perfis, habilidades e experiências de navegação na web.

2. **Definição das Tarefas:**

   - Identificamos uma lista de micro-tarefas que abrangiam diversas áreas e funcionalidades do site.
   - As tarefas foram elaboradas para refletir as atividades comuns realizadas pelos usuários durante a navegação no site.

3. **Execução dos Testes:**

   - Cada participante recebeu as instruções para realizar as tarefas designadas no site.
   - Durante a execução das tarefas, observamos atentamente o comportamento dos usuários, registrando suas interações e eventuais dificuldades encontradas.

4. **Análise dos Resultados:**

   - Após a conclusão dos testes, analisamos os registros e observações para identificar padrões, tendências e problemas recorrentes.
   - Classificamos os problemas encontrados em termos de severidade, considerando seu impacto na experiência do usuário e na conformidade com os critérios de acessibilidade.

### Melhorias Propostas no Processo de Teste:

- Incorporamos uma abordagem prática e direta de testes com usuários, proporcionando insights valiosos sobre a experiência real de navegação no site.
- Garantimos que as tarefas designadas aos usuários fossem representativas das atividades usuais realizadas no site, permitindo uma avaliação abrangente da acessibilidade e usabilidade.
- Utilizamos uma abordagem iterativa, permitindo ajustes contínuos no processo com base nos resultados obtidos e no feedback dos usuários.

---

### Critérios de Seleção dos Participantes

Os participantes foram selecionados com base em perfis específicos que representam diferentes grupos de usuários. Foram escolhidos usuários com deficiência visual, especialistas em interpretação de dados e usuários comuns com experiência em navegação na web em português.

## Resultados

Os resultados dos testes de acessibilidade serão apresentados em detalhes, incluindo os problemas encontrados e sua classificação em termos de severidade.

## Recomendações

Serão propostas soluções para cada problema identificado durante os testes, justificando as escolhas e prioridades para implementação.

### Problemas Identificados

| Número do Problema | Descrição do Problema                                                                                                                | Severidade | Sugestão de melhoria                                                                                                         |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Alguns dados não são completamente explicados, principalmente os apresentados nos cards.                                             | Baixa      | Acrescentar um tutorial para explicar os dados de forma mais completa. Esta melhoria fica para a versão 2 do dashboard.      |
| 2                  | Os links funcionam perfeitamente, porém alguns deles, como o de visualizar funcionário, poderiam abrir em uma nova aba do navegador. | Média      | Implementar a abertura de certos links em uma nova aba do navegador. Essa implementação será analisada para futura execução. |
| 3                  | A identificação do idioma no site é fácil, mas poderia haver a opção de outros idiomas.                                              | Média      | Adicionar a opção de outros idiomas para melhor acessibilidade.                                                              |
| 4                  | A letra em alguns pontos do site é muito pequena, o que pode dificultar a leitura para alguns usuários.                              | Alta       | Aumentar o tamanho da letra, especialmente dentro dos gráficos, para melhorar a acessibilidade.                              |

---

## Objetivo do Teste

O objetivo destes testes é verificar se o site é perceptível e adaptável, conforme exigido pelo Critério de Sucesso 1.3.3 do WCAG 2.1. Isso significa garantir que as instruções ou direcionamentos apresentados no site não dependam de características sensoriais específicas, como cor, som ou posição espacial, por exemplo.

# Teste 1: Critério de Sucesso 1.3.3 - Características Sensoriais

Este teste descreve um cenário para avaliar a conformidade do site com o Critério de Sucesso 1.3.3 do WCAG 2.1 que é
garantir que todos os utilizadores possam aceder às instruções de utilização do conteúdo, mesmo quando não consigam perceber a forma ou o tamanho ou utilizar informações sobre a localização ou orientação espacial. Alguns conteúdos dependem do conhecimento da forma ou posição de objetos que não estão disponíveis na estrutura do conteúdo (por exemplo, “botão redondo” ou “botão à direita”). Alguns utilizadores com deficiência não são capazes de perceber a forma ou a posição devido à natureza das tecnologias de apoio que utilizam. Este Critério de Sucesso exige que sejam fornecidas informações adicionais para esclarecer instruções que dependem deste tipo de informações.

## Objetivo do Teste

O objetivo deste teste é verificar se o site é perceptível e adaptável, conforme exigido pelo Critério de Sucesso 1.3.3 do WCAG 2.1. Isso significa garantir que as instruções ou direcionamentos apresentados no site não dependam de características sensoriais específicas, como cor, som ou posição espacial.

## Cenário de Teste

O usuário será convidado a completar uma tarefa específica no site sem depender de instruções que envolvam características sensoriais.

### Descrição do Cenário:

O usuário é uma mulher de 29 anos, que trabalha com gestão e está acostumada a lidar com planilhas e dados. Ela tem uma leve deficiência visual e depende de óculos para navegar na web.

#### Momento 1:

- **Tarefa 1:** Encontrar a página de organização.
- **Instruções:** Navegar até a seção de organização e localizar o nome do colaborador Luiz Ricardo de Medeiros Santiago.

#### Momento 2:

- **Tarefa 2:** Verificar a nota do colaborador.
- **Instruções:** Identificar se o nome do colaborador é clicável e, em seguida, acessar a página do colaborador para verificar sua nota.

## Avaliação do Desempenho do Usuário

Após a conclusão da tarefa, o desempenho do usuário em termos de dificuldade encontrada:

A usuária apresentou um atraso inicial para reconhecer a interface do site, mas não enfrentou dificuldades significativas na leitura. Ela apreciou as marcações nos nomes dos colaboradores, o que facilitou sua busca. A usuária identificou facilmente o nome do colaborador como clicável e encontrou a nota desejada com facilidade, principalmente devido à distinção visual da nota em relação ao restante da página.

## Resultados do Teste

Em relação ao Critério de Sucesso 1.3.3 do WCAG 2.1, que aborda as características sensoriais, a usuária conseguiu completar o teste com baixa dificuldade.
<br><br><br><br>

# Teste 2: Critério de Sucesso 2.4.4 - Finalidade do Link

Este teste descreve um cenário para avaliar a conformidade do site com o Critério de Sucesso 2.4.4 do WCAG 2.1, que é ajudar os utilizadores a compreender a finalidade de cada link para que possam decidir se pretendem segui-lo. Sempre que possível, forneça um texto do link que identifique a finalidade do link sem a necessidade de contexto adicional. A tecnologia assistiva tem a capacidade de fornecer aos usuários uma lista de links que estão na página da Web. O texto do link que seja o mais significativo possível ajudará os usuários que desejam escolher nesta lista de links. O texto do link significativo também ajuda aqueles que desejam navegar de um link para outro. Links significativos ajudam os usuários a escolher quais links seguir sem exigir estratégias complicadas para entender a página.

## Objetivo do Teste

O objetivo deste teste é verificar se a finalidade dos links é claramente determinada a partir do texto do link ou do contexto ao redor do link. Como nosso site não possui link diretos na página principal, decidimos abordar se o conteúdo do gráfico é clicável.

## Cenário de Teste

A usuária será convidada a completar uma série de tarefas no site que exigem a identificação e compreensão dos "links" no contexto em que estão inseridos.

### Descrição do Cenário:

A usuária é uma analista de dados de 35 anos que trabalha em uma empresa de consultoria. Ela está acostumada a interpretar dados e gráficos.

#### Tarefas:

1. Localizar o gráfico de quantidade de sessões do Zenclub por ano.
2. Verificar a diferença entre a quantidade de consultas no mês de novembro entre duas plantas: Curitiba e São Carlos.
3. Identificar as ações disponíveis dentro do gráfico para aumentar a discrepância entre as duas plantas.

## Avaliação do Desempenho do Usuário

Após a conclusão da tarefa, o desempenho do usuário em termos de dificuldade encontrada:

A usuária apresentou um bom desempenho na identificação e compreensão dos links, utilizando efetivamente o contexto fornecido. Ela conseguiu localizar o gráfico desejado e entender as diferenças entre as plantas, porém apresentou alguma dificuldade em identificar que a legenda do gráfico era clicável.

## Resultados do Teste

Em relação ao Critério de Sucesso 2.4.4 do WCAG 2.1, a usuária conseguiu completar as tarefas com sucesso, demonstrando uma compreensão eficaz da finalidade dos links no contexto.

## Observações Adicionais

Para melhorar a usabilidade e até mesmo a acessibilidade, seria interessante colocar uma bordar ou sublinhado na legenda dos gráficos, além de mudar o ponteiro do mouse para melhor indicar que o gráfico é clicável.

---

# Teste 3: Critério de Sucesso 3.1.1 - Idioma da Página

Este teste descreve um cenário para avaliar a conformidade do site com o Critério de Sucesso 3.1.1 do WCAG 2.1, que é garantir que os criadores de conteúdos fornecem informações na página Web de que os agentes dos utilizadores necessitam para apresentar correctamente o texto e outros conteúdos linguísticos. Tanto as tecnologias assistivas quanto os agentes de usuário convencionais podem renderizar o texto com mais precisão quando o idioma da página da Web é identificado. Os leitores de tela podem carregar as regras de pronúncia corretas. Os navegadores visuais podem exibir caracteres e scripts corretamente.

## Objetivo do Teste

O objetivo deste teste é verificar se o idioma da página está adequadamente declarado.

## Cenário de Teste

O usuário será convidado a verificar se o idioma da página está adequadamente declarado, mesmo que o site seja exclusivamente em português. O foco do teste é saber se todo o site está na língua nativa do usuário.

### Descrição do Cenário:

O usuário é um falante nativo de português e está acostumado a navegar em sites em português. Ele não possui deficiências específicas relacionadas à língua.

#### Tarefa:

1. Verificar se o idioma da página está adequadamente declarado.

### Instruções:

- Verifique se o idioma da página principal está declarado em português.
- Confirme se o idioma declarado é o português.

## Avaliação do Desempenho do Usuário

O usuário conseguiu verificar facilmente que o idioma da página estava declarado como português, conforme esperado. Apesar da presença da palavra "Dashboard", o usuário compreendeu que se trata de um painel gerencial, mostrando uma boa adaptação ao contexto.

## Resultados do Teste

Em relação ao Critério de Sucesso 3.1.1 do WCAG 2.1, consideramos que a página passou no teste, pois o idioma está adequadamente declarado como português em todos os pontos da página. Mesmo com a presença da palavra "Dashboard", o usuário identificou perfeitamente o uso da mesma, mostrando uma boa compreensão do conteúdo.

# Teste 4: Critério de Sucesso 3.2.1 - Em Foco

Este teste tem como objetivo avaliar a conformidade do site com o Critério de Sucesso 3.2.1 do WCAG 2.1, que visa garantir que nenhuma mudança contextual desorientadora ocorra quando um elemento na interface recebe foco.

## Objetivo do Teste

O objetivo deste teste é verificar se o site mantém a compreensibilidade e previsibilidade da interface, conforme exigido pelo Critério de Sucesso 3.2.1 do WCAG 2.1.

## Cenário de Teste

O usuário foi convidado a realizar uma ação que resultará em um elemento na interface recebendo foco. Durante esse processo, devemos observar se ocorre alguma mudança contextual que possa desorientar o usuário, ou seja, se ao interagir, o contexto mude.

### Descrição do Cenário:

O usuário, um homem de 23 anos, está navegando na página inicial do site e deve observar o conteúdo da tabela, tanto a GPTW quanto Stibla.

#### Tarefa:

1. Localizar os botões "GPTW" e "STIBLA" no menu da tabela.
2. Clicar no botão para dar foco ao elemento e observar se ocorre alguma mudança contextual.

### Instruções:

- Verifique as mudanças na interface.
- Verifique se a mudança de foco para o elemento "Stibla" não causa uma mudança contextual inesperada na tela.
- Identifique se o conteúdo da GPTW e Stibla apresentam a mesma estrutura.

## Avaliação do Desempenho do Usuário

Após a conclusão da tarefa, o desempenho do usuário, em termos de compreensibilidade e previsibilidade da interface, foi exemplar, ele conseguiu diferenciar o contexto das duas pesquisas e identificar a estrutura do conteúdo.

## Resultados do Teste

Em relação ao Critério de Sucesso 3.2.1 do WCAG 2.1, a página passou no teste, pois o usuário conseguiu interagir com os elementos da interface sem experimentar mudanças contextuais inesperadas.

---

## Conclusão

Os testes de acessibilidade realizados demonstraram que o site atende aos Critérios de Sucesso da WCAG 2.1, proporcionando uma experiência de navegação acessível e inclusiva para os usuários.

## Melhorias Recomendadas para próximas versões do MVP

Com base nos resultados dos testes, recomendamos as seguintes melhorias para aprimorar ainda mais a acessibilidade e usabilidade do site:

1. **Melhorias na Legibilidade:** Aumentar o tamanho da fonte em certas áreas do site para melhorar a legibilidade, especialmente para usuários com deficiência visual.
2. **Aprimoramentos na Navegação:** Implementar a abertura de certos links em uma nova aba do navegador para melhorar a experiência de navegação.
3. **Suporte a Idiomas Adicionais:** Adicionar suporte a outros idiomas para atender a uma variedade mais ampla de usuários e contextos linguísticos.
4. **Indicação de Links Clicáveis:** Melhorar a indicação visual de links clicáveis, especialmente em gráficos e elementos interativos.
5. **Revisão de Design Responsivo:** Garantir que o site seja totalmente responsivo em diferentes dispositivos e tamanhos de tela para uma experiência consistente em todas as plataformas.

## Referências

1. [Testes de Usabilidade: Um Guia Completo](https://www.nngroup.com/articles/usability-testing-101/)
2. [WCAG - Guia de Consulta Rápida](https://guia-wcag.com/)
