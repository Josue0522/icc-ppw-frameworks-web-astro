# Programación y Plataformas Web
Astro: Desarrollo Web Moderno
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/astro/astro-original-wordmark.svg" width="80" alt="Astro Logo"> </div> 

## Práctica 02: Fundamentos de Astro
Autor

Josue Abad

## Objetivo

Extender el proyecto astro-campus para practicar la estructura básica de Astro mediante frontmatter, componentes reutilizables, props tipados, renderizado de listas y renderizado condicional.

## Contexto de la práctica

Esta práctica continúa sobre el proyecto creado en la práctica 01. En este módulo se agregan nuevas páginas y un componente reutilizable para comprender mejor cómo Astro organiza contenido, componentes y rutas.

El proyecto se amplió con:

una página about.astro
un componente RecursoCard.astro
integración del componente en la página principal
Estructura trabajada
astro-campus/
└── src/
    ├── components/
    │   └── RecursoCard.astro
    └── pages/
        ├── index.astro
        └── about.astro

## Archivos modificados y creados
src/components/RecursoCard.astro
src/pages/index.astro
src/pages/about.astro

## Desarrollo realizado
Paso 1. Crear el componente RecursoCard

Se creó un componente reutilizable para mostrar recursos con título, enlace y descripción opcional.

Paso 2. Actualizar index.astro

Se importó RecursoCard en la página principal y se renderizó una lista de recursos usando .map().

Paso 3. Crear about.astro

Se añadió una segunda página con información del proyecto y del equipo.

Paso 4. Renderizado condicional

Se agregó un mensaje dinámico que cambia según si la aplicación está en modo desarrollo o en producción usando import.meta.env.PROD.

## Verificación

Se ejecutó el siguiente comando:

pnpm astro check

## Resultado obtenido:

0 errores
0 warnings
0 hints

## Validaciones realizadas
 Existe src/components/RecursoCard.astro
 La página principal renderiza los recursos correctamente
 La ruta /about funciona sin errores
 pnpm astro check no reporta errores
 Los estilos del componente se mantienen encapsulados
 El mensaje de modo desarrollo se muestra correctamente
Evidencias

## Las capturas se guardaron en assets/.

02-home-recursos.png — página principal con los recursos renderizados
02-about.png — página /about funcionando correctamente
Resultado final

## El proyecto ahora cuenta con:

componentes reutilizables
props tipados
renderizado de listas con .map()
renderizado condicional
múltiples páginas dentro del sistema de rutas de Astro

Esto deja lista la base para continuar con los siguientes módulos.

## Comandos utilizados
pnpm dev
pnpm astro check
pnpm build
pnpm preview
Repositorio

Proyecto desarrollado dentro del workspace de prácticas de Programación y Plataformas We