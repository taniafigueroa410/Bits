# Bits

App web para iPhone. Registra:

- calorías por comida (desayuno, comida, cena, snack)
- entrenamiento: gym, funcional y cardio
- agua, en botellas Owala de 32 oz
- pasos
- peso

Calcula tu plan a partir de tu peso meta y tu fecha, y analiza tu avance. Una vez instalada en el iPhone funciona sin internet.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | Toda la app (diseño y lógica) |
| `manifest.webmanifest` | Nombre e icono al instalarla |
| `sw.js` | Permite usarla sin internet |
| `icon-180.png`, `icon-192.png`, `icon-512.png` | Iconos |

## Publicar o actualizar en GitHub Pages

1. Entra a tu repositorio en GitHub, toca **Add file → Upload files** y arrastra los 6 archivos. Si ya existen, se reemplazan.
2. Toca **Commit changes**. En 1 o 2 minutos se actualiza tu enlace.

Si cambias el código, sube también `sw.js` con el número de versión aumentado (`bits-v3` → `bits-v4`).

## Instalarla en el iPhone

1. Abre el enlace en **Safari**.
2. Toca **Compartir → Agregar a pantalla de inicio → Agregar**.
3. Ábrela siempre desde ese icono. En iOS la app instalada guarda sus datos aparte de Safari.

Para que aparezca un icono nuevo hay que borrar el icono anterior de la pantalla de inicio y volver a agregarla. Si ya tenías registros, primero ve a **Perfil → Exportar copia**, y después del cambio usa **Importar copia**.

## Pasos y Huawei Health

Huawei Health no permite que una app web lea tus pasos, así que se escriben a mano en **Hoy → Pasos**.

## Respaldos

En **Perfil → Exportar copia** se genera un archivo `.json` que puedes guardar en Archivos o iCloud. Con **Importar copia** lo recuperas en otro teléfono.
