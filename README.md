# https://app.chesslang.com/ source code

### Api Key info

- Get Firebase Api Keys from https://firebase.google.com/
- Get Locize API Keys from https://locize.com/?lng=en

### Setup

```
# Make sure you have node version : v11.15.0

cp .env.example .env
# Set the API Keys
yarn remove @types/react-dom @types/react


yarn add -D @types/react-dom @types/react
yarn install
yarn run dev
```

### Indent files

```
yarn run indent
```

### Localization

[Localization readme](src/locize/readme.md)
npm install --g --production windows-build-tools
