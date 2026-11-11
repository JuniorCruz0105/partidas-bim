# Guía de uso

## 1) Archivos del proyecto

- `index.html`: extensión principal para el visor 3D de Trimble Connect.
- `manifest.json`: manifiesto que GitHub Pages y Trimble Connect usan para localizar la extensión.
- `icon.svg`: icono del proyecto.
- `README.md`: descripción del repositorio.

## 2) Subir al repositorio

Si trabajas localmente:

```bash
git clone https://github.com/JuniorCruz0105/partidas-bim.git
cd partidas-bim
cp /ruta/al/index.html .
cp /ruta/al/manifest.json .
cp /ruta/al/icon.svg .
cp /ruta/al/GUIA.md .
git add .
git commit -m "Agregar extensión Partidas BIM"
git push origin main
```

También puedes cargar los archivos directamente desde GitHub en la pestaña `Add file`.

## 3) GitHub Pages

Una vez publicados los archivos, activa GitHub Pages en el repositorio y selecciona:

- Branch: `main`
- Folder: `/ (root)`

La URL final será:

```text
https://JuniorCruz0105.github.io/partidas-bim/manifest.json
```

## 4) Verificación

Abre la URL del manifiesto en el navegador para confirmar que sirve correctamente.
