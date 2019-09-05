# Express TypeScript Boilerplate

## Using `curl`
```
$ bash <(curl -s https://raw.githubusercontent.com/sidhantpanda/public/master/scripts/generate-express-ts-app.sh)
```

## Manual Method
#### 1. Clone this repo
```
$ git clone git@github.com:sidhantpanda/express-typescript-boilerplate.git your-app-name
$ cd your-app-name
```

#### 2. Install dependencies
```
$ npm i
```

#### 3. Start dev server
```
$ npm run dev
```

#### 4A. Run with docker-compose
```
$ docker-compose up
```

#### 4B. Run with docker
```
$ docker build -t api-server .
$ docker run -t -i -p 3000:3000 api-server
```


#### 4C. Build and run
```
$ npm run build && npm run start
```

---

### Directory Structure

```
+-- src
|   +-- routes
|   |   +-- home
|   |   |   +-- controller.ts
|   |   |   +-- index.ts
|   |   +-- user
|   |   |   +-- controller.ts
|   |   |   +-- index.ts
|   +-- app.ts
|   +-- server.ts
+-- .eslintrc.js
+-- .gitignore
+-- .prettierrc.js
+-- docker-compose.yml
+-- Dockerfile
+-- nodemon.json
+-- package-lock.json
+-- package.json
+-- README.md
+-- tsconfig.json

```