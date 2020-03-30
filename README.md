<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
</p>

# Reactathon GraphQL Workshop

Welcome! I'm really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Moon Highway Vote Playground](http://vote.moonhighway.com)
- [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [SWAPI: Star Wars API](http://graphql.org/swapi-graphql/)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### GraphQL Schema Definition Language

- [Schema Definition Language](https://slides.com/moonhighway/schema-definition-language/)
- [Schema Language Cheat Sheet](https://github.com/sogko/graphql-schema-language-cheat-sheet)
- [Modular Schema](https://github.com/eveporcello/schema-workshop/tree/master/06-extras/modularizing-a-schema/finished)
- [Lab Instructions](https://slides.com/moonhighway/schema-lab/)
- [Possible Lab Solutions](https://github.com/graphqlworkshop/schema-activity)

### Building a GraphQL API

- [Exercise Start Files](https://github.com/graphqlworkshop/snowtooth-api)
- [Lab Instructions](https://slides.com/moonhighway/server-lab/)
- [Sample Data](https://bit.ly/2VF5zJU)
- [Starting Schemas](https://github.com/graphqlworkshop/schema-activity)
- [Simple Strava Sample](https://github.com/eveporcello/simple-strava-sample/blob/master/index.js)
- [REST Data Sources](https://github.com/MoonHighway/countries-datasources)

### Apollo Client

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### React & Apollo

- [React Overview](https://slides.com/moonhighway/react-overview)
- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Lab Instructions](https://slides.com/moonhighway/client-lab/)

## Apollo Tooling 🛠

**Slides**

- [TypeScript & GraphQL](https://slides.com/moonhighway/typescript-graphql)

**Samples**

- [TypeScript & Apollo CLI - Finished Project + Instructions](https://github.com/graphqlworkshop/snowtooth-typescript)
- [Snowtooth API](https://snowtooth.moonhighway.com)
- [Lift Manager Sample Client Code](https://github.com/eveporcello/lift-manager/blob/master/src/index.js)
- [Lift Manager Website](https://lift-manager.netlify.com)
- [Big Basin Sample Client Code](https://github.com/eveporcello/big-basin/blob/master/src/index.js)
- [Big Basin Website](https://big-basin.netlify.com)
- [Snowtooth Project Repo](https://github.com/moonhighway/snowtooth)
- [Client Side Mocking - CodeSandbox](https://codesandbox.io/s/client-mocking-epqmp)
- [Apollo REST Data Sources](https://github.com/MoonHighway/countries-datasources)
- [Batch Link](https://github.com/eveporcello/batching)

## Next Steps

- [Fullstack Error Handling with GraphQL](https://blog.apollographql.com/full-stack-error-handling-with-graphql-apollo-5c12da407210)
- [Apollo Federation](https://egghead.io/playlists/getting-started-with-apollo-federation-60ad0165)

## Evaluation!

* [Evaluation](https://docs.google.com/forms/d/e/1FAIpQLSf-EDajyFkrKvvF-rZfqSLsSsSgM7BCw5Wh_cb9mWPqdNVbEQ/viewform?usp=sf_link)
