# Proyecto tipo e-commerce del curso práctico de frontend developer de Platzi.

## Diseño

En el siguiente [link del diseño](https://scene.zeplin.io/project/60afeeed20af1378ed046538) están las vistas del proyecto para la maquetación.

## Prototipos

En el siguiente [link de prototipo mobile](https://www.figma.com/proto/bcEVujIzJj5PNIWwF9pP2w/Platzi_YardSale?node-id=0%3A684&amp%3Bscaling=scale-down&amp%3Bpage-id=0%3A1&amp%3Bstarting-point-node-id=0%3A719) se puede ver el diseño de forma interactiva para la vista mobile.

En el siguiente [link de prototipo desktop](https://www.figma.com/proto/bcEVujIzJj5PNIWwF9pP2w/Platzi_YardSale?node-id=3%3A1308&amp%3Bscaling=scale-down&amp%3Bpage-id=0%3A998&amp%3Bstarting-point-node-id=5%3A2808) se puede ver el diseño de forma interactiva para la vista desktop.

## Maquetación

- Creo un archivo index.html con su estructura básica

<details>
<summary>Click para ver el código</summary>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
</details>

- Creo una carpeta assets que incluye las carpetas css e img respectivamente. En la carpeta img creo las carpetas icons y logos y paso allí las imágenes del proyecto que se encuentran en el [repositorio](https://github.com/platzi/curso-frontend-developer-practico). Y en la carpeta css creo el archivo de estilos styles.css

- Edito el <head> cambiando el título por Yard Sale y agrego los links de la fuente Quicksand importada de Google Fonts, y también agrego el link a la hoja de estilos propia.

<details>
<summary>Click para ver el código</summary>
``` html

<title>Yard Sale</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="assets/css/styles.css">
```
</details>

- En el archivo de estilos styles.css creo las variables de colores que voy a utilizar y agrego la fuente Quicksand al body.

<details>
<summary>Click para ver el código</summary>
``` css

:root {
    --white: #ffffff;
    --black: #000000;
    --very-light-pink: #c7c7c7;
    --text-input-field: #f7f7f7;
    --hospital-green: #acd9b2;
}

body {
    font-family: 'Quicksand', sans-serif;
}
```
</details>

