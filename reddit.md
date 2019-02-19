# Reddit

## Description

The purpose of this team is to create a simplified [Reddit](https://reddit.com/) clone. Users can sign up and sign in with their Google account. After authentication they are able to submit new post in 3 different types: text, link or image/video, use in-app messaging system, view posts, filter posts by channel or search phrase, vote up/down posts and leave comments under posts.

## Technologies

In this project we are using Angular as frontend, and Node.js as backend combined with MongoDB as database.
Apprentices create routing and layout included Angular components and services which use mock data at this point.
Apprentices create backend endpoints with Express which use a database layer to work with data via Mongoose ODM.
Apprentices wire together frontend and backend and we can see real data in frontend received from backend.
Apprentices write tests for Angular components and services as well as backend endpoints.
Apprentices create Google authentication: in frontend they authenticate and in backend they verify the received token to get the own user object of system together with the generated authentication token.
Eventually apprentices implement more authentication methods and extra features like in-app chat with socket.io.

### Angular
  - Angular CLI
  - Routing, Components, Services
  - Testing with Jasmine + Karma
  - Authentication with Google

### Node.js
  - Express
  - Mongoose
  - Testing with Mocha + Chai
  
### Database: MongoDB

### CI/CD
  - CircleCI
  - Heroku or AWS

## Main Features

- Add new post in 3 different types (included drag'n'drop), and edit or delete post
- View all posts or filtered posts with a channel selector or a search phrase
- Add, edit and delete comment under post
- Handle in-application messaging
- Authenticate with Google
