# Octopart API

Automatically generate code to consume Octopart API.

## About

This project will generate the boilerplate Java code to query the Octopart API using GraphQL.

## Build

Use the following commands to build the project:
```bash
# build JAR
mvn package

# install to local repository
mvn install
```

## Dependencies

The `graphql-maven-plugin` is used to generate Java code from a GraphQL schema file provided by Octopart.

The `graphql-java-extended-scalars` dependency is needed for both the `JSON` and `DateTime` scalars used in the provided schema.
