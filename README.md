# Servers en AR

Visor web de realidad aumentada para el modelo 3D de servidores.

El modelo se publica al 11.55% de la escala del archivo fuente para una colocacion inicial mas manejable en realidad aumentada.

## Ejecutar localmente

```powershell
node dev-server.cjs
```

Abre `http://localhost:4173`.

## Compatibilidad

- Escritorio: previsualizacion 3D interactiva.
- Android compatible con ARCore: boton **Ver en mi espacio** mediante WebXR o Scene Viewer.
- iPhone/iPad: Quick Look usa `SERVERS.usdz`, ya conectado mediante `ios-src`.

Para publicar en GitHub Pages, sube la rama `main` y en `Settings > Pages` selecciona `Deploy from a branch`, rama `main` y carpeta `/root`.
