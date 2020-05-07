# react-scratch
```bash
npm init -y
touch .gitignore

mkdir public src
touch public/index.html
npm install --save react react-dom

npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react
touch .babelrc

npm install --save-dev webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader
gs
touch webpack.config.js

npm install --save-dev typescript ts-loader
npm install --save-dev @types/react @types/react-dom
npx tsc --init

npm install --save-dev eslint prettier eslint-config-prettier eslint-plugin-prettier eslint-loader
npx eslint --init
touch .prettierrc

touch src/index.tsx
touch src/App.tsx
touch src/App.css

npx tsc
npx webpack
webpack-dev-server --mode development
 ```