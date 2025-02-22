OPERACIONES DE CONJUNTOS
Explicación del código:
1.	Conjunto de ciudadanos: Se crea un conjunto totalCiudadanos que contiene 500 ciudadanos numerados del ciudadano_1 al ciudadano_500.
2.	Ciudadanos vacunados con Pfizer: Creamos un conjunto vacunadosPfizer que contiene a los ciudadanos desde ciudadano_1 hasta ciudadano_75, quienes han recibido la vacuna de Pfizer.
3.	Ciudadanos vacunados con AstraZeneca: Creamos un conjunto vacunadosAstraZeneca que contiene a los ciudadanos desde ciudadano_76 hasta ciudadano_150, quienes han recibido la vacuna de AstraZeneca.
4.	Ciudadanos vacunados con ambas vacunas: Creamos un conjunto vacunadosAmbas con los ciudadanos entre ciudadano_51 y ciudadano_85 que han recibido ambas vacunas. Estos ciudadanos se añaden a los conjuntos de Pfizer y AstraZeneca.
5.	Operaciones de conjuntos:
	Listado de todos los ciudadanos: Imprime todos los ciudadanos generados.
	Listado de ciudadanos no vacunados: Utiliza la operación Except junto con Union para obtener aquellos ciudadanos que no están en los conjuntos de vacunados con ninguna de las dos vacunas.
	Listado de ciudadanos que recibieron ambas vacunas: Utiliza la operación Intersect para obtener los ciudadanos que están en ambos conjuntos de vacunados (Pfizer y AstraZeneca).
	Listado de ciudadanos que solo recibieron la vacuna de Pfizer: Utiliza la operación Except para obtener los ciudadanos que solo han recibido Pfizer, excluyendo a los que también recibieron AstraZeneca.
	Listado de ciudadanos que solo recibieron la vacuna de AstraZeneca: Utiliza la operación Except para obtener los ciudadanos que solo han recibido AstraZeneca, excluyendo a los que también recibieron Pfizer.
