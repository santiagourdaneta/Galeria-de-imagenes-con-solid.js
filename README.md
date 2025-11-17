# 🖼️ Galería de Imágenes Interactiva con SolidJS

Bienvenido al repositorio de una Galería de Imágenes dinámica, construida utilizando **SolidJS**, una librería de JavaScript conocida por su rendimiento y su modelo de reactividad de grano fino (fine-grained reactivity).

Este proyecto sirve como una excelente demostración de cómo utilizar los **Signals** de SolidJS para gestionar el estado de la aplicación (como la imagen actualmente seleccionada o el estado de una modal) de manera eficiente y con un rendimiento cercano al de JavaScript puro.

## ✨ Características Principales

* **Renderizado de Imágenes:** Muestra una cuadrícula de miniaturas de imágenes.
* **Visualización Reactiva:** Al hacer clic en una miniatura, se muestra la imagen en tamaño completo.
* **SolidJS Signals:** Uso de `createSignal` para la gestión de estado local, garantizando que solo los componentes necesarios se vuelvan a renderizar.
* **Alta Performance:** Aprovecha la arquitectura sin Virtual DOM (V-DOM) de SolidJS.
* **Diseño Moderno:** Estilizado con CSS para una interfaz de usuario atractiva y responsiva.

## 🛠️ Tecnologías Utilizadas

* **SolidJS:** La librería principal de JavaScript para la construcción de la interfaz.
* **Vite:** Herramienta de construcción (bundler) moderna y rápida, utilizada para el desarrollo y la compilación.
* **JavaScript (ES6+):** Lógica del lado del cliente.
* **HTML & CSS:** Estructura y estilos.

## 🚀 Cómo Empezar

Este proyecto requiere [Node.js](https://nodejs.org/) y npm/pnpm/yarn.

### 1. Clonar el repositorio

```bash
git clone [https://github.com/santiagourdaneta/Galeria-de-imagenes-con-solid.js.git](https://github.com/santiagourdaneta/Galeria-de-imagenes-con-solid.js.git)
cd Galeria-de-imagenes-con-solid.js

2. Instalación de dependencias
Instala los paquetes necesarios definidos en package.json:

npm install # o pnpm install o yarn install

3. Scripts disponibles
En el directorio del proyecto, puedes ejecutar:

npm run dev Inicia la aplicación en modo desarrollo. Abre http://localhost:5173 para verlo en el navegador.
npm run build Compila la aplicación para producción en la carpeta /dist. Optimiza el código para el mejor rendimiento.

💡 Aprende Más
Si eres nuevo en SolidJS, te animo a revisar el código en el directorio src/ para ver cómo se implementa la reactividad sin un V-DOM.

👥 Autor
Santiago Urdaneta
