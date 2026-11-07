# PersonalBoard: showcase

Tablero **Kanban** personal para gestionar proyectos y tareas. Aplicación full-stack en producción. Este repositorio es una vitrina pública; el código fuente es privado.

## Arquitectura

```text
Angular 21 (Cloudflare Pages)  ──►  API Fastify + Zod (Vercel)  ──►  PostgreSQL (Neon)
        nova-iris-ui                 sesión por cookie HttpOnly          scripts y procedimientos
```

## Funcionalidades

- Kanban con drag & drop, filtros por proyecto y resumen.
- CRUD de proyectos en tabla con búsqueda.
- Perfil y cambio de contraseña.
- Sesión persistente con cookie `HttpOnly` y `SameSite=Strict`.

## Calidad

- TypeScript estricto en todo el stack y validación de entradas con Zod.
- Pruebas unitarias con Vitest.
- Configuración por entornos, sin secretos en el repositorio.
- Base de datos versionada en un repositorio propio.

## Stack

Angular 21 · [`@chrisdesign95/nova-iris-ui`](https://www.npmjs.com/package/@chrisdesign95/nova-iris-ui) · Node 24 · Fastify · Zod · PostgreSQL · Docker · Cloudflare Pages · Vercel · Neon.

## Contacto

[Christian Castro](https://github.com/chrisdesing1995) · fernandochris1995@gmail.com
