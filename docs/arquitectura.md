# Arquitectura del Sistema - CatálogoPro

## 1. Estructura de la Aplicación
CatálogoPro es una aplicación móvil construida bajo la arquitectura **Component-Based** con React Native. La navegación y el manejo de datos se gestionan mediante estados principales (`useState`).

## 2. Componentes Clave
- **Estado de Pantalla (`pantalla`):** Controla la navegación condicional (`login`, `registro`, `home`, `catalogo`, `detalle`, `carrito`, `confirmacion`, `compraExitosa`, `movimientos`, `perfil`, `ajustes`).
- **Carrito de Compras (`carrito`):** Mantiene en memoria los artículos agregados, con soporte para incremento/decremento de stock simulado.
- **Historial de Actividad (`movimientos`):** Registra cronológicamente cada acción relevante realizada por el usuario dentro de la app.