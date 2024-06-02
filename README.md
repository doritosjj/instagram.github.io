# Página de Inicio de Sesión de Instagram

Este es un mockup simple de la página de inicio de sesión de Instagram, que incluye un formulario de inicio de sesión y un sistema básico de envío de correo electrónico para capturar intentos de inicio de sesión.

## Estructura de Archivos

- `index.html`: Contiene el código HTML para la página de inicio de sesión.
- `send_email.php`: Script PHP para procesar y enviar correos electrónicos con los detalles del intento de inicio de sesión.

## Uso

1. Coloca los archivos `index.html` y `send_email.php` en tu servidor web.

2. Asegúrate de que el formulario HTML en `index.html` apunte al archivo PHP (`send_email.php`) en la acción del formulario.

3. Configura la dirección de correo electrónico del destinatario en la variable `$to` dentro del archivo PHP.

4. Personaliza el cuerpo del correo electrónico y los campos capturados según tus necesidades.

5. Asegúrate de que el servidor web tenga permisos para enviar correos electrónicos utilizando la función `mail()` de PHP.

## Advertencia

- Este es un ejemplo básico y no ofrece protección completa contra ataques de seguridad. Es importante implementar medidas adicionales según sea necesario para proteger tu aplicación.

## Créditos

- La imagen del logotipo de Instagram es propiedad de Instagram.
- Este proyecto es solo con fines educativos y de demostración.

---

¡Disfruta de tu página de inicio de sesión de Instagram!
