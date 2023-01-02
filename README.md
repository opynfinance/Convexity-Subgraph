# Opyn Options Protocol Subgraph

Subgraph that processes data for the Opyn.co Convexity Protocol.

### Deploy subgraph

#### Install dependencies

```bash
$ yarn
```
or
```bash
$ npm i
```

#### Store the access token

Replace `<ACCESS_TOKEN>` in `auth` package.json script with your access token displayed on The Graph dashboard , then run

```bash
$ yarn auth
```
or
```bash
$ npm run auth
```

You only need to do this once, or if you ever regenerate the access token.

#### Deploy

```bash
$ yarn codegen
$ yarn deploy
```
or
```bash
$ npm run codegen
$ npm run deploy
```
test
