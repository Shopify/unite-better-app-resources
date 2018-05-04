# Resources for Architecture of a Shopify App Unite Talk

## Polaris
You can view the source code for [Polaris v2 on Github](https://github.com/Shopify/polaris), and make sure to visit our expanded [Styleguide](https://polaris.shopify.com).

## React
* [react-html](https://github.com/Shopify/quilt/tree/master/packages/react-html): Provides an HTML React component for use in server-side rendering.
* [react-serialize](https://github.com/Shopify/quilt/tree/master/packages/react-serialize): Provides a component and matching utilities for safely serializing data between server and client. 
* [react-shopify-app-route-propagator](https://github.com/Shopify/quilt/tree/master/packages/react-shopify-app-route-propagator): Provides a React component that automatically matches the path of a React single page embedded app to the admin frame.

## React Testing
* [enzyme-utilities](https://github.com/Shopify/quilt/tree/master/packages/enzyme-utilities): Additional utilities for testing React components with Enzyme.
* [jest-dom-mocks](https://github.com/Shopify/quilt/tree/master/packages/jest-dom-mocks): Mocks of common DOM globals for use with Jest.
* [jest-mock-apollo](https://github.com/Shopify/quilt/tree/master/packages/jest-mock-apollo): A mock version of Apollo that allows specifying per-operation GraphQL fixtures.
* [jest-mock-router](https://github.com/Shopify/quilt/tree/master/packages/jest-mock-router): A mock version of React Router 3.

## GraphQL
* [graphql-typescript-definitions](https://github.com/Shopify/graphql-tools-web/tree/master/packages/graphql-typescript-definitions): A command line tool to generate TypeScript definition files (`.d.ts`) from static GraphQL files (`.graphql`).
* [graphql-validate-fixtures](https://github.com/Shopify/graphql-tools-web/tree/master/packages/graphql-validate-fixtures): A command line tool to compare the types from JSON fixtures to their associated static GraphQL operations.

## Koa
* [koa-shopify-auth](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-auth): Provides a series of Koa middlewares for authenticating with Shopify’s REST and GraphQL APIs.
* [koa-shopify-graphql-proxy](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-graphql-proxy): A Koa middleware to proxy GraphQL requests to Shopify.
* [jest-koa-mocks](https://github.com/Shopify/quilt/tree/master/packages/jest-koa-mocks): A mock version of Koa’s context for use with Jest.

## Other
* [with-env](https://github.com/Shopify/quilt/tree/master/packages/with-env): Safe switching of `process.env.NODE_ENV`.
