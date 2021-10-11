# learning-react


Crear proyecto base de ReactJS.
```bash
npx create-react-app my app
```


Instalar Husky como `devDependency`
```bash
npm install husky -D
```

Usar [conventional changelog](https://github.com/conventional-changelog/commitlint)
Instalar directorio Husky en el proyecto
```bash
npx husky install
```

Crear commitlint.config.js
```bash
# Indicar que usaremos ese script para el conventional commit
module.exports = {extends: ["@commitlint/config-conventional"]};
```

```bash
npx husky add ./husky/pre-commit “npm test”
```
Configurar Linter para el commit [CommonLint](https://commitlint.js.org/#/?id=getting-started)
```bash
npx husky add ./husky/commit-msg 'npx --no-install commitlint --edit "$1"'
```
```bash

```
```bash

```
