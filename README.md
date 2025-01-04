# Maestría en CSS3: Flexbox, Grid, SASS, Bootstrap 5

Del curso de Udemy: `https://www.udemy.com/course/maestria-en-css3`

El orden del curso se puede ver en el nombre de las distintas carpetas.

En este README voy a dejar solo lo que vea más importante de entre todo el contenido del curso.

## Como centrar contenido

Ver los archivos:

`02-CSS3_Presentacion_y_estilos/71-CSS_Trick-Como_Centrar_un_Div`

`07-Flexbox/04-CSS_Trick-Como_Centrar_un_Div`

`12-CSS_Grid_Estructuras_Avanzadas/07-CSS_Trick-Como_Centrar_un_Div`.

## Practicar Flexbox

https://flexboxfroggy.com/#es

## Practicar Grid

https://cssgridgarden.com/#es

## Indicar un icono en la pestaña del navegador

Ver proyecto `14-Web_Productos_Apple`, archivo `index.html` donde aparece:

`<link rel="shortcut icon" href="img/icon.png" type="image/x-icon">`

## Cambiar el estilo del scroll

Ver proyecto `15-Sitio_Web_Corporativo`, archivo `styles.css` donde aparece:

```
body::-webkit-scrollbar {
  width: 8px;
}

body::-webkit-scrollbar-thumb {
  background: #F7CA37;
  border-radius: 50px;
}
```

## ¿Qué se necesita para aplicar Responsive Design?

Ver directorio `16-Responsive_Design`.

Las tres reglas esenciales son:

- Aplicar viewport
- Utilizar porcentajes en contenedores (cajas, header, section...)
- Aplicar Media Query

En Flexbox, hay que usar la propiedad `flex-wrap: wrap;` para que los elementos se ajusten al tamaño de la pantalla. Ver directorio `17-Practicas_Responsive_Design/01-Galeria_de_Imagenes_Responsive`.

En Grid Layout, para que los elementos sean responsive, no hay que usar nada especial, ya que es responsive por defecto. Es decir, usar `grid-template-columns` y `grid-template-rows`, pero, eso si, en los valores hay que usar `auto-fill` para poder acoplar los elementos al contenedor y `minmax` para indicar el tamaño mínimo y máximo.
Ver directorio `17-Practicas_Responsive_Design/03-Aplicando_Responsive_a_Nuestra_Galeria_Grid`.

Para aplicar media query cuando trabajamos con `grid-areas` ver directorio `17-Practicas_Responsive_Design/04-Aplicando_Responsive_a_Nuestras_App_Google_con_Masonry_Layout`.

## Modo oscuro

Ver directorio `16-Responsive_Design/04-Media_Query_Scheme_Para_Aplicar_Modo_Oscuro` para ver como trabajar con el tema del dispositivo.
