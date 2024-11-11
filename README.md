# TP Individual / Segunda parte (entrega final) – García Rocio Ayelén
011/11 Realizo la entrega final del TP1 - Parte 2 | Ampliación de Currículum Vitae (Portfolio).

¡Hola! Este es mi trabajo web! En todo el proceso y luego de la primera corrección, quería comentar que logré corregir algunos códigos del html, como por ejemplo cerrar divs, o algunos links que estaban mal linkeados. También utilicé la recomendación de height: fit content y luego padding bottom, para que los margins bottom no me queden tan grandes. Luego de corregir eso siento que en esta etapa lo he logrado mejor y de forma más prolija. Utilicé una paleta cromática amplia en cuanto a saturación, por un lado un violeta saturado y por el otro un rosa desaturado. También utilicé dos tipografías bien contrastadas entre sí, la Nunito Sans para textos en particular, y la JetBrainsMono para titulares o destacados. Es por esto que considero que la página en su conjunto logró tener consistencia e identidad. También reconozco que con el mediaqueries tuve algunas complicaciones, como por ejemplo la botonera del nav aunque sí hice para el index y para la galería. Otra cosa que me hubiese gustado agregarle al trabajo, son efectos de sonido al pasar el mouse por alguno de los botones del index, con Javascript. Sin duda, estoy segura de que el trabajo podría seguir mejorando y creo objetivamente que he aprendido mucho. En figma no están del todo resueltas algunas interacciones, o algunas no funcionan, pero al fin y al cabo en el código pude lograrlo.

## Descripciones generales
Para hacer este trabajo web utilicé Visual Studio Code como editor de código, y trabajé en un tamaño de pantalla de 1366px/768px.
### Vinculación con Figma
Estuve trabajando bastante en Figma, en principio para tener una guía de la estructura de la página y saber cómo y por dónde quería ir. https://www.figma.com/design/h8kgLuxlNVfzeoyJL4Dn24/Portfolio-RocioG?t=tYW9FGYCg09fGsGl-0

Se buscó que a través de la creación de varios html, que uno pueda navegar en la página de forma más clara, en lugar de que toda la información esté en el Index / Landing, y de esta forma hacerlo más interactivo, también con varios botones. 

#### Archivos html:
En el nav, hay un botón que te lleva a la section “sobre mí” del index y otro que te lleva hacia los proyectos destacados. También hay otro que te direcciona hacia mi cv para hacer una descarga en caso necesario, y otro botón que te lleva al html de contacto. 

**1-index.html:** contiene una breve presentación e información sobre mí, con un botón que te lleva al html de trayectoria para conocerme más. También muestro algunos proyectos destacados de las distintas materias de la carrera con información. Asimismo al hacer scroll en el index hay un apartado de links sobre mis redes, con un botón que te direcciona hacia el html de contacto. 

**2-trayectoria.html:** contiene información más detallada sobre mi experiencia, habilidades, intereses, idiomas, etc.

**3-contacto.html:** contiene un formulario en donde el usuario puede dejar sus datos y contactarse conmigo, o despejar dudas, consultas, etc.

**3-galeria.html:** contiene información detallada sobre cada proyecto. Son 6 html correspondientes ala galería. Al hacer click en una de las imágenes de la sección "Otros proyectos" del index, para ver más, se amplía la información.

También hay un archivo Javascript que lo utilicé para realizar el carrusel de las imágenes de los proyectos destacados.
