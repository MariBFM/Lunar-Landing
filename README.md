# Lunar-Landing Versión Minimificada.

**En este caso para la optimización del proyecto los archivos HMTL y CSS están escritos en una sola línia.**

En este repositorio se muestra la primera parte del proyecto _Lunar Landing_, esta parte
consiste en crear el **HTML** basado en el _StoryBoard_ que se ha dado en la tarea y aplicarle
dos archivos **CSS** diferentes. Uno de ellos se debe aplicar para PC y el otro para dispositivos 
móviles.

**Antes de empezar el HTML he buscado todas las imágenes que necesitaría por Google, después
las he modificado con _Photoshop_ para cambiar color, quitar fondo, etc. Y una vez exportadas
las he pasado por [TinyPNG](https://tinypng.com/) para optimizarlas.**

### HTML

Para empezar el panel donde se muestran los datos de la nave y el menú de opciones son dos lista que
después son modificadas con **css**. Por ahora el panel no mostrará nada más de lo que ya tiene escrito. Para
el menú de opciones he puesto imágenes y les he puesto enlaces, por ahora el único enlace que hace algún
cambio es el de _"How to play"_ que lleva a otro **HTML** donde explica cómo se juega y el objetivo.

El resto del **HTML** son imágenes, la luna, la nave, decoración... La nave esta compuesta por 4 imágenes
pensando en los siguientes pasos del proyecto. Para el **CSS** he añadido _div class_ y _id_ a las imágenes.

En el documento **HTML** también he añadido la siguiente línea de comando en el _head_:  
**meta name="viewport" content="width=device-width, initial-scale=1.0"**  
con esto haremos que el _viewport_ (área visible de una página web) se de la anchura del dispositivo, y que
la escala inicial sea sin zoom.

#### Validador HTML:
![Validador HTML](https://github.com/NMari2/Lunar-Landing/blob/LunarLanding-Minimificada/Validador%20HTML%20Mini.PNG)

### CSS

He creado dos archivos **CSS** uno que se llama _pc.css_ y otro _mob.css_, el primero se aplicará cuando la
pantalla sea de 770px de ancho o mayor, y la otra menor de 770px.

Para ello en el **HTML** he utilizado _Media Queries_ de la siguiente manera:  
link rel='stylesheet' media='screen and (min-width: 770px)' href='css/pc.css'  
link rel='stylesheet' media='screen and (max-width: 770px)' href='css/mob.css'

En _pc.css_ he puesto un fondo estrellado grande, y en _mob.css_ he puesto un fondo más pequeño que quedaría mejor en
dispositivos móviles. 

En ambos **CSS** he ajustado el tamaño en píxeles, y para el posicionamiento he utilizado porcentajes.

Para los enlaces he utilizado apariencias dinámicas para que en ordenador sea más fácil encontrarlos.

#### Validador CSS:
![Validador CSS](https://github.com/NMari2/Lunar-Landing/blob/LunarLanding-Minimificada/VCSSMini.PNG)

### Rawgit de la página minimificada:  
[**LunarLanding**](https://rawgit.com/NMari2/Lunar-Landing/LunarLanding-Minimificada/index.html)
