## Requirements for the project
* Node.Js 24 or plus - Verify the version:
```
node -v
```

## Sequence for creating the project
Initialize the Node.Js project by generating a package.json file:
```
npm init
```

Install Express:
```
npm install express
```

Install TypeScript together with the community-maintained types for Express and Node.js as development dependencies:
```
npm install --save-dev typescript @types/express @types/node
```

Install project compiler for TypeScript:
```
npm i --save-dev ts-node
```

Create tsconfing.json file:
```
npx tsc --init
```