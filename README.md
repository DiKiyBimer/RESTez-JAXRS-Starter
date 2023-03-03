# DIKIYBIMER - REST EASY JAX-RS ARCH (Quarkus)
## dev mode

```shell script
./mvnw compile quarkus:dev
DEV UI: http://localhost:8080/q/dev/.
```
## Packaging and running the application
```shell script
./mvnw package
```
`quarkus-run.jar` in the `target/quarkus-app/`
IT IS NOT an _über-jar_ as the dependencies are copied into the `target/quarkus-app/lib/` directory.
runnable using `java -jar target/quarkus-app/quarkus-run.jar`
If you want to build an _über-jar_, execute the following command:
```shell script
./mvnw package -Dquarkus.package.type=uber-jar
```
The application, packaged as an _über-jar_, is now runnable using `java -jar target/*-runner.jar`.
## Creating a native executable
You can create a native executable using: 
```shell script
./mvnw package -Pnative
```
if don't have GraalVM installed, run the native executable build in a container using: 
```shell script
./mvnw package -Pnative -Dquarkus.native.container-build=true
```
native executable with: `./target/restez-jaxrs-1.0.0-runner`
## Related Guides
- Kogito Add-On Persistence PostgreSQL ([guide](https://quarkus.io/guides/kogito)): Kogito Add-On support for persistence on PostgreSQL
- Kogito Addons Quarkus Data Index PostgreSQL ([guide](https://quarkus.io/guides/kogito)): Kogito Data Index PostgreSQL Add-On
- Hibernate ORM ([guide](https://quarkus.io/guides/hibernate-orm)): Define your persistent model with Hibernate ORM and JPA
- WebSockets Client ([guide](https://quarkus.io/guides/websockets)): Client for WebSocket communication channel
- RESTEasy Reactive ([guide](https://quarkus.io/guides/resteasy-reactive)): A JAX-RS implementation utilizing build time processing and Vert.x. This extension is not compatible with the quarkus-resteasy extension, or any of the extensions that depend on it.
-  ♣♠♦♥ YAML ♣♠♦♥ Configuration ([guide](https://quarkus.io/guides/config#yaml)): Use  ♣♠♦♥ YAML ♣♠♦♥ to configure application
- Hibernate ORM with Panache ([guide](https://quarkus.io/guides/hibernate-orm-panache)): Simplify your persistence code for Hibernate ORM via the active record or the repository pattern
- Reactive PostgreSQL client ([guide](https://quarkus.io/guides/reactive-sql-clients)): Connect to the PostgreSQL database using the reactive pattern
- JDBC Driver - PostgreSQL ([guide](https://quarkus.io/guides/datasource)): Connect to the PostgreSQL database via JDBC
## ♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ 
```shell script
♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ 
```
`♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ YAML ♣♠♦♥ `
`♣♠♦♥ YAML ♣♠♦♥` `♣♠♦♥ YAML ♣♠♦♥` 
# `♣♠♦♥ YAML ♣♠♦♥`

Configure your application with  ♣♠♦♥ YAML ♣♠♦♥
[Related guide section...](https://quarkus.io/guides/config-reference#configuration-examples)
configuration is located in `src/main/resources/application.yml`. (this is ♣♠♦♥ YAML ♣♠♦♥ XD) 

### Hibernate ORM
Create your first JPA entity
[Related guide section...](https://quarkus.io/guides/hibernate-orm)
[Related Hibernate with Panache section...](https://quarkus.io/guides/hibernate-orm-panache)
