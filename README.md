# Proyecto de Evaluación OCI-R

Este proyecto es una Single Page Application (SPA) para evaluar síntomas de TOC. 
Todo el código está contenido en `index.html`.

## Pasos para Desplegar en GitHub Pages

1. **Crear un Repositorio en GitHub**:
   - Ve a [github.com/new](https://github.com/new).
   - Nombre del repositorio: `ocir-evaluacion` (o el que prefieras).
   - Déjalo "Público" (para usar GitHub Pages gratis).
   - No marques "Add a README file" (ya los tenemos localmente).
   - Haz clic en "Create repository".

2. **Subir el Código**:
   Abre una terminal en esta carpeta y ejecuta:
   ```bash
   git remote add origin https://github.com/TU_USUARIO/ocir-evaluacion.git
   git branch -M main
   git push -u origin main
   ```
   *(Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub y `ocir-evaluacion` con el nombre de tu repositorio)*

3. **Activar GitHub Pages**:
   - Ve a la pestaña **Settings** de tu repositorio en GitHub.
   - En el menú lateral izquierdo, haz clic en **Pages**.
   - En "Source", selecciona `Deploy from a branch`.
   - En "Branch", selecciona `main` y la carpeta `/ (root)`.
   - Haz clic en **Save**.

4. **Obtener el Enlace**:
   - Espera unos minutos y refresca la página de Settings -> Pages.
   - Aparecerá un enlace como `https://tu-usuario.github.io/ocir-evaluacion/`.
   - ¡Ese es el enlace para enviar a tus pacientes!

## Notas
- El número de WhatsApp configurado es: `573216284300`.
- El umbral de análisis es: Score >= 21.
