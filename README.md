# Plantilla de documentación técnica

Base mínima con MkDocs Material y despliegue mediante GitHub Pages.

## Usar la plantilla

1. Selecciona **Use this template**.
2. Actualiza `site_name`, `site_description` y la navegación en `mkdocs.yml`.
3. Reemplaza las páginas de ejemplo y añade referencias reproducibles.
4. En **Settings → Pages**, selecciona GitHub Actions como fuente si GitHub no
   la habilita automáticamente después del primer workflow.

## Desarrollo local

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
mkdocs serve
mkdocs build --strict
```

Consulta las [normas de MC-Andes](https://github.com/MC-Andes/standards).
