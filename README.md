# 🌴 Grand Theft Auto VI - Landing Page Clone

Una recreación interactiva y fluida de la landing page oficial de **Grand Theft Auto VI**, construida con **Astro**, **Tailwind CSS v4** y animaciones avanzadas mediante **GSAP & ScrollTrigger**.

🔗 **Demo en vivo**: [https://lading-gta-vi.netlify.app/](https://lading-gta-vi.netlify.app/)

> 💡 Proyecto inspirado y aprendido a través de las enseñanzas de **[Midudev](https://midu.dev/)**. Este proyecto continuará expandiéndose con nuevas secciones, tráilers, interactividad y optimizaciones.

---

## ✨ Características Principales

- ⚡ **Astro 5**: Rendimiento ultra rápido con arquitectura orientada a componentes.
- 🎨 **Tailwind CSS v4**: Estilizado moderno, personalización de fuentes GTA (`@theme`) y diseño adaptativo *Mobile-First*.
- 🎬 **Animaciones con GSAP & ScrollTrigger**:
  - Efecto dinámico de máscara de logo (`CSS mask-image` + `clamp`).
  - Animación y escalado de capas de fondo sincronizados con el scroll (`scrub`).
  - Transiciones suaves y desvanecimiento de controles de interfaz (UI Overlay).
- 📱 **Totalmente Responsive**: Optimizado para dispositivos móviles, tablets y pantallas de escritorio.
- 🔤 **Fuentes personalizadas**: Tipografías oficiales de GTA integradas mediante `@font-face`.

---

## 🛠️ Tecnologías Utilizadas

- [Astro](https://astro.build/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [GSAP (GreenSock)](https://gsap.com/) & ScrollTrigger
- [TypeScript](https://www.typescriptlang.org/)
- [pnpm](https://pnpm.io/)

---

## 🚀 Instalación y Uso Local

Sigue estos pasos para clonar y ejecutar el proyecto en tu entorno local:

### 1. Clonar el repositorio
```bash
git clone https://github.com/CODEATD/lading-gta-vi.git
cd lading-gta-vi
```

### 2. Instalar dependencias
Asegúrate de tener [pnpm](https://pnpm.io/) instalado:
```bash
pnpm install
```

### 3. Iniciar el servidor de desarrollo
```bash
pnpm dev
```
Abre tu navegador en `http://localhost:4321` para ver la aplicación en vivo.

### 4. Compilar para producción (Build)
```bash
pnpm build
```
Los archivos optimizados para despliegue (Netlify, Vercel, etc.) se generarán en la carpeta `dist/`.

### 5. Previsualizar la build de producción
```bash
pnpm preview
```

---

## 🗺️ Roadmap / Próximas Mejoras

Este proyecto se encuentra en constante evolución. Próximamente se añadirán:
- [ ] Separación modular de componentes (`Hero`, `HeroOverlay`, `Header`, `Footer`).
- [ ] Modal de reproducción para el tráiler oficial.
- [ ] Sección interactiva de personajes y novedades de Vice City.
- [ ] Soporte multidioma (i18n).
- [ ] Efectos de sonido y audio ambiente inmersivo.

---

## 👨‍💻 Autor

Desarrollado con dedicación por **CODE ATD**.

- 🌐 **Bio Link / Redes Sociales**: [bio.link/codeatd](https://bio.link/codeatd)
- 🐙 **GitHub**: [@CODEATD](https://github.com/CODEATD)

---

## 📄 Licencia

Este proyecto fue desarrollado con fines educativos y de aprendizaje. Todos los derechos sobre marcas, logotipos, imágenes y material multimedia pertenecen a **Rockstar Games** y **Take-Two Interactive**.

---

Hecho por [CODE ATD](https://codeatd.dev) siguiendo el directo de [midudev](https://midu.dev/).
