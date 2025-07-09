 
Paper de Trabajo: Proyecto de FrontEnd
Instrucciones Generales
Cada alumno deberá diseñar e implementar un sitio web con los requisitos mínimos que se exigen en la sección Requerimientos. Para lo anterior el estudiante deberá escoger uno de los 5 casos que provee el docente o traer uno a su elección, los casos empresas que necesitan un sitio web para promocionarse en internet.
Esta es la primera evaluación de la asignatura por lo que debe tomárselo en serio y ser responsable para poder traer el trabajo dado que la única fecha para mostrarlo y obtener la máxima nota es el día 18.06.2025. Tiene una oportunidad de feedback el dia 11.06.2025
Cualquier entrega fuera de plazo tiene como nota máxima un 3,9. El NO entregar la evaluación una vez terminada la jornada del día 18.06.2025 supone la nota mínima permitida por INACAP
 
 
Requerimientos
Los siguientes son los requerimientos mínimos a cumplir si es que está considerando tener la nota máxima.
Crear un sitio web para dicha empresa
1.	Crear un logotipo
2.	Crear un nombre o utilizar el que se brinda
3.	El sitio debe tener al menos 4 paginas navegables
4.	Debe utilizar framework bootstrap 4.5 obligatorio
5.	El sitio debe ser responsive y lograr una visualización optima al menos en un Smartphone.
6.	El desarrollo y el código debe ser semántico y respetuoso con los nombres de archivos, carpetas, y otros
7.	Incluya el logo de la empresa y los colores corporativos
8.	Debe incluir un favicon para el sitio
9.	Debe utilizar imágenes y esas imágenes ser alusivas a la compañía, utilice IA si es necesario
10.	Todo su proyecto debe estar publicado en GitHub con al menos 3 commits, intente hacer commit cada vez que termine una de las páginas de su sitio, con ello cumple a cabalidad los 3 commits.  
Secciones a Implementar
1.	Index:
a.	NavBar
b.	Carrousel o slider
c.	Sección de contenido
d.	Footer
2.	Sobre Nosotros
a.	NavBar
b.	Información sobre la compañía, equipos, historia, misión, visión…
c.	Footer
3.	Servicios
a.	NavBar
b.	6 servicios/productos con imagen, texto, precio, condiciones...etc.
c.	Footer
4.	Contactenos
a.	NavBar
b.	Formulario de Contactenos
c.	Mapa de la ubicacion de la empresa
d.	Footer
 
Casos para elegir
 
CASO 4: Empresa de Reparto Urbano – “FastGo”
Contexto:
FastGo realiza entregas express en la ciudad. Usan una app de tracking, pero no tienen visibilidad general del rendimiento por zona, repartidor o cliente.

---------------------------------------------------------------------------------------------------------------------------------------------------------------
Evaluación 2 

Requerimientos Evaluación II
Objetivo
El foco estará en el manejo de formularios, validación de correo electrónico y almacenamiento en LocalStorage, es decir al apretar enviar en su formulario además de validar los datos que no estén vacíos, debe validar que el correo electrónico sea correcto y almacenar en el LocalStorage. Instrucciones especificas:
•	Usar el mismo caso trabajado en la Evaluación I, si lo desea no lo utilice, pero debe traer una web de formulario de contacto con bootstrap.
•	Validar el campo de correo electrónico (formato válido).
•	Almacenar los datos del formulario en LocalStorage.
•	Listar los datos que se almacenan
•	Editar un registro y actualizar su LocalStorage
•	Eliminar un registro del LocalStorage
•	Subir el proyecto a GitHub o enviar por correo.
•	Utilizar Jquery
•	Conectarse a la API: https://restcountriies.com/v3.1/lang/spanish y obtener los datos de los países
•	Además, su formulario de contacto debe tener:
o	Nombre
o	Teléfono
o	Email
o	País
o	Nombre oficial del país (debe cargarlo desde la misma API) JSON.
    "name": {
      "common": "Nicaragua",
      "official": "Republic of Nicaragua",
      "nativeName": {
        "spa": {
          "official": "República de Nicaragua",
          "common": "Nicaragua"
        }
      }
    }
o	Comentarios
