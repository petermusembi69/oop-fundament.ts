# oop-fundament.ts 

## Command used to create the project.

Creates a npm project without a the interacting prompts
```typescript
npm init -y
```

Add typescript as a dev dependency
```typescript
yarn add -DE typescript`
```

NB: If yarn is unrecognized install it using npm - global flag  
```typescript
npm install --global yarn
```

Create a tsconfig.json file used when compiling typescript
```typescript
npx tsc --init
```
Add typescript file using the echo command
```typescript
echo console.log("Hello tsc"); > index.tsc
```

Ops, a typo rename the file using the ren command
`ren *.tsc *.ts`

Compile our ts file to generate a js file
```typescript
npx tsc`
```
Run our index.js file using node
```typescript
node index.js
```

## Project Description
The project creates an in memory database using typescript.

- [x] Concept 1 - Factory
- [ ] Concept 2 - Singleton
- [ ] Concept 3 - Observer and Listeners
- [ ] Concept 4 - Visitor