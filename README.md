# Patrimonio — app

App del celular. Son 4 archivos estáticos: `index.html`, `manifest.webmanifest`, `icon-192.png` e `icon-512.png`. No contienen datos ni claves: todo viene de la planilla privada.

## Publicar en GitHub Pages

1. Crear un repositorio (puede ser público: no hay nada sensible adentro) y subir los 4 archivos.
2. **Settings → Pages → Deploy from a branch → main / root**. En un minuto queda en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.
3. Probar primero con **Ver con datos de ejemplo**, sin conectar nada.

Nunca subir al repo la dirección de la aplicación web junto con la clave.

## Instalar en el celular de Javier

1. Abrir el link en Safari (iPhone) o Chrome (Android).
2. iPhone: **Compartir → Agregar a inicio**. Android: **menú ⋮ → Agregar a la pantalla principal**.
3. Abrir desde el ícono, pegar la dirección de la aplicación web y la clave (hoja Config → CLAVE_API).
4. Activar Face ID / huella o un PIN.

## Qué guarda el celular

La dirección, la clave y la última foto del patrimonio (para abrir al instante). El bloqueo con Face ID, huella o PIN es local: protege el acceso en ese dispositivo. Si se pierde el celular, cambiar CLAVE_API en la planilla y ese dispositivo queda sin acceso.

## Asistente

El botón del asistente está reservado en el código (`ASISTENTE_ACTIVO = false`). El texto bajo "Efecto dólar" en la pantalla Hoy es donde irá su comentario del día.
