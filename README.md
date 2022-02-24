# 🎠
## TypeScript Lambda Starter
Simple AWS Lambda Starter Kit using SAM (https://aws.amazon.com/serverless/sam/).

### Defaults
- **TypeScript 5.0.4**

### How to run locally
- `yarn install`
- `yarn build`
- `sam local invoke "HelloWorldFunction" --no-event`

### Build and deploy
- `yarn build` -> Will output a build folder
- `sam deploy --guided` -> Will walk you through deployment steps

### Linting
**ESLint** (Using TypeScript defaults)
- `yarn lint` -> Will lint all code under `src` folder.