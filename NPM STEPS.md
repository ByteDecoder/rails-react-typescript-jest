```bash
$ rails new myapp --webpack=react
$ cd myapp

Add Typescript:
$ bundle exec rails webpacker:install:typescript

$ yarn add eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-config-preact @types/webpack-env eslint-plugin-react -D
$ yarn add babel-plugin-transform-react-jsx

$ yarn add jest ts-jest @types/jest @testing-library/react @testing-library/jest-dom -D
```
