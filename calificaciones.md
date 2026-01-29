Algoritmo promedio_parcial
	Escribir "ingrese la nota del parcial 1 sobre 100"
	Leer parcial_1
	Escribir "ingrese la nota del parcial 2 sobre 100"
	Leer parcial_2
	Escribir "ingrese la nota de participación sobre 100"
	Leer participacion
	Escribir "ingrese la nota de examen final sobre 100"
	Leer examen_final
	promedio<- (parcial_1 * 0.25 + parcial_2 * 0.25 + participacion * 0.20 + examen_final * 0.30)
	Escribir "El promedio ponderado del curso es ", promedio
FinAlgoritmo
