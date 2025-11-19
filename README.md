* O cenário escolhido pelo nosso grupo foi Microinvestimentos Colaborativos. 

* Aqui está as instruções de execução do nosso programa: 1. Instalações necessárias:

Instale antes de executar:
JDK 17 ou superior
Visual Studio Code
Extensão: Extension Pack for Java
PostgreSQL + pgAdmin
Driver JDBC do PostgreSQL (arquivo .jar)

2. Criar o banco de dados

Abra o pgAdmin e execute o arquivo:
banco/microinvestimentos.sql
Esse arquivo cria:
Banco: microinvestimentos
Tabela: investimentos

3. Configurar o JDBC no projeto

Coloque o arquivo do driver dentro da pasta:
codigo/lib/
Depois:
Clique com o botão direito no .jar
Escolha: Add to Build Path

4. Configurar a conexão com o PostgreSQL

Abra:
src/util/ConnectionFactory.java
E altere a linha da senha:
PASSWORD = "sua_senha_do_postgres";

5. Executar o sistema

Abra o arquivo:
src/view/Main.java
Clique em Run (botão ▶ do VS Code)
O menu vai aparecer no console e você poderá:
cadastrar investimento
listar investimentos
atualizar investimento
deletar investimento

* As tecnologias que nós utilizamos foram Java, JDBC, Postgresql, driver JDBC PostgreSQL, vs code, extension pack for java, pgAdmin, sql e programação orientada a objetos.

* Jonathan Soares, Amabiel Júnior, Flávio Lucas e Alexandre Araujo
