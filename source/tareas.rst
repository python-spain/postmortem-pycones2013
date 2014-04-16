Gestión de tareas
=================

Herramientas de gestión
-----------------------

* Lista de correo: usamos el grupo de Google de Python España para la organización del evento. Desde aquí coordinábamos las reuniones del grupo, también las visitas. En la lista se proponían y debatían algunas ideas. También se usaba para hacer llamamientos a voluntarios.

**Ventajas** llegaba a muchos potenciales interesados, y al ser una lista pública, se daba transparencia a la organización. **Desventajas** al ser una lista de propósito general había mucha gente con intereses muy diversos. Esto dificultó la gestión de los implicados. Como recomendación para futuras organizaciones, sería mejor crear una lista exprofesso. Podría ser de acceso libre, pero la inercia ayudaría a que se inscribieran los interesados en colaborar.

* Google Drive: en GDrive teníamos una carpeta con documentación compartida por los organizadores: presupuesto del evento, facturas, certificados, logos, presupuestos de proveedores.

**Ventajas** fácil comprartir la información entre varios. **Inconvenientes** al ser información no normalizada, había que tener bastante conocimiento de la documentación para ubicarse. Aplicación propietaria (la información está en servidores ajenos a la organización).

* Web: en el panel de administración de la web teníamos el listado de empresas candidatas a patrocinio y llevábamos la gestión inicial ahí. También registrábamos aquí las propuestas de charlas.

**Ventajas** información fácil de gestionar con la administración de Django. Aplicación libre (la información está en servidores de la organización). **Inconvenientes** no es tan flexible como un repositorio de documentación.

* Trello: con Trello montamos una especie de panel kanban de tareas asignadas a sus encargados y con el estado de la tarea. Teníamos varios paneles de Trello: financiación de ponentes, seguimiento de patrocinadores, otro para el horario, y uno general con tareas diversas.

**Ventajas** organización muy visual de las tareas. **Inconvenientes** Aplicación propietaria (la información está en servidores ajenos a la organización). Solo sirve para tareas pequeñas y atómicas.

* Wiki Python Hispano: cuando el equipo empezaba a organizarse teníamos a nuestra disposición el wiki de Python Hispano. Sin embargo, el formato wiki no nos resultó útil así que lo dejamos en beneficio de otras herramientas.

En general, tener muchas herramientas tiene varios problemas:
- dificulta la gestión de colaboradores
- dificulta la gestión de la información pues no está unificada

En el caso de PyConES 2013, podríamos haber prescindido de la administración de Django y usar una hoja de cálculo para la recepción de propuestas y para los patrocinadores.

A cambio, diversificar con varias herramientas permite tener la solución adecuada para cada tipo de tarea. En definitiva, las herramientas dependen mucho de cada grupo organizativo.

Organización de las tareas
--------------------------

La mayor parte de las tareas fueron llevadas a cabo por el núcleo organizativo, formado por 4-5 personas. La decisión de qué tareas concretas había que realizar la tomaba normalmente una persona (Yamila) en acuerdo con el resto de equipo organizativo. Asímismo, el seguimiento de las tareas las realizaba Yamila.

En el caso de PyConES 2013 faltó experiencia en organización distribuida y casi toda la gestión surgió del equipo organizador desde Madrid. Consideramos que no es imprescindible que sea así y que con un poco de esfuerzo se podrían organizar tareas atómicas, fácilmente delegables.

Tareas realizadas
-----------------

A continuación, un listado de las principales tareas que se realizaron en la I PyConES:

**Logística**

* gestión del presupuesto: la información relacionada con el presupuesto se puede ver en :ref:`presupuesto`

* patrocinadores: la información relacionada con los patrocinadores se puede ver en :ref:`patrocinadores`

* web: contamos con la ayuda de un diseñador que creó una web sencilla y mantenible. Tuvo muy buena acogida. Es importante tener una web desde pronto, desde donde poder distribuir la información a todos los interesados en el evento. Inicialmente era un Symposion, pero como no veíamos que nos fuera a resultar útil, la dejamos en una web Django. El código está disponible en:

https://github.com/python-spain/pycones-web

* cátering: pedimos unos 10 presupuestos distintos. Tuvimos en cuenta el precio, la calidad, la cantidad, también pedíamos que nos pudieran ofrecer menús vegetarianos. Uno de los aciertos en este sentido fue conseguir que el cátering, ya que no era en cafetería, nos lo dieran en cajas individuales: resultó fácil de repartir y de recoger.

* grabación: pedimos muchos presupuestos. Aquí nos encontramos muchísima variedad de presupuestosy precios, con distintas calidades y servicios.

* cartelería: creamos 3 rollups (uno por cada track) con los patrocinadores, y también paneles con el horario para cada sala.

* papelería: los welcome packs incluían trípticos e información útil impresa.

* camisetas: sabíamos que las camisetas eran un elemento importante para los asistentes. Hicimos un concurso para el diseño y conseguimos un taller que nos las dio en muy buena calidad y que nos daba un modelo de tallaje para mujer.

* welcome pack: para el welcome pack buscamos una empresa que nos ofreciera todo lo que queríamos: el tríptico, las chapas, las cartulinas para las comidas, la bolsa y el lanyard.

* logística: tuvimos que organizar algunos detalles logísticos menores, como conseguir ordenadores para las ponencias, y pendrives para las slides. También telas para vestir las mesas de los stands y botellas de agua para los ponentes.

* venta de entradas: buscamos varias empresas para la gestión de entradas. Finalmente nos decidimos por la que nos ofrecía mejores condiciones. Hacíamos seguimiento diario de la venta de entradas pues representaba parte del presupuesto y afectaba a otros aspectos de la organización.

* call4papers: para el c4p creamos un equipo específico que recibió todas las charlas y votó y organizó los tracks. Para más información sobre el c4p, ver :ref:`charlas`

* voluntarios durante la charla. Tuvimos dos tipos de voluntarios durante el evento:
- voluntarios dentro de las charlas. Consistió en asistentes que ya tenían entrada y que se ofrecieron a la microgestión de las charlas: asegurarse de que funcionaba el proyector, dar la botella de agua para los ponentes, controlar el tiempo de las charlas, grabar las transparencias en el pendrive...
- voluntarios de información. Buscamos voluntarios que no tuvieran entrada: a cambio de su ayuda en el stand de información, en las acreditacoines,  o controlando la entrada al recinto, etc, consiguieron una entrada y pudieron asistir a charlas cuando no estuvieran atendiendo. Se hizo un cuadrante que asegurara que disponían de al menos la mitad del tiempo para asistir a charlas.

**Comunicación**

* newsletter: creamos un boletín muy sencillo, con el que informábamos de novedades y dábamos los avisos pertinentes.

* información útil. También generamos información útil para los asistentes: hoteles y transporte que les ayudaran a gestionar el viaje.

* otros medios: para saber sobre las tareas de comunicación, ver :ref:`comunicacion`

**Otros detalles**

* regalos: conseguimos una importante cantidad de regalos para los asistentes: libros, camisetas y planes en distintas plataformas de software.

* cena de ponentes y patrocinadores. El viernes previo a la conferencia organizamos una cena de cocktail para ponentes y patrocinadores. Funcionó muy bien como antesala de la conferencia.

* pybirras: el sábado por la noche, tras el primer día de charlas, nos juntamos los asistentes enun pub. Teníamos cervezas y picoteo patrocinados.
