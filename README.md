# graphqlgenerator
Generate a spring boot application from graphQL schema

input : a schema graphQL (a.graphqls file)of GraphQL
* Transformation 1: Generate java class (the "model") from type from graphql.
* Transformation 2: Generate java spring entities, repository , mapping orm from mmodel
* Transformation 3: Generate spring graphQl Endpoint from Query and Mutation of graphQl

In fact, the model is useless. Its goal is only to generate the Spring application. 

# test
* http://localhost:8081/api2
* http://localhost:8081/graphiql interface graphique graphQL
* http://localhost:8081/graphql
* http://localhost:8080/welcome diverses infos
* http://localhost:8080/v2/api-docs swagger endpoint
* http://localhost:8080/swagger-ui/index.html swagger ui

#Documentation


* [GraphQL Java Tool readme](https://github.com/graphql-java-kickstart/graphql-java-tools/blob/master/README.md)
* [GraphQL Java Tool Documentation](https://www.graphql-java-kickstart.com/tools/)
* [GraphQL Tools js](https://www.graphql-tools.com/docs/introduction/)
* [Netflix GraphQL for Spring](https://netflixtechblog.com/open-sourcing-the-netflix-domain-graph-service-framework-graphql-for-spring-boot-92b9dcecda