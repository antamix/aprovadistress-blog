backend:
  name: git-gateway
  branch: main

media_folder: "images"
public_folder: "/images"

collections:
  - name: "posts"
    label: "Articoli"
    folder: "_posts"
    create: true
    slug: "{{year}}-{{month}}-{{day}}-{{slug}}"
    fields:
      - {label: "Titolo", name: "title", widget: "string"}
      - {label: "Categoria", name: "cat", widget: "string", default: "HRV"}
      - {label: "Sottotitolo", name: "subtitle", widget: "string", required: false}
      - {label: "Copertina", name: "cover", widget: "image", required: false}
      - {label: "Tempo lettura", name: "time", widget: "string", default: "4 min"}
      - {label: "Contenuto", name: "body", widget: "markdown"}
