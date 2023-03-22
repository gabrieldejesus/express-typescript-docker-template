# express-typescript-docker-template

🐳 NODE.TS - TypeScript starter for quick test projects using Docker and Express.

## Installation

#### 1. Clone project

```
$ git clone https://github.com/gabrieldejesus/express-typescript-docker-template your-app-name
$ cd your-app-name
```

#### 2. Install dependencies

```sh
$ npm install # or just npm i
```

## Run Locally

#### 1. Start the server in dev mode

```sh
$ npm run dev
```

#### 2. Start the server with Docker

```sh
$ docker build . -t your-app-name
```

```sh
$ docker run --rm -p 3000:3000 your-app-name
```
