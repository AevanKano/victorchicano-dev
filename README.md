# victorchicano.dev

> Portfolio y blog técnico personal enfocado en arquitectura frontend, ingeniería cloud, rendimiento web y automatización DevOps.

---

## 🚀 Stack Tecnológico

- **[Astro](https://astro.build/)**: Framework web server-first basado en la arquitectura de islas (Islands Architecture) para conseguir cero JavaScript innecesario por defecto.
- **[TypeScript](https://www.typescriptlang.org/)**: Configuración en modo estricto (`strict: true`, extensión de `astro/tsconfigs/strictest`).
- **[Tailwind CSS](https://tailwindcss.com/)**: Diseño minimalista, responsivo y modo oscuro nativo mediante clases de utilidad.
- **[Astro Content Collections](https://docs.astro.build/en/guides/content-collections/)**: Gestión de contenido tipado con esquemas validados en tiempo de compilación mediante **Zod**.

---

## 📐 Principios de Desarrollo

- **Seguridad de Tipos Estricta:** Cero uso de `any`. Todos los componentes `.astro` definen explícitamente su contrato de propiedades mediante `interface Props`.
- **Rendimiento Extremo:** Generación de sitio estático (SSG) con tiempos de carga instantáneos y Core Web Vitals optimizados.
- **Calidad de Código y DoD:** Cada cambio requiere pasar `npx astro check` sin errores ni advertencias de tipo antes de generar el build de producción.

---

## 🛠️ Guía de Comandos

Clona el repositorio e instala las dependencias:

```bash
# Instalación de dependencias
npm install

# Servidor de desarrollo (disponible en http://localhost:4321)
npm run dev

# Verificación estricta de tipos TypeScript
npx astro check

# Compilación estática para producción (directorio /dist)
npm run build

# Vista previa del build de producción en local
npm run preview
```

---

## 📄 Licencia

Distribuido bajo la licencia MIT. Consulta el archivo de licencia para más detalles.
