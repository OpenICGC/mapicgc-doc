<p >
<img src="docs/assets/cartography2.png" alt="Esquema" height="120px">
<img src="docs/assets/ICGC_color.svg" alt="ICGC" height="100px">
</p>


# mapicgc-doc

### Instal.lar eines de documentació 💿

- Instal.lar Python i pip
- Obrir PowerShell com administrador

```bash
pip install mkdocs-material
```

### Comandes mkdocs ✨

- `mkdocs serve`: Arranca un servidor web intern amb auto-recàrrega.

  http://localhost:8000/

- `mkdocs build`: Compila la documentació en html.
- `mkdocs gh-deploy`: Publica la documentació a branch gh-pages.

### Editar contingut ✎

- Per modificar qualsevol pàgina, cal editar el contingut dels fitxers `.md` de la carpeta `docs`.
- Si es vol afegir una nova secció o pàgina, cal generar el fitxer `.md` corresponent.
- Si es vol editar o modificar la barra de navegació, cal actualitzar la secció `nav` del fitxer `mkdocs.yml`.
- Per afegir una nova secció dins una pàgina (i que aquesta aparegui a la Taula de continguts), s'ha de referenciar de la següent manera: `#### NomSecció`.
- Per afegir un enllaç a una secció: `[Titol secció](document.md)`.

### Pujar documentació al web ⏫

- Compilar la documentació (`mkdocs build` o `python -m mkdocs build`)
- Copiar el contingut de la carpeta `site` al servidor corresponent.
