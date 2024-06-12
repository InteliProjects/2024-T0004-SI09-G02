# Diagrama de Caso de Uso do Sistema de Controle de Dados Gerenciais da Volkswagen

1. [Introdução](#c1)
2. [Estrutura do Diagrama de Caso de Uso](#c2)
3. [Atores](#c3)
4. [Casos de Uso](#c4)
5. [Relacionamentos entre os Casos de Uso](#c5)
6. [Conclusão](#c6)
<br>

![diagrama](https://github.com/Inteli-College/2024-T0004-SI09-G02/blob/develop/Assets/Diagrama_Caso-de-Uso.jpeg)

## <a name="c1">Introdução</a>

Este documento descreve o diagrama de caso de uso do projeto em parceria com a Volkswagen, delineando os atores envolvidos, os principais casos de uso e seus relacionamentos.

Na Unified Modeling Language (UML, ou Linguagem de Modelagem Unificada em português), os sistemas são apresentados em diferentes níveis de detalhes para mostrar uma perspectiva específica no design do sistema. Os diagramas de caso de uso são considerados diagramas UML.

Os diagramas garantem o desenvolvimento de sistemas corretos e eficientes que atenderão adequadamente aos seus objetivos ao capturar os requisitos e expectativas do ponto de vista do usuário, além de permitirem a visualização das interações que um usuário ou cliente pode ter com um sistema.

## <a name="c2">Estrutura do Diagrama de Caso de Uso</a>

<img src="https://github.com/Inteli-College/2024-T0004-SI09-G02/blob/develop/Assets/Diagrama_Caso-de-uso-estrutura.png" alt="estrutura diagrama" width="300">


O diagrama de caso de uso é composto por três elementos principais: atores, casos de uso e relacionamentos. 

- **Atores**: um ator é qualquer pessoa que executa uma ação usando seu sistema. Atores ou usuários podem ser uma pessoa, uma organização ou um sistema externo. Os atores são representados por bonecos em um diagrama de caso de uso.

- **Sistema**: o escopo do sistema abrange uma sequência de ações e interações entre usuários e o sistema. Para representar o limite do sistema, as caixas de limite do sistema são usadas para indicar que um caso de uso está dentro do escopo do sistema.

- **Casos de uso**: os casos de uso são os diferentes usos ou aplicações que seu sistema pode oferecer aos usuários. Formas ovais horizontais são usadas para simbolizar casos de uso, enquanto linhas são desenhadas para conectar o usuário ao caso de uso.

- **Relacionamentos**: relacionamentos entre o negócio e os indivíduos.

Bonecos palito representam os atores no processo, e a participação do ator no sistema é modelada com uma linha entre o ator e o caso de uso. Para representar o limite do sistema, foi desenhada uma caixa em torno do próprio caso de uso. Os casos de uso são representados por estruturas circulares, e os relacionamentos entre os casos de uso são representados por linhas, com possibilidade de se estruturarem entre "incluir" e "estender".

A relação de "incluir" é usada quando todo caso de uso base necessita de outro processo, assim tendo um caso de uso incluído. A relação de "estender" é usada quando se cumprem certos requisitos (então é condicional).

## <a name="c3">Atores</a>

Os atores são as entidades que interagem com o sistema. Eles podem ser pessoas, outros sistemas ou dispositivos. No caso do projeto, os atores são:

- CEO da Volks (Vermelho);
- VP de RH da Volks (Roxo);
- Líderes Gerenciais de diferentes áreas da Volks (Azul).

### Nota
- É importante destacar que as conexões dos atores com os casos de uso podem parecer um pouco confusas à primeira vista. No entanto, para manter as boas práticas no desenvolvimento do diagrama de caso de uso, foi necessário posicionar todos os atores no lado esquerdo do diagrama. Isso se deve ao fato de que todos os atores são usuários diretos do sistema. Seguindo essa convenção, os atores que reagem às ações dos usuários (como sistemas externos ou dispositivos) são tradicionalmente posicionados no lado direito do diagrama.

## <a name="c4">Casos de Uso</a>

1. **Login**
    - Este caso de uso representa o processo pelo qual os usuários se autenticam no sistema. Os usuários serão solicitados a fornecer suas credenciais de login, que geralmente consistem em um nome de usuário e uma senha. O sistema verifica essas credenciais para autenticar o usuário e conceder acesso ao sistema.
    - Fluxo Principal:
        1. O usuário acessa a página de login do sistema.
        2. O usuário fornece seu nome de usuário e senha.
        3. O sistema verifica as credenciais do usuário.
        4. Se as credenciais forem válidas, o usuário é autenticado e redirecionado para a página principal do sistema.
    - Fluxo Alternativo:
        1. Se as credenciais do usuário forem inválidas, o sistema exibe uma mensagem de erro e solicita que o usuário forneça credenciais válidas.
    - Pré-condições: Nenhuma.
    - Pós-condições: O usuário está autenticado no sistema e pode acessar as funcionalidades disponíveis.

2. **Acessar Dash**
    - Este caso de uso representa o processo pelo qual os usuários acessam o painel principal do sistema, também conhecido como "dashboard". O painel pode conter informações resumidas, estatísticas, gráficos ou outras visualizações de dados relevantes para os usuários.
    - Fluxo Principal:
        1. O usuário autenticado acessa a página principal do sistema.
        2. O sistema exibe o painel principal (dashboard).
    - Fluxo Alternativo:
        - O usuário autenticado acessa o sistema.
        - O sistema oferece a opção de filtrar os dados do painel por plantas específicas.
        - O usuário seleciona as plantas desejadas e aplica o filtro.
        - O sistema atualiza o painel para exibir os dados filtrados.
    - Pré-condições: O usuário está autenticado no sistema.
    - Pós-condições: O usuário pode visualizar o painel principal do sistema e pode visualizar informações relevantes.

3. **Ver Painéis Comparativos**
    - Este caso de uso permite aos usuários comparar dados ou métricas de diferentes áreas ou unidades dentro da organização. Os usuários podem visualizar painéis que apresentam informações comparativas para análise e tomada de decisões.
    - Fluxo Principal:
        1. O usuário acessa a página de painéis comparativos.
        2. O sistema exibe os painéis comparativos de todas as áreas da organização.
        3. O usuário seleciona os painéis de interesse para visualização.
        4. O sistema exibe os painéis selecionados.
    - Pré-condições: O usuário está autenticado no sistema.
    - Pós-condições: O usuário pode visualizar os painéis comparativos selecionados.

4. **Ver Relatório Completo**
    - Este caso de uso permite aos usuários acessar um relatório detalhado que inclui informações abrangentes sobre diversos aspectos da organização, como críticas aos benefícios, remuneração, promoção, notas das áreas comparadas com a média da empresa, e outras informações relevantes obtidas de pesquisas e formulários.
    - Fluxo Principal:
        1. O usuário autenticado acessa o sistema.
        1. O sistema oferece a opção de visualizar o relatório completo.
        1. O usuário seleciona a opção para visualizar o relatório completo.
        1. O sistema exibe o relatório completo com todas as informações detalhadas.
    - Pré-condições: O usuário está autenticado no sistema.
    - Pós-condições: O usuário pode visualizar o relatório completo com todas as informações detalhadas.

5. **Visualizar Relatório Gerencial**
    - Este caso de uso permite aos usuários acessar um relatório específico voltado para análise gerencial. O relatório pode conter informações sobre críticas aos benefícios e/ou promoções da área, notas específicas da área comparadas com a média da empresa, e outros dados relevantes relacionados ao engajamento da pesquisa dentro da área.
    - Fluxo Principal:
        1. O usuário autenticado acessa o sistema.
        2. O sistema oferece a opção de visualizar o relatório gerencial.
        3. O usuário seleciona a opção para visualizar o relatório gerencial.
        4. O sistema exibe o relatório gerencial com as informações específicas da área.
    - Pré-condições: O usuário está autenticado no sistema.
    - Pós-condições: O usuário pode visualizar o relatório gerencial com todas as informações relevantes para análise gerencial.

## <a name="c5">Relacionamentos entre os Casos de Uso</a>

1. **Login**
    - Incluir: Verificar LOGIN via email
    - Estender: Exibir erro de login
2. **Acessar Dash**
    - Incluir: Alimentar o dash
    - Incluir: Visualizar perguntas dos forms (NOTA: 5 perguntas com maiores notas e 5 perguntas com menores notas de cada pesquisa)
    - Estender: Filtrar por plantas
3. **Ver Painéis Comparativos**
    - Extension Points:
        - "De todas as áreas" para os CEO
        - "Da área respectiva" para os líderes gerenciais
4. **Ver Relatório Completo**
    - Incluir: Ver Críticas aos benefícios, remuneração, promoção
    - Incluir: Ver Notas das áreas X média da empresa
    - Incluir: Relacionar forms GPTW x ESTIBA
    - Incluir: Ver engajamento da pesquisa
5. **Visualizar Relatório Gerencial**
    - Incluir: Ver críticas aos benefícios e/ou promoções da área
    - Incluir: Ver Notas da área X média da empresa
    - Incluir: Relacionar forms da área GPTW x ESTIBA
    - Incluir: Ver engajamento da pesquisa da área

### Notas Importantes

- Todos os atores possuem ligação com os casos de uso Login, Acessar Dash, Ver Painéis Comparativos e Visualizar Relatório Gerencial.
- Os líderes gerenciais não possuem acesso para visualizar o Relatório Completo.

## <a name="c6">Conclusão</a>

O README.md fornecido apresenta uma visão abrangente do diagrama de caso de uso do projeto, delineando seus atores, casos de uso e relacionamentos. Através deste documento, os stakeholders e membros da equipe têm uma compreensão clara das funcionalidades principais do sistema e como eles interagem entre si.

O diagrama de caso de uso é uma ferramenta fundamental no processo de desenvolvimento de software, pois permite uma representação visual das interações entre os usuários e o sistema. Ao capturar os requisitos e expectativas do ponto de vista do usuário, o diagrama de caso de uso facilita a comunicação e colaboração entre os membros da equipe de desenvolvimento, garantindo que o sistema atenda adequadamente às necessidades dos usuários finais.

Além disso, o diagrama de caso de uso serve como uma referência central durante todo o ciclo de vida do projeto, desde a fase de concepção até a implementação e teste. Ele ajuda a garantir que todas as funcionalidades necessárias sejam identificadas e implementadas corretamente, contribuindo para o desenvolvimento de um sistema robusto e eficiente.

Em resumo, o diagrama de caso de uso desempenha um papel crucial no desenvolvimento de software, fornecendo uma representação clara e concisa das interações entre os usuários e o sistema. Este README.md serve como um guia útil para entender o diagrama de caso de uso do projeto, destacando seus elementos principais e enfatizando a importância desta ferramenta no desenvolvimento de software de qualidade.