1. setting

- yarn init

- yarn add ts-node typescript tslint-config-prettier --dev
- add files for typescript (tsconfig.json, tslint.json)

- create files app.ts , index.ts
- yarn add nodemon graphql-yoga
- yarn add middleware (cors, helmet, dotenv, morgan)
- modify package.json dev script => nodemon -e ts, graphql ...

- create api folder => graphql && resolver
- yarn add graphql-tools merge-graphql-schemas babel-runtime
- create filis schema.ts
- modify app.ts => schema

- yarn add graphql-to-typescript gql-merge --dev
- modify package.json "pretypes": "gql-merge --out-file ./src/schema.graphql ./src/api/\*_/_.graphql",
- modify package.json "types": "graphql-to-typescript ./src/schema.graphql ./src/types/graph.d.ts"

- github/typeorm/typeorm
- yarn add typeorm pg
