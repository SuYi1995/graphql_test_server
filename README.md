# graphql-test-server

## clone the repository

```
git clone git@github.com:SuYi1995/graphql_test_server.git
```

##  Run the GIN server

```
go serve server.go
```

##  Make changes to schema by editing the file `schema.graphqls`

After making changes run the below command to auto generate the `models` and `resolvers`. We need to implement the resolvers.

```
gqlgen generate
```
