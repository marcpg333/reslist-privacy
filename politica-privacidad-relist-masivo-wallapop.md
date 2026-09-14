# Política de Privacidad — Relist Masivo para Wallapop

**Última actualización:** 14 de septiembre de 2026

Esta Política de Privacidad describe cómo la extensión de Chrome **"Relist Masivo para Wallapop"** ("la Extensión", "nosotros") trata la información del usuario al utilizar la Extensión.

## 1. Responsable

- **Nombre del desarrollador/marca:** Relist tools
- **Contacto:** legatos_amatory.0q@icloud.com
- **Sitio web:** 

## 2. Finalidad única de la Extensión

La Extensión tiene un único propósito: permitir a los usuarios republicar de forma masiva sus propios anuncios activos en Wallapop (wallapop.com), automatizando la acción de "republicar" que normalmente se realiza manualmente anuncio por anuncio, para mejorar la visibilidad de sus productos en los resultados de búsqueda.

La Extensión **no** está afiliada, patrocinada ni respaldada oficialmente por Wallapop ni por Adevinta.

## 3. Datos que se recopilan y cómo se usan

| Dato | Finalidad | ¿Dónde se almacena? |
|---|---|---|
| Lista de anuncios activos del usuario (título, ID, estado) | Mostrar al usuario qué anuncios puede seleccionar para republicar | Localmente, en el propio navegador (`chrome.storage`) |
| Selección de anuncios y configuración de programación (frecuencia, horarios) | Ejecutar la republicación automática según las preferencias del usuario | Localmente, en el propio navegador |
| Estado de la última ejecución / historial de relists | Mostrar al usuario el resultado de cada republicación | Localmente, en el propio navegador |
| [Si aplica] Estado de suscripción (plan Gratis / Pro) | Activar o desactivar funcionalidades según el plan contratado | [Localmente + sincronizado con nuestro servidor en api.tudominio.com, si tienes backend de pagos] |

La Extensión **no recopila ni almacena**:
- Contraseñas ni credenciales de acceso a Wallapop (la Extensión opera sobre la sesión ya iniciada por el usuario en su propio navegador).
- Datos de pago (los pagos, si existen, se gestionan a través de un proveedor externo como Stripe/Paddle/LemonSqueezy, que tiene su propia política de privacidad).
- Historial de navegación fuera de wallapop.com.

## 4. Permisos solicitados y su justificación

- **`storage`** — Guardar localmente la configuración del usuario (anuncios seleccionados, frecuencia de republicación, estado de la última ejecución).
- **`alarms`** — Programar la ejecución automática de la republicación en los intervalos definidos por el usuario, sin necesidad de mantener la Extensión abierta en el momento exacto.
- **`scripting`** — Inyectar código en las páginas de wallapop.com para localizar y ejecutar la acción de "republicar" de cada anuncio del usuario.
- **Permiso de host (`wallapop.com`)** — Necesario porque es el único sitio donde la Extensión opera; no se solicita acceso a ningún otro dominio.

## 5. Código remoto

[Elige la versión que corresponda a tu caso real:]

> **Si no usas código remoto:** La Extensión no ejecuta código remoto. Todo el código JavaScript forma parte del paquete revisado y publicado en el Chrome Web Store.

> **Si verificas suscripciones vía API:** La Extensión realiza llamadas remotas únicamente a [tu API] para verificar el estado de la suscripción del usuario. No se ejecuta código JavaScript de terceros; solo se reciben datos (JSON) que activan o desactivan funcionalidades ya incluidas en el paquete de la Extensión.

## 6. Compartición de datos con terceros

No vendemos, alquilamos ni compartimos los datos del usuario con terceros para fines publicitarios ni de ningún otro tipo ajeno al funcionamiento descrito en esta política. [Si usas un proveedor de pagos, añade:] Únicamente se comparte la información estrictamente necesaria con [Stripe/Paddle/LemonSqueezy] para procesar pagos, conforme a su propia política de privacidad.

## 7. Conservación y eliminación de datos

Los datos almacenados localmente permanecen en el navegador del usuario mientras la Extensión esté instalada. El usuario puede eliminarlos en cualquier momento:
- Desinstalando la Extensión desde `chrome://extensions`.
- O borrando manualmente los datos de la Extensión desde la configuración de Chrome (Configuración → Privacidad y seguridad → Configuración del sitio → Ver permisos y datos almacenados en todos los sitios).

## 8. Seguridad

Adoptamos medidas razonables para proteger la información gestionada por la Extensión. No obstante, ningún sistema es completamente infalible, por lo que no podemos garantizar una seguridad absoluta.

## 9. Menores de edad

La Extensión no está dirigida a menores de edad y no recopila conscientemente información de menores.

## 10. Cambios en esta política

Podemos actualizar esta Política de Privacidad ocasionalmente. Cualquier cambio se reflejará en esta misma página, actualizando la fecha de "Última actualización".

## 11. Contacto

Para cualquier duda sobre esta Política de Privacidad o sobre el tratamiento de tus datos, puedes escribirnos a: **legatos_amatory.0q@icloud.com**
