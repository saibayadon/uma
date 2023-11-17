# 🎠
## TypeScript Lambda Starter
Simple AWS Lambda Starter Kit using SAM (https://aws.amazon.com/serverless/sam/).

### Defaults
- **TypeScript 5.2.2**

### How to run locally
- `bun install`
- `bun run build`
- `sam local invoke "HelloWorldFunction" --no-event`

### Build and deploy
- `bun run build` -> Will output a build folder
- `sam deploy --guided` -> Will walk you through deployment steps

### Linting
**ESLint** (Using TypeScript defaults)
- `bun run lint` -> Will lint all code under `src` folder.