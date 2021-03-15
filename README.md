Asignación de codificación del módulo 2
Curso de Coursera: HTML, CSS y Javascript para desarrolladores web

¡Woo-hoo! ¡Puedes hacer algo de codificación! ¡Emocionante!

Tiempo para completar: 1-2 horas. Puede que le lleve menos tiempo si ha absorbido bien el material de este módulo.

¡Haga preguntas en Discusiones si se atasca! Todos estamos aprendiendo, y atravesar el problema y luego despegarnos (incluso con la ayuda de alguien) puede ser una experiencia de aprendizaje muy valiosa.

No se asuste por la cantidad de puntos a continuación. Realmente no es tanto. Solo quería explicar todo lo más claramente posible y dividirlo en pasos más pequeños.

Esto es lo que necesitará para completar la tarea:

(Si aún no lo ha hecho) Cree una cuenta de GitHub.com y un repositorio que utilizará para esta clase.

(Si aún no lo ha hecho) Siga las instrucciones del video de configuración de desarrollo (al comienzo del Módulo 1) sobre cómo crear un repositorio y configurarlo de manera que pueda alojar y ver sus páginas web terminadas en las páginas de GitHub, es decir, GitHub.io nombre de dominio. Deberá proporcionar esa URL para su revisión por pares.

Cree una carpeta en su repositorio que servirá como carpeta contenedor para su solución a esta asignación. Puedes llamarlo como quieras. Por ejemplo, module2-solutiono mod2_solution, etc. Crear un index.htmlarchivo dentro de la carpeta recipiente de solución, por ejemplo, module2-solution/index.html.

La implementación de la página que creará debe seguir las ilustraciones de la maqueta que se muestran a continuación. Se le proporcionan 3 maquetas: computadora de escritorio, tableta y dispositivo móvil. Su implementación tiene que ser SOLO 1 página, NO 3 páginas. En otras palabras, creará una página única y receptiva.

Su página debe incluir un archivo CSS. No se permiten estilos en línea. Su archivo CSS se debe colocar en una csscarpeta dentro de la carpeta envase de la solución, por ejemplo, module2-solution/css.

NO se le permite utilizar ningún marco CSS (o Javascript) para esta tarea, incluido el marco CSS Bootstrap de Twitter. No se debe hacer referencia a ningún archivo CSS de framework en su index.html, incluso si no los está utilizando. Sin embargo, PUEDE usar el marco receptivo simple que desarrollamos en la Lección 24 como punto de partida para esta tarea.

Debe implementar los siguientes puntos de interrupción que se considerarán computadoras de escritorio, tabletas y dispositivos móviles. El navegador debería mostrar una versión de escritorio del sitio cuando el ancho de la ventana del navegador sea de 992px o más. La vista de tableta debería aparecer solo si el ancho de la ventana del navegador está entre 768px y 991px, inclusive. La vista móvil debe aparecer solo si el ancho del navegador es igual o menor a 767 px.

Tu sitio es muy simple. Consta de un encabezado de página y 3 secciones (todas en una fila en la vista de escritorio). Cada sección contiene algo de texto. Puede convertirlo en texto ficticio / "lorem ipsum", no importa. La disposición de las secciones en la pantalla depende del ancho de la ventana del navegador. ( Sugerencia: use las consultas de medios que se discutieron en la Clase 23 ).

Diseño: en la vista de escritorio (992px y superior), cada una de las 3 secciones debe ocupar la misma cantidad de espacio en la pantalla. A medida que amplía o estrecha la ventana del navegador, cada sección debería hacerse más ancha o más estrecha. ( Sugerencia: use porcentajes para definir el ancho y use la propiedad 'float'. Vea la lección 24 ). Para obtener una referencia visual de esta vista, consulte la ilustración de la maqueta del escritorio a continuación.

Diseño: en la vista de tableta (entre 768px y 991px, inclusive), las 2 primeras secciones deben estar en la primera fila y tener el mismo tamaño. La tercera sección debe estar en la segunda fila y ocupar toda la fila por sí sola. Para obtener una referencia visual de esta vista, consulte la ilustración de la maqueta de la tableta a continuación.

Diseño: en la vista móvil (igual o menor a 767 px), cada sección debe ocupar toda la fila. Para obtener una referencia visual de esta vista, consulte la ilustración de la maqueta móvil a continuación.

Región del título de la sección: cada sección debe tener una región del título de la sección que siempre esté ubicada en la esquina superior derecha de la sección, sin importar la vista (escritorio, tableta o dispositivo móvil). Copie los títulos de la ilustración de la maqueta (es decir, pollo, ternera, sushi) o cree uno propio. ( Sugerencia: use posiciones y compensaciones relativas y absolutas como se discutió en la Clase 22 ).

Espaciado: preste atención al espaciado que se muestra en las ilustraciones de la maqueta. Tenga en cuenta el espacio entre las secciones (tanto horizontal como vertical). Tenga en cuenta el espacio horizontal entre los bordes de la sección y los bordes de la ventana del navegador. Además, tenga en cuenta el espacio entre el texto ficticio en cada sección y los bordes de la sección. Por último, asegúrese de que el texto ficticio esté "empujado hacia abajo" lo suficiente para que no se superponga a la región del título de la sección. ( Sugerencia: use márgenes y relleno y use border-box como su tamaño de caja como se discutió en la Lección 19. )

Bordes y colores: cada sección debe tener un color de fondo establecido en algún color (de su elección). Establezca el color de fondo de cada región de título de sección en un color único (de su elección). Asegúrese de que el color de fondo aún permita al usuario ver el texto en la sección y en las regiones del título de la sección. Dependiendo del color que elija, es posible que desee cambiar el color del texto para que sea fácil de leer. Establezca un borde negro tanto en la sección como en la región del título de la sección con un grosor de 1 px. Advertencia: Si bien no especificar bordes y colores de acuerdo con los requisitos no perjudica tanto su calificación, no hacerlo hará que sea mucho más difícil para sus compañeros calificar el resto de su tarea, lo que posiblemente resulte en una calificación mucho más baja.

(OPCIONAL) NO se le calificará en esto , pero es posible que desee establecer explícitamente una familia de fuentes para el texto de su página, de modo que no se quede atascado con la familia de fuentes predeterminada del navegador. Además, establezca el tamaño de fuente del encabezado y el título de la sección para que sea un 75% más grande y un 25% más grande (respectivamente) que el tamaño de fuente del texto ficticio.

Aquí está la ilustración de la maqueta de la versión de escritorio del sitio. Su resultado final debería parecerse mucho a esta maqueta.

escritorio

Aquí está la ilustración de la maqueta de la versión para tableta del sitio. Su resultado final debería parecerse mucho a esta maqueta. Tenga en cuenta que en esta vista, la tercera sección ocupa toda la fila.

tableta

Aquí está la ilustración de la maqueta de la versión móvil del sitio. Su resultado final debería parecerse mucho a esta maqueta.

móvil
