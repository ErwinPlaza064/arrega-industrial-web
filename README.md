# Arrega Industrial · Maqueta del sitio

Maqueta HTML de un solo archivo (`index.html`) del rediseño de arregaindustrial.com. Se abre directo en el navegador, sin compilar.

## Páginas (rutas por hash)
- `#/` Inicio (servicios, proceso, industrias, acreditación, catálogo, recursos, cierre)
- `#/productos` Catálogo con filtros, vistas, ficha rápida y cotización múltiple
- `#/contacto` Formulario y datos de contacto
- `#/acceso` Acceso a clientes (solo diseño, no se conecta al portal)

## Notas
- Versión H: video en el héroe (motion graphic de muestra incrustado, reemplazar por video real), sección "cine" a pantalla completa, frase que se ilumina al hacer scroll, revelados, contadores, zoom de fotos y parallax. Respeta `prefers-reduced-motion`.
- Estilo claro: blanco, arena y ámbar `#F8A826`; Plus Jakarta Sans y Hanken Grotesk.
- Fotos de referencia incrustadas en base64 (tomadas del sitio actual); se reemplazan con fotos propias.
- Datos marcados "por confirmar" (teléfono, WhatsApp, certificado ANAB, cifras) y testimonios son de ejemplo.
- Productos del catálogo de ejemplo; en el sitio real vendrán de la base de datos / panel de administración.
- Destino previsto: Laravel + Inertia/React + MUI, con panel Filament.
