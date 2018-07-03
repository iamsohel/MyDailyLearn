#### What is GraphQL & Benefits?

- New `API` standard that was invented & open-sourced by Facebook
- Provides a more efficient, powerful and flexible alternatives to `REST`.
- Enables **declaratative data fetching**.
- Exposes **single endpoint** and responds to `queries`.
- Uses **strong type** system to define capabilities of an API
- Schema serves as contract between client and server.
- Frontend and Backend teams can work completely independent from each other.
- GraphQL is great for frontend developers as data fetching complexity can be pushed to the server-side (mean: client does not care where data is coming from)

#### A more efficient Alternative to REST

- Increased mobile usage creates need for efficient data loading.
- Variety of different frontend frameworks and platforms on the client-side.
- Fast development speed & expectation for rapid feature development

#### GraphQL is **not** only for React developers

- Facebook uses GraphQL since 2012 in their native mobile apps.
- First time presented publicly at React.js Conf 2015
- GraphQL can be used with any programming language and framework.
- Other companies were working on similar ideas
- `Netflix` open-sourced their solution `Falcor`.

#### GraphQL is the better REST

- GraphQl was developed to cope with the **need for more flexibility and efficiency** in client-server communication.
- Overfetching: graphQL don't downloading unnecessary data
- Underfetching: graphQL gives all necessary data in one API endpoint unlike REST is underfetching (an endpoing doesn't return enough of the right information; need to send multiple requests: n+1-requests problem).

#### Core Concepts
##### The Schema Definition Language (SDL)
- 3 kinds of **mutations**
  - `creating` new data
  - `updating` existing data
  - `deleting` existing data

#### Architecture Use Cases
- GraphQL server with a connected database
- GraphQL server to integrate existing system
- A hybrid approach with a connected database and integration of existing system

##### Resolver functions
- GraphQL queries/mutations consist of set of fields
- GraphQL server has one resolver function per field
- The purpose of each resolver is to retrieve the data for its corresponding field

