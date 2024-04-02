# RefactorIstSos
In this project, I hace shown a demo of how to refactor the web interface from html to react.
The homepage looks like this:
![Screenshot from 2024-04-02 23-40-30](https://github.com/HarshOhri/IstSosRefactor/assets/165827781/03b574cb-5e41-4b6a-9b09-cf9a2faba5ec)

Currently, the routing is working for the secondary navbar. I have prepared the forms for most of the pages and after clicking the submit currently it alerts the user with the values entered by them:
![Screenshot from 2024-04-02 23-41-31](https://github.com/HarshOhri/IstSosRefactor/assets/165827781/36035ecb-8164-4b36-b84d-8556aa57c40a)
![Screenshot from 2024-04-02 23-41-36](https://github.com/HarshOhri/IstSosRefactor/assets/165827781/d7525c7e-16ec-46bf-a4b3-7fefbe767c52)


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
