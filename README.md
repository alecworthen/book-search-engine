# Book Explorer: A GraphQL-powered Book Search Engine

## Overview

In this project, you will refactor a fully functioning Google Books API search engine from using a RESTful API to utilizing GraphQL. The application is built using the MERN stack, including a React front end, MongoDB database, and Node.js/Express.js server and API. The primary goal is to enhance the application's performance and scalability by transitioning to a GraphQL API built with Apollo Server.

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria
```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with options to Search for Books and Login/Signup, along with an input field and a submit button for searching books
WHEN I enter a search term and click the submit button
THEN I am presented with search results including the book's title, author, description, image, and a link to view more details on the Google Books site
WHEN I click on the Login/Signup option
THEN I am presented with a modal to login or signup
WHEN I login or signup
THEN I am logged into the application and can perform various actions such as saving books or viewing saved books
```

## Getting Started

To start working on this project, follow these steps:

1. Clone the repository from GitHub.
2. Install dependencies by running `npm install`.
3. Set up your environment variables.
4. Ensure MongoDB is installed and running.
5. Start the development server by running `npm start`.

## Back-End Specifications

### Authentication Middleware

- Update the `auth.js` middleware function to work with the GraphQL API.

### GraphQL Schema and Resolvers

- Define query and mutation functionality in the `resolvers.js` file.
- Export typeDefs and resolvers in `index.js`.
- Define necessary `Query`, `Mutation`, `User`, `Book`, and `Auth` types in `typeDefs.js`.

## Front-End Specifications

### Queries and Mutations

- Create `queries.js` and `mutations.js` files.
- Define GraphQL queries and mutations using Apollo Client hooks.

### Components

- Update components such as `SearchBooks`, `SavedBooks`, `SignupForm`, and `LoginForm` to work with Apollo Client.

## Deployment

Deploy the application to a live URL using a service like Render. Ensure that the application loads with no errors and submit the GitHub repository URL.

## Author

[Alec Worthen](https://github.com/alecworthen/book-search-engine)