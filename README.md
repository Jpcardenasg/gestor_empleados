# GESTOR DE EMPLEADOS

Base de datos de empleados y sus departamentos usando MySQL

* Cardinalidad:

    - Un empleado puede solo puede estar asociado a un departamento. Empleado **1 : N** Departamento.
    - Un departamento puede tener muchos empleados. Departamento **1 : N** Empleado.

## Entidad Departamento
### Modelo lógico
![Descripcion Departamento](/images/desc_departamento.png)
### Datos
![Datos Departamento](/images/tabla_departamento.png)


## Entidad Empleado
### Modelo lógico
![Descripcion Empleado](/images/desc_empleado.png)
### Datos
![Datos Empleado](/images/tabla_empleado.png)


## Consultas

### Una tabla
1. Lista el primer apelldio de todos los empleados
![Primer punto](/images/UnaTabla/punto_1.PNG)

2. Lista el primer apellido de los empleados eliminando los apellidos que estén repetidos.
![Segundo punto](/images/UnaTabla/punto_2.PNG)

3. Lista todas las columnas de la tabla empleado.
![Tercer punto](/images/UnaTabla/punto_3.PNG)

4. Lista el nombre y los apellidos de todos los empleados.
![Cuarto punto](/images/UnaTabla/punto_4.PNG)

5. Lista el identificador de los departamentos de los empleados que aparecen en la tabla empleado.
![Quinto punto](/images/UnaTabla/punto_5.PNG)

6. Lista el identificador de los departamentos de los empleados que aparecen en la tabla empleado, eliminando los identificadores que aparecen repetidos.
![Sexto punto](/images/UnaTabla/punto_6.PNG)

7. Lista el nombre y apellidos de los empleados en una única columna.
![Séptimo punto](/images/UnaTabla/punto_7.PNG)

8. Lista el nombre y apellidos de los empleados en una única columna, convirtiendo todos los caracteres en mayúscula.
![Octavo punto](/images/UnaTabla/punto_8.PNG)

9. Lista el nombre y apellidos de los empleados en una única columna, convirtiendo todos los caracteres en minúscula.
![Noveno punto](/images/UnaTabla/punto_9.PNG)

10. Lista el identificador de los empleados junto al nif, pero el nif deberá aparecer en dos columnas, una mostrará únicamente los dígitos del nif y la otra la letra.
![Decimo punto](/images/UnaTabla/punto_10.PNG)

11. Lista el nombre de cada departamento y el valor del presupuesto actual del que dispone. Para calcular este dato tendrá que restar al valor del presupuesto inicial (columna presupuesto) los gastos que se han generado (columna gastos). Tenga en cuenta que en algunos casos pueden existir valores negativos. Utilice un alias apropiado para la nueva columna columna que está calculando.
![Onceavo punto](/images/UnaTabla/punto_11.PNG)

12. Lista el nombre de los departamentos y el valor del presupuesto actual ordenado de forma ascendente.
![Punto Doce](/images/UnaTabla/punto_12.PNG)

13. Lista el nombre de todos los departamentos ordenados de forma
ascendente.
![Punto Trece](/images/UnaTabla/punto_13.PNG)

14. Lista el nombre de todos los departamentos ordenados de forma
descendente.
![Punto Catorce](/images/UnaTabla/punto_14.PNG)

15. Lista los apellidos y el nombre de todos los empleados, ordenados de forma alfabética tendiendo en cuenta en primer lugar sus apellidos y luego su nombre.
![Punto Quince](/images/UnaTabla/punto_15.PNG)

16. Devuelve una lista con el nombre y el presupuesto, de los 3 departamentos que tienen mayor presupuesto.
![Punto Dieciséis](/images/UnaTabla/punto_16.PNG)

17. Devuelve una lista con el nombre y el presupuesto, de los 3 departamentos que tienen menor presupuesto.
![Punto Diecisiete](/images/UnaTabla/punto_17.PNG)

18. Devuelve una lista con el nombre y el gasto, de los 2 departamentos que tienen mayor gasto.
![Punto Dieciocho](/images/UnaTabla/punto_18.PNG)

19. Devuelve una lista con el nombre y el gasto, de los 2 departamentos que tienen menor gasto.
![Punto Dieciocho](/images/UnaTabla/punto_19.PNG)

20. Devuelve una lista con 5 filas a partir de la tercera fila de la tabla empleado. La tercera fila se debe incluir en la respuesta. La respuesta debe incluir todas las columnas de la tabla empleado.
![Punto Veinte](/images/UnaTabla/punto_20.PNG)

21. Devuelve una lista con el nombre de los departamentos y el presupuesto, de aquellos que tienen un presupuesto mayor o igual a 150000 euros.
![Punto VeinteUno](/images/UnaTabla/punto_21.PNG)

22. Devuelve una lista con el nombre de los departamentos y el gasto, de aquellos que tienen menos de 5000 euros de gastos.
![Punto VeinteDos](/images/UnaTabla/punto_22.PNG)

23. Devuelve una lista con el nombre de los departamentos y el presupuesto, de aquellos que tienen un presupuesto entre 100000 y 200000 euros. Sin utilizar el operador BETWEEN.
![Punto VeintiTres](/images/UnaTabla/punto_23.PNG)

24. Devuelve una lista con el nombre de los departamentos que no tienen un presupuesto entre 100000 y 200000 euros. Sin utilizar el operador BETWEEN.
![Punto VeintiCuatro](/images/UnaTabla/punto_24.PNG)

25. Devuelve una lista con el nombre de los departamentos que tienen un presupuesto entre 100000 y 200000 euros. Utilizando el operador BETWEEN.
![Punto VeintiCinco](/images/UnaTabla/punto_25.PNG)

26. Devuelve una lista con el nombre de los departamentos que no tienen un presupuesto entre 100000 y 200000 euros. Utilizando el operador BETWEEN.
![Punto VeintiSéis](/images/UnaTabla/punto_26.PNG)

27. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean mayores que el presupuesto del que disponen.
![Punto VeintiSiete](/images/UnaTabla/punto_27.PNG)

28. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean menores que el presupuesto del que disponen.
![Punto VeintiOcho](/images/UnaTabla/punto_28.PNG)

29. Devuelve una lista con el nombre de los departamentos, gastos y presupuesto, de aquellos departamentos donde los gastos sean iguales al presupuesto del que disponen.
![Punto VeintiNueve](/images/UnaTabla/punto_29.PNG)

30. Lista todos los datos de los empleados cuyo segundo apellido sea NULL.
![Punto Treinta](/images/UnaTabla/punto_30.PNG)

31. Lista todos los datos de los empleados cuyo segundo apellido no sea NULL.
![Punto TreintayUno](/images/UnaTabla/punto_31.PNG)

32. Lista todos los datos de los empleados cuyo segundo apellido sea López.
![Punto TreintayDos](/images/UnaTabla/punto_32.PNG)

33. Lista todos los datos de los empleados cuyo segundo apellido
sea Díaz o Moreno. Sin utilizar el operador IN.
![Punto TreintayTres](/images/UnaTabla/punto_33.PNG)

34. Lista todos los datos de los empleados cuyo segundo apellido
sea Díaz o Moreno. Utilizando el operador IN.
![Punto TreintayCuatro](/images/UnaTabla/punto_34.PNG)

35. Lista los nombres, apellidos y nif de los empleados que trabajan en el departamento 3.
![Punto TreintayCinco](/images/UnaTabla/punto_35.PNG)

36. Lista los nombres, apellidos y nif de los empleados que trabajan en los departamentos 2, 4 o 5.
![Punto TreintaySeis](/images/UnaTabla/punto_36.PNG)

### Multitabla (Composición interna)
1. Devuelve un listado con los empleados y los datos de los departamentos donde trabaja cada uno.
![Punto Uno](/images/MultiTabla/interna_1.png)

2. Devuelve un listado con los empleados y los datos de los departamentos donde trabaja cada uno. Ordena el resultado, en primer lugar por el nombre del departamento (en orden alfabético) y en segundo lugar por los apellidos y el nombre de los empleados.
![Punto Dos](/images/MultiTabla/interna_2.png)

3. Devuelve un listado con el identificador y el nombre del departamento, solamente de aquellos departamentos que tienen empleados.
![Punto Tres](/images/MultiTabla/interna_3.png)

4. Devuelve un listado con el identificador, el nombre del departamento y el valor del presupuesto actual del que dispone, solamente de aquellos departamentos que tienen empleados. El valor del presupuesto actual lo puede calcular restando al valor del presupuesto inicial (columna presupuesto) el valor de los gastos que ha generado (columna gastos).
![Punto Cuatro](/images/MultiTabla/interna_4.png)

5. Devuelve el nombre del departamento donde trabaja el empleado que tiene el nif 38382980M.
![Punto Cinco](/images/MultiTabla/interna_5.png)

6. Devuelve el nombre del departamento donde trabaja el empleado Pepe Ruiz Santana.
![Punto Seis](/images/MultiTabla/interna_6.png)

7. Devuelve un listado con los datos de los empleados que trabajan en el departamento de I+D. Ordena el resultado alfabéticamente.
![Punto Siete](/images/MultiTabla/interna_7.png)

8. Devuelve un listado con los datos de los empleados que trabajan en el departamento de Sistemas, Contabilidad o I+D. Ordena el resultado alfabéticamente.
![Punto Ocho](/images/MultiTabla/interna_8.png)

9. Devuelve una lista con el nombre de los empleados que tienen los departamentos que no tienen un presupuesto entre 100000 y 200000 euros.
![Punto Nueve](/images/MultiTabla/interna_9.png)

10. Devuelve un listado con el nombre de los departamentos donde existe algún empleado cuyo segundo apellido sea NULL. Tenga en cuenta que no debe mostrar nombres de departamentos que estén repetidos.
![Punto Diez](/images/MultiTabla/interna_10.png)

### Multitabla (Composición externa)
1. Devuelve un listado con todos los empleados junto con los datos de los departamentos donde trabajan. Este listado también debe incluir los empleados que no tienen ningún departamento asociado.
![Punto Uno](/images/MultiTabla/externa_1.png)

2. Devuelve un listado donde sólo aparezcan aquellos empleados que no tienen ningún departamento asociado.
![Punto Dos](/images/MultiTabla/externa_2.png)

3. Devuelve un listado donde sólo aparezcan aquellos departamentos que no tienen ningún empleado asociado.
![Punto Tres](/images/MultiTabla/externa_3.png)

4. Devuelve un listado con todos los empleados junto con los datos de los departamentos donde trabajan. El listado debe incluir los empleados que no tienen ningún departamento asociado y los departamentos que no tienen ningún empleado asociado. Ordene el listado alfabéticamente por el nombre del departamento.
![Punto Cuatro](/images/MultiTabla/externa_4.png)

5. Devuelve un listado con los empleados que no tienen ningún departamento asociado y los departamentos que no tienen ningún empleado asociado. Ordene el listado alfabéticamente por el nombre del departamento.
![Punto Cinco](/images/MultiTabla/externa_5.png)

### Consultas resumen
1. Calcula la suma del presupuesto de todos los departamentos.
![Punto Uno](/images/Resumen/punto_1.png)

2. Calcula la media del presupuesto de todos los departamentos.
![Punto Dos](/images/Resumen/punto_2.png)

3. Calcula el valor mínimo del presupuesto de todos los departamentos.
![Punto Tres](/images/Resumen/punto_3.png)

4. Calcula el nombre del departamento y el presupuesto que tiene asignado, del departamento con menor presupuesto.
![Punto Cuatro](/images/Resumen/punto_4.png)

5. Calcula el valor máximo del presupuesto de todos los departamentos.
![Punto Cinco](/images/Resumen/punto_5.png)

6. Calcula el nombre del departamento y el presupuesto que tiene asignado, del departamento con mayor presupuesto.
![Punto Seis](/images/Resumen/punto_6.png)

7. Calcula el número total de empleados que hay en la tabla empleado.
![Punto Siete](/images/Resumen/punto_7.png)

8. Calcula el número de empleados que no tienen NULL en su segundo apellido.
![Punto Ocho](/images/Resumen/punto_8.png)

9. Calcula el número de empleados que hay en cada departamento. Tienes que devolver dos columnas, una con el nombre del departamento y otra con el número de empleados que tiene asignados.
![Punto Nueve](/images/Resumen/punto_9.png)

10. Calcula el nombre de los departamentos que tienen más de 2 empleados. El resultado debe tener dos columnas, una con el nombre del departamento y otra con el número de empleados que tiene asignados.
![Punto Diez](/images/Resumen/punto_10.png)

11. Calcula el número de empleados que trabajan en cada uno de los departamentos. El resultado de esta consulta también tiene que incluir aquellos departamentos que no tienen ningún empleado asociado.
![Punto Once](/images/Resumen/punto_11.png)

12. Calcula el número de empleados que trabajan en cada unos de los departamentos que tienen un presupuesto mayor a 200000 euros.
![Punto Doce](/images/Resumen/punto_12.png)

## Subconsultas
**Con operadores básicos de comparación**

1. Devuelve un listado con todos los empleados que tiene el departamento de Sistemas. (Sin utilizar INNER JOIN).
![Punto Uno](/images/Subconsultas/punto_1.PNG)

2. Devuelve el nombre del departamento con mayor presupuesto y la cantidad que tiene asignada.
![Punto Dos](/images/Subconsultas/punto_2.PNG)

3. Devuelve el nombre del departamento con menor presupuesto y la cantidad que tiene asignada.
![Punto Tres](/images/Subconsultas/punto_3.PNG)

**Subconsultas con ALL y ANY**

4. Devuelve el nombre del departamento con mayor presupuesto y la cantidad que tiene asignada. Sin hacer uso de MAX, ORDER BY ni LIMIT.
![Punto Cuatro](/images/Subconsultas/punto_4.PNG)

5. Devuelve el nombre del departamento con menor presupuesto y la cantidad que tiene asignada. Sin hacer uso de MIN, ORDER BY ni LIMIT.
![Punto Cinco](/images/Subconsultas/punto_5.PNG)

6. Devuelve los nombres de los departamentos que tienen empleados asociados. (Utilizando ALL o ANY).
![Punto Seis](/images/Subconsultas/punto_6.PNG)

7. Devuelve los nombres de los departamentos que no tienen empleados asociados. (Utilizando ALL o ANY).
![Punto Siete](/images/Subconsultas/punto_7.PNG)

**Subconsultas con IN y NOT IN**

8. Devuelve los nombres de los departamentos que tienen empleados asociados. (Utilizando IN o NOT IN).
![Punto Ocho](/images/Subconsultas/punto_8.PNG)

9. Devuelve los nombres de los departamentos que no tienen empleados asociados. (Utilizando IN o NOT IN).
![Punto Nueve](/images/Subconsultas/punto_9.PNG)

**Subconsultas con EXISTS y NOT EXISTS**

10. Devuelve los nombres de los departamentos que tienen empleados asociados. (Utilizando EXISTS o NOT EXISTS).
![Punto Diez](/images/Subconsultas/punto_10.PNG)

11. Devuelve los nombres de los departamentos que tienen empleados asociados. (Utilizando EXISTS o NOT EXISTS).
![Punto Once](/images/Subconsultas/punto_11.PNG)
