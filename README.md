# Mobblog Digital — sitio web

Paquete preparado para publicar el sitio estático de Mobblog Digital en GitHub Pages.

## Archivos incluidos
- `index.html`: página principal completa; sus recursos visuales y estilos están integrados en el HTML.
- `preview.jpg`: imagen para vistas previas al compartir el sitio.
- `robots.txt`: instrucciones básicas para rastreadores.
- `sitemap.xml`: mapa del sitio.
- `CNAME`: dominio personalizado `mobblogdigital.com`.
- `.nojekyll`: evita el procesamiento Jekyll de GitHub Pages.

## Publicar en GitHub Pages
1. Crea o abre el repositorio donde publicarás la web.
2. Sube **todos los archivos de esta carpeta a la raíz del repositorio**.
3. En GitHub, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
6. En **Custom domain**, confirma `mobblogdigital.com` si no aparece automáticamente.
7. Activa **Enforce HTTPS** cuando GitHub indique que el certificado está disponible.

## Dominio y DNS
El archivo `CNAME` declara `mobblogdigital.com`, pero no configura los DNS por sí solo. Configura en el proveedor del dominio los registros que GitHub Pages indique en Settings → Pages. No elimines registros de correo existentes (MX, SPF, DKIM o DMARC).

## Verificaciones después de publicar
- Abre `https://mobblogdigital.com/` y revisa escritorio y móvil.
- Comprueba `https://mobblogdigital.com/robots.txt` y `https://mobblogdigital.com/sitemap.xml`.
- Verifica el dominio en Google Search Console y envía el sitemap.
- Comprueba Google Analytics 4 en tiempo real. El ID incorporado es `G-8RCRHPBF27`.

## Integraciones incorporadas
- WhatsApp: `https://wa.me/51940156307`
- Blog: `https://mobblogdigital.blogspot.com/`
- YouTube: `https://youtube.com/@mobblogdigital`
- Google Analytics 4: `G-8RCRHPBF27`

**Importante:** este paquete contiene los archivos listos para subir. La publicación efectiva, la configuración DNS y la recepción de datos en Analytics se confirman después del despliegue.
