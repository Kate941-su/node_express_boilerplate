# Node Express Boilerplate

Once you do clone this repository, you can establish your minimum express server.

## How to establish

1. Execute `npm install` command to resolve dependencies. After the command you can see that the errors in your directory will be valished.
2. See `package.json` file.
```json
{
  "name": "node_express_server_boilerplate",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "npx ts-node-dev --respawn --transpile-only --exit-child server.ts",⭐️
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "MIT",
  "devDependencies": {
    "@mermaid-js/mermaid-cli": "^10.8.0",
    "@types/cors": "^2.8.17",
    "@types/express": "^4.17.21",
    "@types/morgan": "^1.9.9",
    "@types/node": "^20.11.17",
    "morgan": "^1.10.0",
    "ts-node-dev": "^2.0.0",
    "typescript": "^5.3.3"
  },
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.18.2",
    "hi-base32": "^0.5.1",
    "otpauth": "^9.2.2"
  }
}
```
When you execute `npm start`, you can build server and can access `localhost:8000`
