# Testing

https://teams.microsoft.com/l/meetup-join/19:meeting_NGMyNDc0ZDQtYzhlMy00MzI4LThiYzEtYjdmMmQ1YWRlMTNi@thread.v2/0?context=%7B%22Tid%22:%2221f25632-7ab8-4714-8918-0a227d8809b3%22,%22Oid%22:%22fdefd84a-3cd6-4a37-b34b-3fb87e2f7d4e%22%7D





graphql-java Blog & Site:

GraphQL Java Overview (https://github.com/graphql-java/graphql-java)
GraphQL Java is the Java (server) implementation for GraphQL. There are several repositories in the GraphQL Java Github org. The most important one is the GraphQL Java Engine which is the basis for everything else.

GraphQL Java Engine itself is only concerned with executing queries. It doesn’t deal with any HTTP or JSON related topics. For these aspects, we will use the GraphQL Java Spring Boot adapter which takes care of exposing our API via Spring Boot over HTTP.

GraphQL is getting popular as an alternative for REST API. Some of the advantages of GraphQL over REST API.
REST API has many endpoints and every end point is specific to some resource but in GraphQL it has only one endpoint.
No versioning in GraphQL unlike REST , In GraphQL clients can control the structure of the response.
Some of the basic validations like type checking and null checks are handled by GraphQL server itself , so developers no need to worry about.
GraphQL server caches the often-requested data, thereby minimising the processing time and effort.
The GraphQL team has developed a query editor called GraphQL intended for development purposes. It is intelligent and comes in handy to test our GraphQL requests. We can test most of the features of the GraphQL server using GraphiQL.
  
The main steps of creating a GraphQL Java server are:
Defining a GraphQL Schema.
Deciding on how the actual data for a query is fetched.

GraphQL-Java itself started supporting for spring boot (https://github.com/graphql-java/graphql-java-spring): 
The core project doesn’t deal with any form of HTTP or JSON specific things and has on purpose basically no dependencies at all. This will not change, but we recognize the need for having an easy way to get a full service up and running. This is why we are currently working on first class Spring (Boot) support.it will provide an easy way to integrate GraphQL Java in a Spring (Boot) application without adding any abstraction on top of GraphQL Java.
https://github.com/graphql-java/graphql-java-spring

There are four different artifacts: (all with group id com.graphql-java)
graphql-java-spring-webflux
graphql-java-spring-boot-starter-webflux
graphql-java-spring-webmvc
graphql-java-spring-boot-starter-webmvc

https://www.graphql-java.com/blog/
https://github.com/graphql-java/graphql-java
https://github.com/graphql-java/graphql-java-spring  

Example implemented:
DemoGraphQl: https://github.com/eh3rrera/graphql-java-spring-boot-example  

Tutorials:
https://www.viralpatel.net/graphql-spring-boot-tutorial/

There are third party libraries on top of it, like kickstart is one of the libraries, so they moved it to another github as below mentioned.
https://www.graphql-java.com/blog/moving-projects/
https://github.com/graphql-java-kickstart/
com.graphql-java-kickstart:graphql-spring-boot-starter:12.0.0
com.graphql-java-kickstart:graphiql-spring-boot-starter:12.0.0
















