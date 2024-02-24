# TS
## commands used for this project

`Command for:` Initializing a new package.josn file, __-y__ or __--yes__ to automatically accept all default configuration options.
```bash
npm init -y
# or
npm init --yes
# or for step by step configuration
npm init
```

`Command for:` __npm i__ is npm install, __--save-dev__ to specify that the package being installed should be added as a development dependency, __typescript__ the name of the package.
```bash
npm i --save-dev typescript
```

`Command for:` To initalize a TypeScript configuration
```bash
npx tsc --init
```

`Command for:` __npm create-snowpack-app__ to craete a snowpack application, __(.)__ represents the current directory, __--template @snowpack/app-template-blank-typescript__ specifies the template to use for creating the snowpack application
```bash
npx create-snowpack-app . --template @snowpack/app-template-blank-typescript

# or force the creation if the directory is not empty
npx create-snowpack-app . --template @snowpack/app-template-blank-typescript --force
```


`Command for:` To create unique id for each task
```bash
npm i uuid
```

`Command for:` To add it in the development dependency, dev dependency are typically TypeScript type defination or tool that are used during the development or build process but are not needed in production runtime 
```bash
npm i --save-dev @types/uuid
```

`Command for:` to run the application
```bash
npm start
```
