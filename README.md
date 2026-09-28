# Urban Greys Jeans — Catálogo online de jeans

🔗 **Demo:** [urbangreys-jeans.vercel.app](https://urbangreys-jeans.vercel.app)

Catálogo online para una tienda física de jeans push up. Las clientas pueden explorar modelos por categoría, elegir talla, armar su bolsa y enviar el pedido por WhatsApp. La tienda administra productos y fotos desde un panel web.

> Proyecto desarrollado en equipo por **Benjamin Canales** y **[Bryan Piña](https://github.com/Bemol69)**. Participé en el diseño y el desarrollo de funcionalidades.

## ✨ Funcionalidades

- **Catálogo con filtros** por categoría (skinny, cargo, con faja, accesorios).
- **Ficha de producto** con galería de imágenes y selector de tallas.
- **Bolsa de compras** persistente con cálculo de total en pesos chilenos.
- **Checkout por WhatsApp** con opción de retiro en tienda o despacho a todo Chile.
- **SEO local** para búsquedas en la ciudad de la tienda.
- **Panel de administración (/admin)** con Sveltia CMS para gestionar productos, categorías y fotos.

## 🏗️ Arquitectura

- Sitio estático en **JavaScript vanilla** con productos en archivos JSON.
- **Build en Node.js** (`scripts/build.mjs`) que arma el catálogo y genera canonical, Open Graph, datos estructurados, `sitemap.xml` y `robots.txt`.
- **Publicación continua en Vercel** desde GitHub.

## 🛠️ Tecnologías

JavaScript · HTML5 · CSS3 · Node.js · Sveltia CMS · GitHub · Vercel

## 🚀 Ejecutar localmente

```bash
node scripts/build.mjs
npx serve dist
```
