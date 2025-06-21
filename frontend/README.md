

# 🎨 BA-Atelier Frontend

**BA Atelier – Página Web de Alta Costura**

**BA Atelier** es un espacio exclusivo dedicado a la moda de alta costura, donde cada prenda es una obra de arte creada con pasión y atención al detalle. Este repositorio contiene el código para la página web de BA Atelier, que ofrece una experiencia digital única para los amantes de la moda.

---

## ✨ Servicios destacados

- 👗 **Diseño de Alta Costura**: Colecciones personalizadas y prendas únicas creadas para clientes exigentes.
- 💬 **Consultoría de Moda Personalizada**: Asesoramiento sobre tendencias, estilo y adaptación de looks a medida.
- ✂️ **Arreglos y Transformaciones**: Modificación de prendas existentes, asegurando un ajuste perfecto.
- 🎉 **Eventos Exclusivos**: Información sobre desfiles, presentaciones y eventos privados de moda.

Esta página está diseñada para proporcionar una experiencia elegante y sofisticada, al igual que las creaciones de BA Atelier, ofreciendo un vistazo a la artesanía y visión detrás de cada colección.


---

## 🚀 Tecnologías principales

- ⚡ **Astro** – Framework web moderno, rápido y orientado a contenido estático/dinámico. [Astro](https://astro.build/), [Tailwind CSS](https://tailwindcss.com/) y [TypeScript](https://www.typescriptlang.org/). Esta interfaz moderna y modular aprovecha integraciones como Clerk para autenticación y anima elementos mediante Tailwind Animations.

---

## 🚀 Tecnologías principales

- ⚡ **Astro** – Framework web moderno, rápido y orientado a contenido estático/dinámico.
- 🎨 **Tailwind CSS** – Framework de estilos utilitarios con animaciones personalizadas.
- 🔐 **Clerk** – Autenticación de usuarios lista para producción.
- 🧠 **TypeScript** – Tipado estático para mayor robustez y escalabilidad.
- 📦 **pnpm** – Gestor de paquetes ultrarrápido.

---

## 📁 Estructura del proyecto

```bash
Frontend/
├── .env                # Variables de entorno
├── public/             # Archivos estáticos (favicon, íconos, etc.)
├── src/                # Código fuente
│   ├── assets/         # Imágenes y recursos visuales
│   ├── components/     # Componentes reutilizables
│   ├── layouts/        # Plantillas de diseño
│   ├── pages/          # Rutas del sitio (Astro routing)
│   ├── Scripts/        # Lógica o scripts auxiliares
│   └── styles/         # Archivos CSS globales
├── astro.config.mjs    # Configuración de Astro
├── tailwind.config.mjs # Configuración de Tailwind CSS
├── tsconfig.json       # Configuración de TypeScript
├── package.json        # Scripts y dependencias
└── pnpm-lock.yaml      # Lockfile de dependencias
```

---

## 🛠 Scripts disponibles

Todos los comandos se ejecutan con `pnpm`:

| Comando        | Descripción                          |
|----------------|--------------------------------------|
| `pnpm install` | Instala todas las dependencias       |
| `pnpm dev`     | Inicia el servidor de desarrollo     |
| `pnpm build`   | Genera la build optimizada           |
| `pnpm preview` | Previsualiza la build antes de subir |

---

## 📦 Dependencias clave

```json
"dependencies": {
  "@astrojs/node": "^9.2.2",
  "@clerk/astro": "^2.9.1",
  "@clerk/localizations": "^3.16.5",
  "@clerk/themes": "^2.2.50",
  "@midudev/tailwind-animations": "^0.2.0",
  "@tailwindcss/vite": "^4.1.10",
  "astro": "^5.9.4",
  "tailwindcss": "^4.1.10"
}
```

---

## ✅ Requisitos del entorno

- [Node.js](https://nodejs.org/) ≥ 18
- [pnpm](https://pnpm.io/) ≥ 8

---

## 🧪 Instalación y uso

```bash
# Clonar el repositorio
git clone https://github.com/DKRblasam/BA-Atelier.git
cd BA-Atelier/Frontend

# Instalar dependencias
pnpm install

# Iniciar el servidor de desarrollo
pnpm dev
```

---

## 🔐 Autenticación

Este proyecto usa [Clerk](https://clerk.dev/) para la gestión de usuarios. Asegúrate de crear un archivo `.env` con las claves necesarias basadas en `.env.example`.

---

## 📄 Licencia

MIT – [LICENSE](../LICENSE)

---

## ✨ Créditos

Proyecto creado y mantenido por [DKRblasam](https://github.com/DKRblasam).  
Inspirado en el enfoque moderno y accesible para aplicaciones web frontend.
