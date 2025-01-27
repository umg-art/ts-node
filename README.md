## Typescript project setup

```
install typescript first: 

npm i -D typescript
```

step 2 : 
```
npm i -D ts-node
```
step 3 : to genrate the tsconfig.json (optional)
```
-> tsc --init

```

modify the outDir to the dist folder.
```
"baseUrl" : "src"
```

if you are using the src/ folder then add this line after "compilerOptions"
```
"include": ["src/**/*.ts"],
```

## For NodeJs types

```
npm i @types/express @types/mongoose 
```