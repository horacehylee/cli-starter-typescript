# Cli Starter Typescript

## Usage
```
# --depth 1 removes all but one .git commit history
git clone --depth=1 https://github.com/horacehylee/starter-cli-typescript.git <your-project-name>

# change directory to your project folder
cd <your-project-name>

# remove .git folder
rm -r .git

# development
npm run serve

# build
npm run build

# test
npm run test
```

## Change tool name
```typescript
// src/index.ts
const scriptName = "__tool_name__";
```

```js
// 
{
  "name": "starter-cli-typescript",
  ...
  "bin": {
    "__tool_name__": "./build/main.js"
  },
}
```

## License

MIT © [Horace Lee](https://github.com/horacehylee)