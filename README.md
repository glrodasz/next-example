# Next Example

1. Inicializar el `package.json` con el comando `npm init -y`.
2. Hacer el archivo `.gitignore` y ignorar `node_modules`.
3. Instalar las dependencias y guardarlas en el `package.json`.
4. Copiar los scripts de next.js y remplazarlos en el `package.json`.
```
"scripts": {
  "dev": "next",
  "build": "next build",
  "start": "next start"
},
```
5. Crear la carpeta `pages` y crear un archivo `index.js` con el siguiente contenido:
```
export default () => (
  <div>Welcome to the jungle</div>
)
```
