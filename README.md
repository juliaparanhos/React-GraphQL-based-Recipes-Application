# React/GraphQL based Recipes Application

An application where people can find authentic Asia recipes. 

Stack: React + GraphQL (Apollo Client) + Express + Mongoose.

## Todo List:

| Function     | Description   | Status  | Tech Used  |
| -------------|:--------------| ------- |:----------- |
| 1. User signup |  | Finished | bcrypt (hash password), react-router-dom (routing), react-apollo (Mutation component) |
| 2. User signin and authentication, redirect upon signin/signup || Finished | Local Storage, JWT, graphql-express middleware, HOC (Higher-Order Components, withSession.js and withRouter from react-router-dom) |
| 3. Navigation, dynamic navbar based on whether user logged in, user signout || Finished | session, ApolloConsumer from react-apollo, localStorage |
| 4. Create and display recipes || Finished | react-apollo (Mutation component), apollo-cache-inmemory (InMemoryCache, cache object), Optimistic UI. |
| 5. Search recipe(s) || Finished | react-apollo (ApolloConsumer component) |
| 6. User profile || Finished | Route protection: add withAuth()() to Profile and AddRecipe route |
| 7. Delete user recipes || Finished | Optimistic UI |
| 8. Like/unlike recipe || In progress ||
| 0. Polish UI apperance | | | React Pose Animation, Skeleton CSS |