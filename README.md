```shell
npm i @nestjs/graphql @nestjs/apollo graphql apollo-server-express
```

# GraphQL

### Query

### Mutation

n REST, any request might end up causing some side-effects on the server, but by convention it's suggested that one doesn't use GET requests to modify data. GraphQL is similar - technically any query could be implemented to cause a data write. However, it's useful to establish a convention that any operations that cause writes should be sent explicitly via a mutation.