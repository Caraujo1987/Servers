# Servers en AR

Visor web de realidad aumentada para el modelo 3D de servidores.

## Ejecutar localmente

```powershell
node dev-server.cjs
```

Abre `http://localhost:4173`.

## Compatibilidad

- Escritorio: previsualizacion 3D interactiva.
- Android compatible con ARCore: boton **Ver en mi espacio** mediante WebXR o Scene Viewer.
- iPhone/iPad: requiere un archivo USDZ del mismo modelo y declararlo con `ios-src` en `index.html`.

Para publicar en GitHub Pages, sube la rama `main` y en `Settings > Pages` selecciona `Deploy from a branch`, rama `main` y carpeta `/root`.
