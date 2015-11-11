#Academia Class Diagram

Requisitos
----
Una Academia de idiomas pretende disponer de una aplicación para controlar las inscripciones a sus cursos, que imparte diariamente en horario de 8 a 21 horas, en periodos de una hora exacta. Tras analizar el problema se ha llegado a la conclusión de que es necesario implementar las siguientes clases: 

* Alumno: cada uno de los alumnos de la academia. Debe tener información sobre la lista de los cursos en que se inscribe (inicialmente vacía), además del nombre, apellidos y DNI. Debe ser capaz de informar de la deuda total del alumno.

* Curso: Cada uno de los cursos que organiza la academia. Tiene un código identificador único e información sobre el idioma, nivel, fechas de inicio y final, así como la hora en que se imparte. Tiene un número de alumnos máximo, un precio de matrícula y mantiene una lista de los alumnos inscritos. 

* Matrícula: Representa la inscripción de un alumno en un curso concreto. Tiene un número único de matrícula y puede estar pagada o pendiente de pago (estado inicial).
Cuando se crea la inscripción, el alumno y el curso deben existir y hay que comprobar tanto que un alumno no se matricula dos veces en un mismo curso como que un curso no tiene más alumnos que los máximos autorizados.
Cuando posteriormente se recibe el pago se marca la matrícula como pagada.
Se puede cambiar de nivel a un alumno si se ve que no es adecuado con la siguiente restricción: solo se puede subir o bajar un nivel, dentro del mismo idioma. Además no se puede superar el máximo de alumnos.  
· El conjunto de clases debe permitir obtener la lista de alumnos de un curso, la lista de cursos de un alumno y la lista de inscripciones sin pagar de un curso.
 

Elabore las clases mencionadas en Java, así como la clase Academia encargada de comprobar el buen funcionamiento del resto de las clases. Esta clase crea y mantiene la lista de cursos, alumnos y matrículas. Debe comprobar si se dan las condiciones previas para las matrículas y si es posible crearlas. Debe probar del mismo modo el resto de métodos públicos de las otras tres clases.

Solucion:
----
<img src="Class Diagram-Academia.png" border="0" alt="DamasPythonGtk3"></a>


Autores
----
Sergio García: [garciparedes](https://github.com/garciparedes)
