# Potosí 1945 — Proyecto listo para correr

## Contenido
Carpeta con HTML, SCSS, CSS compilado y placeholders de imágenes. Diseño igual a la imagen solicitada (colores, tarjetas, tipografía serif del sistema).

## Requisitos (opcionales para compilar SASS)
- Node.js instalado (opcional si solo abres `index.html`)
- Para compilar SASS localmente:
  ```bash
  npm install -g sass
  npx sass --watch scss/style.scss:css/style.css
  ```

## Estructura
```
potosi1945/
├── index.html
├── scss/
│   ├── style.scss
│   ├── _variables.scss
│   ├── _layout.scss
│   ├── _components.scss
│   └── _responsive.scss
├── css/
│   └── style.css
├── img/
│   ├── potosi1.svg
│   ├── potosi2.svg
│   └── potosi3.svg
└── README.md
```

## Ejecutar
1. Abre `index.html` en tu navegador.
2. (Opcional) Ejecuta el comando para compilar SASS si haces cambios en SCSS.

---
He incluido CSS ya compilado para que puedas abrir `index.html` inmediatamente sin instalar nada.
