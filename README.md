# 🛒 Catálogo de Productos con Astro y DummyJSON

Este proyecto es una aplicación web construida con Astro que consume una API REST externa (`DummyJSON`), procesa los datos JSON en el servidor y presenta los productos mediante un diseño en cuadrícula (CSS Grid) responsivo y un buscador interactivo del lado del cliente.

## 📌 API Utilizada
- **Endpoint:** `https://dummyjson.com/products?limit=12`
- **Formato:** JSON
- **Propiedades renderizadas:** `title`, `price`, `category`, `rating`, `thumbnail`.

## 🛠️ Tecnologías Utilizadas
- **Astro** (Generación de páginas y arquitectura basada en componentes)
- **TypeScript** (Tipado e interfaces de la API)
- **CSS Grid & Flexbox** (Diseño responsivo sin desbordamientos)
- **JavaScript ES6+** (Filtrado DOM dinámico)

## 🚀 Pasos para Ejecutar el Proyecto Localmente

1. **Clonar el repositorio:**
   ```bash
   git clone <URL_DE_TU_REPOSITO_EN_GITHUB>
   cd catalogo-api