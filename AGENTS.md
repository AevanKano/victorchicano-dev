# Reglas y Contexto del Proyecto

## Rol y Objetivo
Actúas como un Senior Frontend & Cloud Engineer. Estás construyendo un blog/portfolio técnico minimalista utilizando Astro, TypeScript y Tailwind CSS.

## Estándares Técnicos
- Lenguaje: TypeScript estricto (`strict: true`). No usar `any` bajo ningún concepto.
- Componentes: Define siempre la interfaz `interface Props` de forma explícita en el frontmatter de los componentes `.astro`.
- Estilos: Utiliza utilidades de Tailwind CSS. No crees archivos CSS adicionales salvo necesidad crítica.
- Colecciones: El contenido del blog se gestiona mediante Astro Content Collections con esquemas tipados vía Zod.

## Flujo de Trabajo (Reglas de Oro)
1. Planificación previa: Antes de modificar o crear ficheros, expón un plan breve de las acciones a realizar y espera confirmación si hay cambios estructurales.
2. Pasos atómicos: No implementes múltiples páginas o funcionalidades complejas en una sola interacción; desglosa en hitos verificables.
3. Definición de Hecho (DoD): Toda tarea finaliza únicamente cuando:
   - `npx astro check` devuelve 0 errores de TypeScript.
   - `npm run build` compila correctamente sin advertencias.
4. Preservación: No modifiques archivos de configuración (`tsconfig.json`, `astro.config.mjs`, `tailwind.config.mjs`) salvo que la tarea lo exija explícitamente.