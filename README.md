### Configuración del Proyecto

Este repositorio incluye configuraciones específicas para el desarrollo que puedes revisar y utilizar como referencia.

#### Dependencias de Desarrollo

El archivo `package.json` contiene las siguientes dependencias de desarrollo junto con las versiones específicas:

```json
"devDependencies": {
  "@testing-library/jest-dom": "^6.4.6",
  "@testing-library/react": "^16.0.0",
  "@types/aos": "^3.0.7",
  "@types/react": "^18.2.66",
  "@types/react-dom": "^18.2.22",
  "@vitejs/plugin-react": "^4.2.1",
  "jsdom": "^24.1.0",
  "typescript": "^5.2.2",
  "vite": "^5.2.0",
  "vitest": "^1.6.0",
  "@typescript-eslint/eslint-plugin": "^6.0.0",
  "@typescript-eslint/parser": "^6.0.0",
  "eslint": "^8.54.0",
  "eslint-config-airbnb": "^19.0.4",
  "eslint-config-airbnb-typescript": "^17.1.0",
  "eslint-config-prettier": "^9.0.0",
  "eslint-plugin-import": "^2.29.0",
  "eslint-plugin-jsx-a11y": "^6.8.0",
  "eslint-plugin-prettier": "^5.0.1",
  "eslint-plugin-react": "^7.33.2",
  "eslint-plugin-react-hooks": "^4.6.0",
  "eslint-plugin-react-refresh": "^0.4.4",
  "vite-plugin-eslint": "^1.8.1",
  "prettier": "^3.1.0"
}
```

#### Instalación de Dependencias

Para instalar todas las dependencias listadas en el archivo `package.json` con las versiones especificadas y forzar la instalación, ejecuta el siguiente comando:

```bash
npm install --save-dev --force @testing-library/jest-dom@^6.4.6 @testing-library/react@^16.0.0 @types/aos@^3.0.7 @types/react@^18.2.66 @types/react-dom@^18.2.22 @vitejs/plugin-react@^4.2.1 jsdom@^24.1.0 typescript@^5.2.2 vite@^5.2.0 vitest@^1.6.0 @typescript-eslint/eslint-plugin@^6.0.0 @typescript-eslint/parser@^6.0.0 eslint@^8.54.0 eslint-config-airbnb@^19.0.4 eslint-config-airbnb-typescript@^17.1.0 eslint-config-prettier@^9.0.0 eslint-plugin-import@^2.29.0 eslint-plugin-jsx-a11y@^6.8.0 eslint-plugin-prettier@^5.0.1 eslint-plugin-react@^7.33.2 eslint-plugin-react-hooks@^4.6.0 eslint-plugin-react-refresh@^0.4.4 vite-plugin-eslint@^1.8.1 prettier@^3.1.0
```

Para instalar las dependencias sin especificar versiones y forzar la instalación, puedes ejecutar:

```bash
npm install --save-dev --force @testing-library/jest-dom @testing-library/react @types/aos @types/react @types/react-dom @vitejs/plugin-react jsdom typescript vite vitest @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-react-refresh vite-plugin-eslint prettier
```

#### Configuraciones

Es importante copiar los archivos de configuración de ESLint (`eslint.config.js`) y Prettier (`prettier.config.js`) ubicados en la raíz del proyecto para asegurar la consistencia y calidad del código.

- **ESLint**: Utiliza las reglas de Airbnb para JavaScript y TypeScript, integradas con Prettier para mantener el estilo y la legibilidad del código.

- **Prettier**: Configurado para formatear automáticamente el código según las mejores prácticas y estándares establecidos.

