# Plan de formación en IA

Sitio estático en español para una ruta práctica de ocho semanas, desde fundamentos y prompting hasta skills, agentes y evaluación. Incluye cuestionarios interactivos por semana.

## Vista local

Abre `index.html` directamente en un navegador. El progreso semanal se guarda en el almacenamiento local de ese navegador.

## Publicar en GitHub Pages

1. Crea un repositorio vacío en GitHub, por ejemplo `plan-formacion-ia`.
2. Desde esta carpeta, inicializa Git y sube los archivos:

   ```bash
   git init
   git add index.html README.md .nojekyll
   git commit -m "Crear itinerario de formación en IA"
   git branch -M main
   git remote add origin https://github.com/USUARIO/plan-formacion-ia.git
   git push -u origin main
   ```

3. En GitHub, abre **Settings → Pages** y selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Guarda los cambios. GitHub mostrará la URL del sitio en esa página.

No se ha creado ni publicado un repositorio remoto; este directorio queda listo para conectarlo al repositorio que elijas.
