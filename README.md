# Portal MkDocs — MongoDB y MySQL

## Requisitos
Python 3.9 o superior, pip y acceso a internet para instalar dependencias.

## Ejecutar en Ubuntu

```bash
cd Portal_Documentacion_Bases_de_Datos
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Abre http://127.0.0.1:8000 en el navegador. Detén el servidor con Ctrl+C.

## Generar sitio estático

```bash
mkdocs build
```

Se crea la carpeta `site/`. Para publicar en GitHub Pages, crea un repositorio GitHub y, con git configurado y permisos sobre el repositorio, ejecuta `mkdocs gh-deploy`.

## Editar contenido

- `docs/index.md`: página inicial.
- `docs/mongodb.md`: instructivo de MongoDB.
- `docs/mysql.md`: instructivo de MySQL.
- `docs/assets/`: imágenes incorporadas.
- `mkdocs.yml`: menú, tema y configuración.

Las imágenes y los textos proceden de los dos instructivos Word elaborados previamente. Revisa los comandos y requisitos en tu versión específica de Ubuntu antes de ejecutarlos.
