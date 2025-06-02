# Consultas de SQL, actividad #2

## Modelo físico de la base de datos

![Empresa](img/Empresa.jpg "Modelo Físico de la BD")

## Estructura de la BD

![Estructura](img/estructura.png "Estrucutra de la BD")

## Consultas a la BD

1. Obtener la lista de los apellidos de todos los empleados.

`SELECT apellidos_empleados FROM empleado;`

![Consulta 1](img/consulta_1.png "Consulta 1")

2. Obtener los apellidos de todos los empleados sin repeticiones.

`SELECT DISTINCT apellidos_empleados FROM empleado;`

![Consulta 2](img/consulta_2.png "Consulta 2")

3. Obtener todos los datos de los empleados que se apellidan 'Gomez'.

`SELECT * FROM empleado WHERE apellidos_empleados = 'Gomez';`

![Consulta 3](img/consulta_3.png "Consulta 3")

4. Obtener todos los datos de los empleados que se apellidan "Diaz" y los que se apellidan "Rodriguez".  Usar OR o IN

`SELECT * FROM empleado WHERE apellidos_empleados = 'Diaz' OR apellidos_empleados = 'Rodriguez';`

![Consulta 4](img/consulta_4.png "Consulta 4")