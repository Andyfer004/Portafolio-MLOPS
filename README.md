# Portafolio MLOps

Sitio web estático para presentar proyectos, laboratorios, casos de estudio y talleres relacionados con MLOps.

## Páginas

- Inicio
- Proyectos
- Laboratorios
- Casos de estudio
- Talleres

## Desarrollo local

Puedes abrir `index.html` directamente o levantar un servidor local:

```bash
python3 -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Publicación con GitHub Pages

El workflow `.github/workflows/pages.yml` publica el sitio automáticamente al hacer push a `main`.

En GitHub, abre **Settings → Pages → Build and deployment → Source**, selecciona **GitHub Actions** y guarda. Después de subir los cambios, revisa la ejecución en la pestaña **Actions**.
