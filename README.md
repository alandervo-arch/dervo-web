# Alquileres Dervo — sitio en Astro

## Requisitos
- Node.js 18.20.8+ o 20.3.0+ (LTS recomendado)

## Instalación

```bash
npm install
```

## Desarrollo

```bash
npm run dev
```

Abre `http://localhost:4321`.

## Build de producción

```bash
npm run build
npm run preview
```

## Estructura

- `src/pages/` — una ruta real por página: `/` (inicio), `/planes`, `/ablandadores`, `/contacto`.
- `src/components/` — Nav, Footer, botón de WhatsApp flotante y botón de volver, compartidos entre páginas.
- `src/layouts/Layout.astro` — head, nav y whatsapp fab comunes a todas las páginas.
- `src/styles/global.css` — estilos globales (variables de color, tipografía, layout).
- `src/assets/dispenser.png` — foto del dispenser, optimizada automáticamente por Astro.
