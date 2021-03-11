# EDanimate

Es una librería de animaciones empaquetadas en mixins de Sass. Esta inspirada en animate.css y es parte del curso [CSS Avanzado Animaciones de EDteam](https://ed.team/css-animaciones).

## ¿Cómo usarlo?

Puedes usar EDanimate con CSS o con Sass (recomendable).

### Con CSS
* Descarga el archivo `public/css/style.css` e inclúyelo en tu proyecto. Luego puedes agregar las siguientes clases a los elementos que deseas que se animen:
```language-css
.fade-in | .fadein
.fade-out  | .fadeout
.slide-left | .slideleft
.slide-right | .slideright
.slide-top   .slidetop
.slide-bottom | .slidebottom
.slide-up  | .slideup
.slide-down | .slidedown
.zoom-in | .zoomin
.zoom-out | .zoomout
.bounce-left | .bounceleft
.bounce-top | .bouncetop
.bounce-right | .bounceright
.bounce-bottom | .bouncebottom
.animated-borders | .animatedborders
``` 

### Con Sass
* Instale EDanimate con el comando `npm install --save-dev ed-animate`
* Establezca la variable `$style: false` para compilar solo lo necesario (debe hacerlo antes de importar EDanimate).
* Importe `ed-animate/style` en su proyecto.
* Los mixins disponibles son:
```language-scss
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideDown($time, $height)
slideUp($time,$height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceTop($time)
bounceRight($time)
bounceBottom($time)
animatedBorders($time, $color)
``` 
