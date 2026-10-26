# Escudo Móvil

App para el celular que funciona sin conexión y sin gastar tokens de IA. Nueve agentes locales:

| Agente | Qué hace |
|---|---|
| Coordinador | Escaneo completo con puntuación de salud y chat de ayuda sin conexión |
| Optimizador | Prueba de velocidad (red, latencia, CPU) y plan para acelerar el teléfono |
| Guardián antivirus | Analiza APK y archivos: doble extensión, archivos disfrazados, permisos peligrosos del APK, PDF con código, macros, huella SHA-256 y enlace a VirusTotal |
| Filtro anti-spam | Puntúa SMS, correos, enlaces y números (phishing, suplantación de marcas, números de pago, estafa del familiar) |
| Auditor de privacidad | Lista guiada para quitar permisos, administradores y apps maliciosas |
| Analista de contraseñas | Fuerza y tiempo de descifrado, búsqueda en filtraciones (k-anonimato, nunca se envía la clave) y generador de claves y frases |
| Escáner QR | Lee el QR desde una foto y revisa el enlace o la red Wi-Fi antes de abrirlo |
| Limpiador | Encuentra fotos y archivos duplicados y los más pesados |
| Ahorrador de tokens | Comprime prompts antes de enviarlos a Claude Code y ofrece plantillas cortas |

## Limitaciones

Android e iOS no permiten que una app borre otras apps ni lea sus archivos. Escudo Móvil detecta y te guía para eliminar; la desinstalación la haces tú desde Ajustes.

## Instalar en el teléfono

1. Publica la carpeta en GitHub Pages (Settings › Pages › rama y carpeta `/` del repo; la app queda en `.../escudo/`).
2. Abre la dirección en Chrome (Android) o Safari (iPhone).
3. Android: menú ⋮ › «Instalar app». iPhone: Compartir › «Añadir a pantalla de inicio».

En Android, al instalarla aparece en el menú «Compartir»: comparte un SMS o enlace sospechoso con Escudo y se analiza al instante. Tus ajustes se pueden pasar a otro teléfono desde Más › Copia de seguridad.

Después funciona sin internet (salvo la prueba de velocidad).
