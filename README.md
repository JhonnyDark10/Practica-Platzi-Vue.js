# Practica-Platzi-Vue.js

Práctica Módulo 2
Armar un simple “tracker” de cursos, que permita calcular y registrar la cantidad cursos de Platzi tomados y obtener la suma de las horas invertidas en tu educacion.

Haz fork de este CodePen para obtener la estructura basica del proyecto:

Consideraciones:
La aplicación debe cumplir los siguientes lineamientos:
Un propiedad courses que sea un array y permita almacenar la lista de cursos.
Tener una propiedad title y otra time que se usean para agregar un nuevo curso a la lista, estas propiedades deben estar enlazados a los inputs usando v-model.
Un boton con un metodo addCourse (enlazado con v-on) que permita agregar un nuevo courso usando los valores de title y time.
Una propiedad computada totalTime que recorra toda la lista de cursos y retorne la suma del tiempo invertido en educacion.
Mostrar la lista de cursos tomados, con el titulo de los mismos y las horas de cada uno usando v-for.
Mostrar el total de horas con totalTime, en caso que no existan cursos se debe mostrar un mensaje indicandolo.
