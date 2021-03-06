# React-GraphQL based Recipes Application

An application where people can share and find recipes.

[[Click here to checkout demo.]](https://react-graphql-recipes.herokuapp.com/)

Stack: React + GraphQL (Apollo Stack) + Express + Mongoose + JWT + Pose + Skeleton CSS.

<img src="https://jlyu26.github.io/assets/img/recipeak.PNG" alt="">

## Milestones:

| Function     | Description   | Status  | Tech Used  |
| -------------|:--------------| ------- |:----------- |
| 1. User signup |  | Finished | bcrypt (hash password), react-router-dom (routing), react-apollo (Mutation component) |
| 2. User signin and authentication, redirect upon signin/signup || Finished | Local Storage, JWT, graphql-express middleware, HOC (Higher-Order Components, withSession.js and withRouter from react-router-dom) |
| 3. Navigation, dynamic navbar based on whether user logged in, user signout || Finished | session, ApolloConsumer from react-apollo, localStorage |
| 4. Create and display recipes || Finished | react-apollo (Mutation component), apollo-cache-inmemory (InMemoryCache, cache object), Optimistic UI. |
| 5. Search recipe(s) || Finished | react-apollo (ApolloConsumer component) |
| 6. User profile || Finished | Route protection: add withAuth()() to Profile and AddRecipe route |
| 7. Delete user recipes || Finished | Optimistic UI |
| 8. Like/unlike recipe || Finished | Optimistic UI, like/unlike toggle client-side logic |
| 9. Clean up repetitive in queries || To do | Fragments |
| 10. Integrate CKEditor || Finished | react-ckeditor-component (CKEditor) |
| 0. Polish UI apperance || Finished | react-pose (React Pose Animation), react-spinners, Skeleton CSS |