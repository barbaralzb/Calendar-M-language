# Buscar la fecha minima y maxima de dos tablas
Aquí hago otra request con propiedades avanzadas en lenguaje M en Power Query donde en parámetros le paso el nombre de mis dos tablas a evaluar. Saco la fecha mínima y la fecha maxima y luego la paso a la función FunctionCalendar() que recibe estos dos parámetros (fecha mínima y fecha máxima).

Huzo GetMinAndMaxYearsFromTwoTables ya que es obligacion que una tabla de dimension Calendario empiece un 1/01 y termine un 31/12 y en esta funcion le paso solamnete el año o de forma dinamica de las dos tablas seleccionadas para tener una **consistencia temporal**, al comenzar el 1 de enero nos aseguramos que todos los años tengan la misma cantidad de dias en la tabla.
