# Políticas de Seguridad - CatálogoPro

## 1. Validación de Entrada de Datos
- Formulario de inicio de sesión con campos obligatorios para prevenir campos vacíos.
- Confirmación obligatoria de contraseña en el registro para evitar errores tipográficos.
- Ocultación de contraseña en pantalla mediante la propiedad `secureTextEntry`.

## 2. Gestión de Sesión y Privacidad Local
- Al presionar **Cerrar Sesión**, el sistema limpia las variables de estado (`correo`, `password`, `usuario`) y vacía el carrito actual por seguridad.
- Control de permisos en pantalla de ajustes mediante un control de notificaciones (`Switch`).