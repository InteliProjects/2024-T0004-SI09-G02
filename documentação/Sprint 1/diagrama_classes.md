# Diagrama de classes

Um diagrama de classes é uma representação visual da estrutura e das relações entre as classes de um sistema. No diagrama de classes, as classes são representadas por retângulos, com seus atributos e métodos listados dentro deles. As relações entre as classes são mostradas por meio de linhas que conectam os retângulos, indicando associações, heranças, dependências ou outras interações.
<br>
<br>
O diagrama de classes é uma ferramenta poderosa para entender a estrutura do sistema, facilitando o desenvolvimento das classes e no design do software. A seguir, temos a primeira versão do diagrama de classes esperado para o desenvolvimento do dashboard
<br>
<br>
![Diagrama de Classes](https://github.com/Inteli-College/2024-T0004-SI09-G02/blob/develop/Assets/Diagrama_Classes.png?raw=true)
<br>
<br>
Nesse diagrama podemos observar a classe Usuário, ela será a abstração responsável pelos atributos e métodos comuns das classes Gerente e Administrador. Funções comuns que serão acessíveis a todos os usuários são as de verificar seu login com o email organizacional, acessar o dashboard e filtrar os resultados.
<br>
<br>
A classe Gerente corresponde ao gerente de cada setor, sendo assim importante que ele só tenha acesso ao relatório gerencial de seu escopo. Por outro lado, a classe Administrador contempla tanto o cargo de CEO, quanto do VP de RH, tornando-se crucial como regra de negócio a sua permissão de criar formulários, acessar diferentes relatórios e outros métodos administrativos do dashboard.