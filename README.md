# NOVA MÓVIL

Abre `index.html` en un navegador para revisar la tienda. El botón de consulta abre WhatsApp en `+591 77254863` con el producto escrito automáticamente.

## Edición segura al publicar

Una página estática por sí sola no puede proteger un panel de administración: una contraseña puesta en el navegador sería visible para otras personas. Esta carpeta ya incluye Decap CMS. Para que solo tú edites de forma segura, publícala desde un repositorio de GitHub conectado a Netlify.

La opción más sencilla es Netlify + Decap CMS:

1. Crea una cuenta de GitHub y sube esta carpeta a un repositorio privado.
2. Crea una cuenta de Netlify y selecciona ese repositorio para publicar.
3. Activa **Identity** y **Git Gateway** en Netlify; invita únicamente tu correo como usuario.
4. Se añadirá una ruta `/admin`; allí editarás marcas, modelos, precios, cantidades, fotografías y fichas sin tocar código.
5. Define stock `0` para que el artículo diga “Agotado” y el botón de WhatsApp quede desactivado.

No compartas la contraseña ni la invitación de Netlify. Antes de publicar, reemplaza las fichas marcadas como “Pendiente de verificación” con la información oficial de tus equipos.
