# spring-boot-api-rest-alura
## Projeto de estudo, focado em criar uma API REST com as melhores práticas ministrado pelo professor Rodrigo Ferreira.
<img src="https://img.shields.io/static/v1?label=Spring&message=Study&color=6DB33F&style=for-the-badge&logo=SpringBoot">


Tabela de conteúdos

<!--ts-->
   * [Sobre](#Sobre)
   * [Features](#Sobre)
   * [Tecnologias](#tecnologias)
   * [Autor](#Sobre)
<!--te-->

---

## 💻 Sobre

Esse projeto tem o objetivo de prover um upgrade nas habilidades do autor deste README.
O foco do projeto é desenvolver uma API REST com o uso de módulos spring e o auxílio de outras ferramentas como Postman e banco de dados H2.

---
### Features

Introdução ao Spring Boot
- [x] Construção do projeto com spring initializr
- [x] uso da anotação @Controller para criação do primeiro Controller
- [x] uso da anotação @RequestMapping para mapear as URLs
Publicando Endpoints
- [x] Uso da anotação @ResponseBody para o Controller não encaminhar a requisição à uma página JSP ou Thymeleaf
- [x] Uso da anotação @RestController para não ter que repetir a anotação @ResponseBody em todo método da API 
- [x] Uso da ferramente Devtools para não precisar reiniciar manualmente o servidor a cada alteração realizada no código 
- [x] Uso do padrão DTO(Data Transfer Object) como boa prática para retornar entidades JPA nos métodos dos controllers 
Usando Spring Data
- [x] Uso do módulo Spring Boot Data JPA, que utiliza o Hibernate como padrão para sua implementação
- [x] Uso do Banco de Dados H2 e sua configuração no arquivo src/main/resources/application.properties
- [X] Uso das anotações @Entity, @Id, @GeneratedValue, @OneToMany e @Enumerated para mapear as classes de domínio da aplicação como entidade JPA
- [x] Criação do arquivo src/main/resources/data.sql para que o Spring Boot popule automaticamente o banco de dados
- [x] Uso de nomenclatura de métodos Spring como, por exemplo, findByCursoNome para criar consultas que filtram por atributos da entidade
- [x] Uso da anotação @Query para criar consultas manualmente com JPQL
Trabalhando com POST
- [x] Uso da anotação @RequestMapping em cima da classe controller para evitar repetir a URL base em todos os métodos
- [x] Uso anotação @PostMapping para mapear as requisições do tipo POST
- [ ] Uso do padrão DTO(Data Transfer Object) como boa prática para eceber dados enviados no corpo da requisição
Trabalhando com Bean Validation
- [x] Validação do pedido
- [x] Mensagens de erro
- [x] Objetivo da anotação @Valid
Trabalhando com templates
- [x] Finalizando o topo
- [x] Criando template
ZFormatação e finalização
- [x] Modelando o status
- [x] Rota do status
- [x] Formatação de número e data


---

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [JAVA11](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html)
- [Spring initializr](https://start.spring.io/)
- [Spring boot](https://spring.io/projects/spring-boot)
- [Spring Web](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html)
- [Spring data jpa](https://spring.io/projects/spring-data-jpa)
- [Spring security](https://spring.io/projects/spring-security)
- [Spring validation](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/validation.html)
- [Spring devtools](https://docs.spring.io/spring-boot/docs/1.5.16.RELEASE/reference/html/using-boot-devtools.html)
- [Thymeleaf](https://www.thymeleaf.org/)
- [Intelij IDEA](https://www.jetbrains.com/pt-br/idea/)
- [java-Dotenv](https://github.com/cdimascio/java-dotenv)

---

### Autor
[Leonardo da Silva Costa](https://www.linkedin.com/in/leonardo-costa-b49b8062/)

Em busca do próximo nível 🚀 - Never stop learning. 🧑‍🎓


<h4> 
	Finalizado. 👌
</h4>

