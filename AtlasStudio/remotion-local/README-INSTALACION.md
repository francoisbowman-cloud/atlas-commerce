# Remotion en tu ordenador (Atlas Studio)

Esta carpeta es el mismo proyecto de Remotion que probé en mi entorno, pero limpio para correr en tu Windows. Aquí sí funcionará el navegador que Remotion necesita para renderizar (en mi entorno está bloqueado por seguridad).

## 1. Instalar Node.js (solo la primera vez)

Si no lo tienes: entra a [nodejs.org](https://nodejs.org), descarga la versión "LTS" e instálala como cualquier programa (Siguiente, Siguiente, Instalar).

Para comprobar que quedó instalado, abre la aplicación **Terminal** (o "Símbolo del sistema") y escribe:

```
node --version
```

Si te muestra un número de versión (ej. `v22.x.x`), quedó instalado correctamente.

## 2. Instalar las dependencias del proyecto

En la Terminal, entra a esta carpeta (ajusta la ruta si moviste el proyecto):

```
cd "C:\Users\user\Claude\Projects\Atlas E-Commerce\AtlasStudio\remotion-local"
npm install
```

Esto puede tardar unos minutos la primera vez. Va a descargar también un Chrome propio para renderizar (a diferencia de mi entorno, aquí no hay ninguna restricción para eso).

## 3. Ver el video en vivo (editor visual)

```
npm start
```

Esto abre una ventana del navegador con un editor donde puedes ver el video reproduciéndose y ajustar el código en `src/AtlasIntro.jsx` mientras ves los cambios en tiempo real.

## 4. Exportar el video final (.mp4)

```
npm run build
```

El archivo final queda en `out/atlas_intro.mp4`, dentro de esta misma carpeta.

## Cómo personalizarlo

Abre `src/AtlasIntro.jsx` con cualquier editor de texto (o con VS Code si lo tienes). Ahí puedes cambiar:

- `TITLE` y `SUBTITLE`: el texto que aparece.
- Los colores (`backgroundColor`, `color`): están en formato hexadecimal, ej. `#1F3A5F`.
- `durationInFrames` en `src/Root.jsx`: duración del video en fotogramas (a 30 fps, 120 fotogramas = 4 segundos).

Cuando quieras un video distinto (por ejemplo, un anuncio para un producto concreto de Etsy), la forma más simple es pedirme que te prepare un nuevo archivo `.jsx` con esa plantilla, y lo agregas a `src/Root.jsx` como una nueva `Composition`.
