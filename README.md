# Regalo para la Dra. Ari 🎓📚

Página estática de un solo uso (`index.html`, sin build).

## Publicar en GitHub Pages

1. Crear un repo nuevo en GitHub (p. ej. `regalo-ari`).
2. Desde esta carpeta:
   ```bash
   git init -b main
   git add .
   git commit -m "Regalo Dra. Ari"
   git remote add origin https://github.com/<usuario>/regalo-ari.git
   git push -u origin main
   ```
3. En el repo: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
4. En 1-2 minutos queda en `https://<usuario>.github.io/regalo-ari/`.

## Notas

- La elección queda guardada en el navegador (localStorage). Para resetearla: botón
  "quiero cambiar de modo" debajo del vale.
- Los pasos del slider (libros/tiempo) están en el array `STEPS` del `<script>`.
- Lleva `noindex` para que no aparezca en buscadores.
