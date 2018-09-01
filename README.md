# docker-nodejs-graphql
Implement Graphql with Node.js in Docker.

## Test GraphQL

```
curl -X POST \
-H "Content-Type: application/json" \
-d '{"query": "{ hello }"}' \
http://localhost:4000/graphql
```