# TAILWINDCSS-REACT

### Crear Proyecto desde cero
```sh
npx create-react-app tailwindcss-react
cd tailwindcss-react
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm install react-scripts@latest
npm run start
```

#### Posterior a la instalación
 * Agregar las siguientes lineas al archivo _tailwind.config.js_
    ```js
    module.exports = {
    content: [
        "./src/**/*.{js,jsx,ts,tsx}",
    ],
    theme: {
        extend: {},
    },
    plugins: [],
    }
    ```

* Agregar dependencias css al archivo _src/index.css_
    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
### Clonar e utilizar este proyecto
```sh
npm i
npm run start
```


NOTA:
Este proyecto utiliza las dependencias:

| Plugins |
| ------ |
[@heroicons/react](https://www.npmjs.com/package/@heroicons/react)
[@headlessui/react](https://www.npmjs.com/package/@headlessui/react)


