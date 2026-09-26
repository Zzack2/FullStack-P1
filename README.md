# TiendaMenos - Frontend

Frontend de **TiendaMenos**, desarrollado con **Angular**.
La aplicación permite gestionar el catálogo, carrito de compras, autenticación y panel administrativo.

## Requisitos

* Node.js
* npm
* Angular

## Instalación

Clonar el repositorio y ejecutar:

```bash
npm install
```

## Ejecución

Para iniciar el proyecto:

```bash
npm start
```

La aplicación estará disponible en:

```text
http://localhost:4200
```

## Tecnologías

* Angular
* TypeScript
* Tailwind CSS
* RxJS

## Estructura

* `src/app/` — Componentes y páginas de la aplicación.
* `src/core/` — Servicios y configuración.
* `public/` — Recursos y datos utilizados por el frontend.
* `src/app/app.routes.ts` — Configuración de rutas y acceso por roles.

## Estado actual

El frontend utiliza datos de prueba mediante `mock_data.json` y almacenamiento local para algunas funciones. Actualmente **no contiene usuarios de prueba registrados**.
