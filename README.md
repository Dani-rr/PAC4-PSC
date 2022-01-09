# PAC4-PSC
PAC4 de la asignatura programación para la ciencia de datos.

Con la realización de este ejercicio vamos a poner en práctica los conocimientos obtenidos durante el curso, centrándonos especialmente en la modularidad del código y en el testeo del mismo.

El proyecto está estructurado de la siguiente forma:

- Carpeta principal: 
	pec4.py: Script principal que resuelve las dudas propuestas en el enunciado de la PEC
	test.py: Unittest que comprueban el buen funcionamiento de las funciones implementadas.
	.coverage: Resultado de runear el paquete coverage
	requirements.txt: Archivo con los paquetes necesarios para runear nuestro código

- data: Contiene tanto el zip original con todos los csv, así como su extracción y el dataframe 'df.csv' que hemos generado y que se usará durante el ejercicio.


- tareas2-7:
	Hemos decidido separar cada tarea por paquetes. Dentro de estos paquetes encontraremos modulos llamados funciones[número de tarea].py con cada una de las funciones necesarias para resolver esta tarea.


La tarea se resolverá ejecutando el archivo pec4.py.

## Otros aspectos

### PEP8

El código ha sido formateado según lo expuesto en el enunciado de la práctica con el paquete black.

### Requirements

El requirements.txt puede ser algo más extenso de lo necesario ya que no me queda claro las dependencias entre librerías y el procedimiento de instalado, aun así y comparándolo con otros environments es bastante ligero.

### Tests

Se han ejecutado test para las funciones de las tareas 2, 3 y 4. He intentado documentarme sobre la posibilidad de testear los plots devueltos en las funciones de las tareas 5, 6 y 7 pero no he conseguido hacerlo funcionar. La cobertura mostrada en el Total (67%) no es del todo exacta ya que no está tomando los funciones de los archivos funciones5-6.

Para ejecutar y comprobar la cobertura se necesita seguir los siguientes correr las siguientes lineas en la terminal de nuestro IDE:

coverage run -m unittest discover

coverage report -m

### Otros

Debido a la falta de tiempo no se ha podido realizar la tarea opcional (8).

## Licencia

Se ha elegido una la licencia CC-BY-NC-SA por los siguientes motivos: 

- Cualquier me modificación o implementación de información que se produzca en el dataset puede ser de ayuda a otros usuarios.

- Dado que los datos son de carácter público, se prefiere que el uso que se haga de ellos no sean de carácter comercial y todas las contribuciones o modificaciones de ellos deberán distribuirse bajo el mismo tipo de licencia.

## Agradecimientos

Last but not least. Como con la entrega de esta práctica se acaba la asignatura me gustaría agradecerte todo el conocimiento y material que has puesto a nuestra disposición. Siempre has estado disponible y has respondido todas nuestras dudas en el foro (incluso a los que no posteamos mucho) de manera clara, amena y humilde. 
