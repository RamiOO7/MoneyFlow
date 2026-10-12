# 💰 MoneyFlow

App de gestión de dinero, sencilla y bonita. Controla tus ingresos y gastos desde el móvil o el ordenador, sin registro y sin internet.

## Características

- Balance total con resumen de ingresos y gastos
- Añadir movimientos con cantidad, descripción, categoría y fecha
- Gastos por categoría con barras de porcentaje
- Filtros: Todo, Ingresos y Gastos
- Borrado de movimientos con confirmación
- Modo claro y oscuro (automático o manual)
- Funciona en iOS, Android y PC
- Tus datos se guardan en tu dispositivo, no se envían a ningún sitio

## Uso

1. Abre `index.html` en cualquier navegador.
2. Pulsa **+** para añadir un gasto o un ingreso.
3. Consulta el balance y las categorías en la pantalla principal.

> Los datos se guardan en el navegador. Si borras los datos del sitio, se pierden.

## Instalar como app

Abre la página web publicada en GitHub Pages y pulsa **Instalar app** en el menú del navegador (Chrome o Edge). En iPhone: Compartir → *Añadir a pantalla de inicio*. Una vez instalada funciona sin internet.

Archivos necesarios en el repositorio: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` e `icon-maskable-512.png`.

## Crear el .exe (Windows)

Con el proyecto `dinero-exe.zip`:

```bash
npm install
npm run build
```

El instalador aparece en la carpeta `salida`.

## Licencia

MIT. El texto completo está incluido al principio de `index.html` y en el archivo `LICENSE` del proyecto.
