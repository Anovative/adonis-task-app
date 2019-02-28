# Adonis Task App

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Run the following command to install Node packages
```
npm i
```

Create a `.env` file in the root of the project and copy all of the contents of the `.env.example` file.

Generate your `APP_KEY`
```
adonis key:generate
```

### Migrations

Run the following command to run startup migrations
```
adonis migration:run
```

### Run The App

Run the following command to start the application
```
npm run dev
```

You should see that the app is served up by default on host 127.0.0.1 and on port 3333. 
Both the host and the port can be changed in the `.env` file. 
The app will be available at `127.0.0.1:3333`

**NOTE: Commands above assume you are in the root of the project directory**
