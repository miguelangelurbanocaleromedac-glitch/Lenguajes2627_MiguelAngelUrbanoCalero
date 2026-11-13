# WEBLAB · Proyecto final de Lenguajes de Marcas

Sitio web estático realizado con HTML5 y CSS3. Contiene una página de inicio y una página independiente para cada uno de los temas 1–9 del temario facilitado.

## Cómo abrir la web

1. Descarga y descomprime el ZIP.
2. Abre la carpeta `WEBLAB` en Visual Studio Code.
3. Abre `index.html` en el navegador. También puedes utilizar la extensión Live Server.
4. Para revisar una unidad, entra desde las tarjetas del inicio o desde el menú de navegación de la izquierda.

## Estructura de carpetas

```text
WEBLAB/
├── index.html
├── tema1.html
├── tema2.html
├── tema3.html
├── tema4.html
├── tema5.html
├── tema6.html
├── tema7.html
├── tema8.html
├── tema9.html
├── css/
│   └── style.css
└── README.md
```

## Tecnologías utilizadas

- HTML5: estructura semántica, enlaces, tablas, formularios y ejemplos de código.
- CSS3: diseño visual, rejillas, flexbox, efectos, estados hover y media queries.
- No necesita base de datos, servidor ni dependencias externas para visualizar el contenido.

## Git y GitHub

Desde la terminal de Visual Studio Code, dentro de la carpeta del proyecto:

```bash
git init
git add .
git commit -m "Version inicial del proyecto WEBLAB"
```

Después crea un repositorio vacío en GitHub y enlázalo con la dirección que te proporcione GitHub:

```bash
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

Para guardar nuevas versiones:

```bash
git add .
git commit -m "Actualizo contenidos y estilos"
git push
```

Sustituye `TU-USUARIO` y `TU-REPOSITORIO` por los datos del repositorio que hayas creado. No subas contraseñas ni datos privados.

## Antes de entregar

- Comprueba que `index.html` abre correctamente.
- Entra en los nueve temas y revisa los enlaces anterior/siguiente.
- Cambia el tamaño de la ventana para comprobar el diseño adaptable.
- Revisa que los títulos, textos y ejemplos estén escritos correctamente.
- Haz al menos un commit en Git y comprueba que el repositorio de GitHub contiene los archivos.

## Fuente del contenido

Contenidos basados en los PDF facilitados de **Lenguajes de Marcas y Sistemas de Gestión de Información, temas 1 a 9**. La explicación y los ejemplos de esta web se han reorganizado y redactado de forma resumida para el proyecto.
