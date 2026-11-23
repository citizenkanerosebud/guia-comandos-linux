# Guía de comandos GNU/Linux

Aplicación web de un solo archivo (HTML + CSS + JS, sin dependencias) que explica comandos de GNU/Linux en tres niveles (básicos, intermedios y avanzados) más un anexo de red y administración del sistema. Cada comando incluye una explicación y 3 ejemplos copiables.

- Básicos: válidos en cualquier distribución.
- Intermedios, avanzados y anexo: orientados a Debian, Ubuntu y Fedora (y sus equivalentes de servidor).

## Uso

Abre `index.html` en el navegador: https://citizenkanerosebud.github.io/guia-comandos-linux/.. No requiere servidor ni instalación.

## Añadir comandos

Edita el array `D` dentro de `index.html`. Cada comando tiene este formato:

```js
['nombre','Explicación.',[['ejemplo 1','nota'],['ejemplo 2','nota'],['ejemplo 3','nota']]]
```

Un cuarto elemento opcional en un ejemplo (`'Debian/Ubuntu'`) muestra una etiqueta de distribución.

## Licencia

MIT
