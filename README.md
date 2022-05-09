<h1>Conhecendo o Projeto Spring Data JPA na Prática </h1>
<p> Sejam bem-vindos ao projeto de LAB <strong>Conhecendo o Projeto Spring Data JPA na Prática</strong> oferecido gratuitamente pela plataforma de cursos online <a href="https://dio.me/"><strong> Digital Innovation One</strong></a>.<br>

<h2>🎯 Objetivo do Projeto</h2>
<p>Ao final deste projeto, o Dev irá conhecer os principais conceitos de mapeamento objeto relacional (ORM) usando o <strong>Spring Data JPA</strong>. Para isso, uma <strong>API RESTful</strong> será desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.</p>

<h2>
🛑 Aplicar melhorias
</h2>

- [x] Usar Docker Compose

- [x] Desenvolver o CRUD completo (Update e Delete)

<h2> 🚦 Guia </h2>

<ol>
    <li> Apresentação do Projeto Base </li>
    <li> Configuração do banco de dados (SGBD <em>PostgreSQL</em>)</li>
    <li> Aplicando as <em>annotations</em></li>
    <li>Execução do fluxo back-end: <em>Controller - Service - Repository</em></li>
    <li>Validação - <em>Hibernate Validator</em> </li>
    <li>Consultas Avançadas - <em>Derived Query - Native Query</em></li>
    <li>Aplicar Update e Delete no Crud - Como Desafio Final</li>
</ol>

<h2>🛠 Tecnologias Utilizadas</h2>

<ul>
    <li><strong>IDE IntelliJ</strong></li>
    <li><strong>Java 11</strong></li>
    <li><strong>Maven</strong></li>
    <li><strong>Spring Web</strong></li>
    <li><strong>Spring Data JPA</strong></li>
    <li><strong>PostgreSQL Driver</strong></li>
    <li><strong>Hibernate Validator</strong></li>
    <li><strong>Lombok</strong></li>
    <li><strong>Postman</strong></li>
    <li><strong>Docker</strong></li>
</ul>


<h2><a href="https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/"> Anotações de Mapeamento </a></h2>

<strong>@Entity</strong>
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.

<strong>@Table</strong>
Usada para especificar a tabela principal da entidade atualmente anotada.

<strong>@Id</strong>
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.

<strong>@GeneratedValue</strong>
Especifica que o valor do identificador de entidade é gerado automaticamente.

<strong>@Column</strong>
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.

<strong>@JoinColumn</strong>
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.

<strong>@OneToMany</strong>
Usada para especificar um relacionamento de banco de dados um-para-muitos.

<strong>@OneToOne</strong>
Usada para especificar um relacionamento de banco de dados um-para-um.

<strong>@ManyToOne</strong>
Usada para especificar um relacionamento de banco de dados muitos-para-um.

<strong>cascade</strong>
Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.

<strong>mappedBy</strong>
Indica qual é o lado inverso ou não dominante da relação.

<h2>🔗 Links Úteis</h2>
<ul>
    <li><a href="https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.1&packaging=jar&jvmVersion=11&groupId=me.dio.academia&artifactId=academia-digital&name=academia-digital&description=Tutorial%20API%20RESTful%20modelando%20sistema%20de%20academia%20de%20gin%C3%A1stica&packageName=me.dio.academia.digital&dependencies=web,data-jpa,postgresql,validation,lombok">Spring Initializr</a></li>
    <li><a href="https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html">Common application properties</a></li>
    <li><a href="https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories">Spring Data JPA - Reference Documentation</a></li>
</ul>


<h2> 🤝 Contribuindo </h2>

Como melhoria rodei o projeto usando o Docker com o seguinte comando:
<ul>
    <li><strong>Para inicializar nossa aplicação:</strong></li>
    <li><strong>docker run -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres</strong></li>
</ul>
<ul>
    <li><strong>Assim que terminar de utilizar os contêiners o comando:</strong></li> 
    <li><strong>docker stop id_conteiner</strong></li>
</ul>



