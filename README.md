# Piedras Angulares

## Introducción

Os presento mi versión de **"Piedras Angulares"**, 
primer proyecto del Bootcamp y también mi primer repositorio en GitHub.

Es una web hecha con HTML semántico y CSS que rinde homenaje a mujeres pioneras en la ciencia oceánica.

Las he elegido porque me fascina el mundo marino y crear una coherencia temática que ayuda al diseño.

He querido que fuera sencilla e intuitiva, para que cualquier persona pueda navegar fácilmente.

Primero conocemos a las protagonistas y luego navegamos — nunca mejor dicho — por la web.

---

## Protagonistas

He seleccionado 4 mujeres invisibilizadas, esenciales y que **no fueron reconocidas en su momento**:

**🐙 Maude Delap**  
Descubrió el ciclo completo de vida de las medusas criándolas en cautiverio. Por ser mujer y autodidacta, fue excluida de instituciones académicas y nunca tuvo un cargo formal.

**⚓ Honor Frost**  
Primera persona en realizar excavaciones arqueológicas científicas bajo el agua, revolucionando el estudio de restos submarinos. Su liderazgo fue minimizado por ser mujer autodidacta.

**⭐ Irene Bernasconi**  
Zoóloga argentina que lideró una expedición a la Antártida en 1968 estudiando estrellas de mar en condiciones extremas. Su rol fue ignorado por prejuicios de género y edad.

**🌊 Roberta Eike**  
Oceanógrafa y geóloga marina estadounidense que desafió las normas embarcándose en secreto en una expedición oceanográfica en una época en que las mujeres no podían participar oficialmente.

---

## Diseño visual

Utilicé una paleta de azules suaves y blancos con fondos texturizados, con imágenes libres de Unsplash para crear una atmósfera marítima envolvente.

El fondo del `<nav>` simula la superficie del agua, dando la sensación de que te sumerges al entrar en la web. Luego, al bajar por el contenido del `<body>`, el efecto de la imagen de agua continúa, como si navegases bajo el mar.

El `<footer>` tiene un azul más oscuro que recuerda a las profundidades marinas, cerrando la experiencia visual y reforzando la ambientación oceánica.

La tipografía principal es **Cinzel**, obtenida de Google Fonts, que aporta un aire clásico y elegante al título.

---

## Uso de Grid

El diseño utiliza CSS Grid para organizar las tarjetas en dos columnas en escritorio, ofreciendo una sensación limpia y ordenada.

Con media queries, para pantallas menores a 768px, las tarjetas pasan a una columna única para mejorar la lectura en móvil.

---

## Tarjetas

Cada tarjeta muestra dos imágenes: una de acción y otra más formal, para conectar mejor con la historia de cada científica.

Incluyo un emoji relacionado con cada protagonista para darle un toque visual acorde a cada una.

El marco blanco de las tarjetas ayuda a que las imágenes respiren y destaquen.

---

## Interactividad

Las tarjetas giran con un efecto de rotación 3D (`transform: rotateY(180deg)`) al pasar el ratón por encima, con una transición suave y dinámica.

Para el reverso de las tarjetas, que puede tener textos largos, se usa `overflow-y: auto` con scroll personalizado para no perder contenido ni desbordar el contenedor.

---

## Diseño responsivo

En pantallas pequeñas:

- Las tarjetas pasan a una columna única.  
- Se ajustan tamaños y anchos para facilitar la lectura.

---

## Estructura HTML

- `<header>` contiene un `<nav>` con el título principal "PIEDRAS ANGULARES".  
- `<main>` está dividido en dos secciones:  
  1. `.main-subtitle`: Introducción y cita inspiradora.  
  2. `.cards-container`: Contenedor con 4 tarjetas, una para cada científica.  
- Cada tarjeta (`<article class="card">`) tiene una parte frontal con imagen y título, y una parte trasera con info extra y biografía resumida.  
- `<footer>` incluye el origen del proyecto (primer trabajo del Bootcamp FemCoders-4), el aviso de derechos de autor, el logo del proyecto y los datos de contacto para que puedas conectar fácilmente.

---

## Cierre

Con este proyecto he combinado código, diseño y memoria histórica.

El objetivo era conseguir un sitio funcional, estético y educativo solo con HTML y CSS.

**Piedras Angulares** es mi forma de mostrar que programar también es contar historias.


---

## Estructura de carpetas del proyecto

```piedras-angulares/
├── index.html
├── styles.css
├── files/
│   ├── image1.png
│   ├── image2.png
│   ├── logo.png
│   └── ...
└── README.md```


---

## Sobre las imágenes utilizadas

Por motivos de derechos de imagen y con fines educativos, las fotos originales tenían baja resolución o restricciones. Por eso, he generado imágenes a partir de ellas con inteligencia artificial, respetando siempre la identidad y dignidad de las protagonistas.

Las imágenes de fondo usadas en `<nav>` y `<body>` son libres y obtenidas de [Unsplash](https://unsplash.com).

---

## Logo

Al final del README puedes incluir tu logo personal con:

```md
![Logo de Aday](./logo.png)
