# 🔴 Pokedex PWA - React

Una aplicación web progresiva (PWA) desarrollada con **React** que permite explorar, buscar, ordenar y consultar información detallada de diferentes Pokémon.

El proyecto consume la **PokéAPI** y cuenta con funcionalidades como favoritos, búsqueda, detalles de Pokémon e instalación como aplicación en dispositivos compatibles.

## 🚀 Demo

🔗 **GitHub:**
https://github.com/estivenbueno7-cell/pokedex-pwa-react-native

---

## ✨ Funcionalidades

* 🔎 Búsqueda de Pokémon por nombre.
* 📋 Listado de Pokémon.
* 🔢 Ordenamiento de Pokémon.
* ❤️ Sistema de favoritos.
* 📖 Vista detallada de cada Pokémon.
* 📱 Diseño responsive para dispositivos móviles y escritorio.
* ⚡ Consumo de la PokéAPI.
* 📲 Instalación como aplicación mediante PWA.
* 💾 Persistencia de favoritos en el navegador.
* 📥 Funcionalidad para descargar la Pokédex.
* 🚀 Carga dinámica de información.
* 🎨 Interfaz moderna y sencilla.

---

## 🛠️ Tecnologías utilizadas

### Frontend

* **React**
* **JavaScript**
* **Vite**
* **CSS**

### API

* **PokéAPI**
* https://pokeapi.co/

### PWA

* Service Worker
* Web App Manifest
* Cache de recursos
* Instalación en dispositivos compatibles

### Herramientas

* Git
* GitHub
* Visual Studio Code
* npm

---

## 📂 Estructura del proyecto

```text
pokedex/
│
├── public/
│   ├── icons/
│   └── ...
│
├── src/
│   ├── components/
│   │   ├── PokeCard.jsx
│   │   ├── PokeDetail.jsx
│   │   └── ...
│   │
│   ├── hooks/
│   │   ├── usePokemons.js
│   │   ├── useFavorite.js
│   │   ├── useInstallPrompt.js
│   │   └── useDownloadPokedex.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
│
├── package.json
├── vite.config.js
└── README.md
```

> La estructura puede variar dependiendo de la versión actual del proyecto.

---

## ⚙️ Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/estivenbueno7-cell/pokedex-pwa-react-native.git
```

### 2. Entrar al proyecto

```bash
cd pokedex-pwa-react-native
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Ejecutar el proyecto

```bash
npm run dev
```

La aplicación estará disponible normalmente en:

```text
http://localhost:5173
```

---

## 🔌 PokéAPI

La aplicación utiliza **PokéAPI** para obtener la información de los Pokémon.

Ejemplo de endpoint:

```text
https://pokeapi.co/api/v2/pokemon
```

La aplicación consulta información como:

* Nombre
* ID
* Imagen
* Tipos
* Estadísticas
* Habilidades
* Altura
* Peso
* Información adicional

---

## ❤️ Favoritos

Los usuarios pueden agregar Pokémon a una lista de favoritos.

Los favoritos se almacenan localmente en el navegador, permitiendo conservar la selección aunque el usuario cierre o recargue la aplicación.

---

## 📱 PWA

Este proyecto está preparado como **Progressive Web App**, permitiendo que los usuarios puedan instalar la aplicación en dispositivos compatibles.

Dependiendo del navegador y dispositivo, puede aparecer una opción similar a:

```text
Instalar aplicación
```

Una vez instalada, la Pokédex puede ejecutarse como una aplicación independiente.

---

## 📥 Descarga de la Pokédex

La aplicación incorpora una funcionalidad para permitir al usuario descargar información de la Pokédex para utilizarla posteriormente.

Esta funcionalidad está implementada mediante el hook:

```text
useDownloadPokedex.js
```

---

## 🔍 Búsqueda y ordenamiento

La aplicación permite localizar Pokémon rápidamente mediante el buscador.

También cuenta con diferentes opciones de ordenamiento para facilitar la navegación por el listado.

Ejemplo:

```text
Nombre A-Z
Nombre Z-A
Número ascendente
Número descendente
```

---

## 🧩 Componentes principales

### `PokeCard`

Componente encargado de representar cada Pokémon dentro del listado.

### `PokeDetail`

Muestra información detallada del Pokémon seleccionado.

### `usePokemons`

Hook encargado de gestionar la obtención de Pokémon desde la API.

### `useFavorite`

Gestiona el sistema de Pokémon favoritos.

### `useInstallPrompt`

Gestiona la posibilidad de instalar la aplicación como PWA.

### `useDownloadPokedex`

Gestiona la funcionalidad relacionada con la descarga de información de la Pokédex.

---

## 🧪 Scripts disponibles

Puedes ejecutar los siguientes comandos:

```bash
npm run dev
```

Inicia el servidor de desarrollo.

```bash
npm run build
```

Genera la versión optimizada para producción.

```bash
npm run preview
```

Permite visualizar localmente la versión de producción.

---

## 🌐 Producción

Para generar la aplicación optimizada:

```bash
npm run build
```

Los archivos generados estarán disponibles en:

```text
dist/
```

Esta carpeta puede desplegarse en servicios como:

* Vercel
* Netlify
* GitHub Pages
* Firebase Hosting

---

## 🎯 Objetivo del proyecto

Este proyecto fue desarrollado como una práctica para fortalecer conocimientos en:

* Desarrollo frontend con React.
* Consumo de APIs REST.
* Manejo de estados.
* Hooks personalizados.
* Componentización.
* Diseño responsive.
* Persistencia de información en el navegador.
* Desarrollo de aplicaciones PWA.
* Control de versiones con Git y GitHub.

---

## 👨‍💻 Autor

**Kevin Estiven Bueno Cardona**

Tecnólogo en Análisis y Desarrollo de Software — SENA.

GitHub:

https://github.com/estivenbueno7-cell

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de aprendizaje.

La información de Pokémon utilizada por la aplicación proviene de **PokéAPI**.

---

⭐ Si este proyecto te resulta útil, puedes darle una estrella al repositorio.
