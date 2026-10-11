# Perfil de Lumeris

El README y assets se suben a un repositorio publico llamado Lumeris-SP, dentro de la cuenta Lumeris-SP. README.md debe quedar en la raiz del repositorio.

Extrae el ZIP y abre la carpeta Lumeris-SP. Si el repositorio remoto esta vacio:

```powershell
git init -b main
git add .
git commit -m "Agrega perfil de Lumeris"
git remote add origin https://github.com/Lumeris-SP/Lumeris-SP.git
git push -u origin main
```

Si GitHub ya tiene un commit inicial, detente y revisa antes de volver a subir. No uses --force.

Para regenerar los banners:

```powershell
python -m pip install -r scripts/banner/requirements.txt
python scripts/banner/generate.py
```

El generador usa la foto original y un recorte definido en portrait_points. Los colores se definen en THEMES y el texto en YAML_ROWS. Los simbolos animados son una grafica y un engranaje originales, no logos oficiales. Las tarjetas de herramientas son ilustraciones propias.

No hay contadores de visitas ni radares. No se han inventado proyectos, certificaciones o niveles de dominio. La seccion de intereses se puede ajustar a los de Lumeris.

