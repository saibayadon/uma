# 🎠

## TypeScript Lambda Starter

Simple AWS Lambda Starter Kit using SAM (https://aws.amazon.com/serverless/sam/).

For a more robust serverless setup, check out https://sst.dev/

### Defaults

- **TypeScript 5.6.3**

### How to run locally

- `bun i`
- `bun run build`
- `sam local invoke "HelloWorldFunction" --no-event`

### Build and deploy

- `bun run build` -> Will output a build folder
- `sam deploy --guided` -> Will walk you through deployment steps

### Linting

**ESLint** (Using TypeScript defaults)

- `bun run lint` -> Will lint all code under `src` folder.
