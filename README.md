# Star Wars Characters Portal 

Este proyecto es una aplicación web construida con **Vue 3 + Vite** que muestra una galería de personajes del universo de Star Wars, utilizando datos obtenidos dinámicamente desde la **API pública SWAPI** (https://swapi.dev/).

## Características

- Consumo de la API SWAPI: [https://swapi.dev/api/people/](https://swapi.dev/api/people/)
- Visualización de personajes en tarjetas: nombre, altura, género y año de nacimiento.
- Interfaz responsive usando CSS puro (sin frameworks).
- Navegación entre vistas usando Vue Router.
- Componentes reutilizables: Navbar, Footer y PersonCard.
- Manejo básico de carga (`loading`) y errores.

## Tecnologías utilizadas

- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Vue Router](https://router.vuejs.org/)
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- CSS puro

## Estructura del proyecto

src/
├── assets/
├── components/
│   ├── Navbar.vue
│   ├── Footer.vue
│   └── PersonCard.vue
├── views/
│   └── PeopleList.vue
├── router/
│   └── index.js
├── App.vue
├── main.js
├── style.css

## Instalación y ejecución

1. Clona este repositorio o descarga el ZIP:

```bash
git clone https://github.com/tu-usuario/StarWarsPortal.git
cd StarWarsPortal

2. instala las dependencias:
    npm install

3. Ejecuta el proyecto localmente:
    npm run dev

4. Abre el navegador en:
    http://localhost:5173

