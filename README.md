# GreenTech-MVP-Sostenible_GilCue_Pepe

## Descripción del proyecto

Este proyecto consiste en la refactorización de una página web, *"Salvemos el Planeta"* de GreenTech Solutions. El objetivo es transformar una web pesada e ineficiente, en una versión ligera, rápida y sostenible, eliminando todo lo inecesario.

El resultado y el objetivo del trabajo es una web funcionalmente e idéntica a la original, pero que consume muchos menos recursos, carga más rápido y respeta los principios del diseño web sostenible.

## Estructura del repositorio

El repositorio contiene los siguientes archivos:

* **GreenTechSolutionAEE.html** → Archivo HTML refactorizado, limpio y sin dependencias externas innecesarias.
* **GreenTechSolutionAEE.css** → Hoja de estilos propia en CSS, sin frameworks.
* **Principal.html** → Archivo HTML original proporcionado como punto de partida, conservado como referencia.
* **README.md** → Este documento, explicativo del proyecto.

## Qué se ha refactorizado y por qué

### Eliminación de Bootstrap

La versión original cargaba **Bootstrap**, un framework CSS que pesa bastante más en comparacion al .css. Bootstrap es una herramienta muy útil cuando se construyen interfaces complejas con decenas de componentes, pero en este caso solo se usaba para aplicar estilos a un único botón y a un  puequeño bloque de texto.

En la versión refactorizada, todos esos estilos se han reescrito directamente en el archivo `GreenTechSolutionAEE.css`. El resultado visual es prácticamente idéntico, pero sin el peso añadido.

## Relación con la sostenibilidad

Hay un efecto del software ineficiente que pasa muy desapercibido: hace que los móviles y ordenadores envejezcan antes de tiempo.

Cuando una web carga librerías enormes que no necesita, el dispositivo tiene que trabajar más de la cuenta para procesarlas. Eso se traduce en que el móvil va más lento, se calienta y gasta batería más rápido. Con el tiempo, el usuario siente que su teléfono "ya no sirve" y lo cambia, aunque el hardware en sí todavía funcione perfectamente. Y el software mal optimizado es uno de sus principales culpables, y nosotros podemos ser uno de los principales culpables o esenciales para poder solucionar este problema.

Por eso, que nuestra web pese apenas 5 KB en lugar de 600 KB no es solo una cuestión de velocidad. Es una decisión que ayuda a que funcione bien en dispositivos modestos y antiguos, y que contribuye, aunque sea en pequeña medida, a que no haya que fabricar uno nuevo antes de tiempo.

## Tecnologías utilizadas

* **HTML5** semántico para la estructura de la página.
* **CSS3** para los estilos, sin ningún framework externo.




