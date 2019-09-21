## Ejercicios 1.
### Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.

El servidor que se ha elegido es [HP ProLiant ML110 Gen9 E5-1620v3/4GB/1TB](http://www.pccomponentes.com/hp_proliant_ml110_gen9_e5_1620v3_4gb_1tb.html).

Vamos a calcular su coste de amotización en base al artículo proporcionado: [Cómo calcular el coste de amortización de un ordenador portátil](http://www.infoautonomos.com/consultas-a-la-comunidad/988/)

Para calcular la amortización, hay que tener en cuenta el precio final del artículo sin IVA, en este caso, el coste del IVA sería de 220,24 €, y el del servidor de 1.048,76€

Para cada año de los primeros cuatro, se deduce una amortización máxima de un 25% del coste del servidor (sin IVA), por ello, lo que habría que pagar cada año sería: 
	- 1048,76€ * 0,25	=	262,19€

** Cálculo de la amortización a 7 años **
	- Primer Año  :	1048,76€ * 0,25	=	262,19€
	- Segundo Año :	1048,76€ * 0,25	=	262,19€
	- Tercer Año  :	1048,76€ * 0,15 =	157,31€
	- Cuarto Año  : 1048,76€ * 0,15 =	157,31€
	- Quinto Año  : 1048,76€ * 0,10 =	104,88€
	- Sexto Año   : 1048,76€ * 0,05 =	52,438€
	- Séptimo Año : 1048,76€ * 0,05 =	52,438€


## Ejercicio 2: 
### Usando las tablas de precios de servicios de alojamiento en Internet y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

Servicio de alojamiento en Internet: [Strato](https://www.strato.es/)
Proveedor de servicios en la nube: [Azure](https://azure.microsoft.com/es-es/pricing/details/virtual-machines/#Linux)

** Coste de Strato
 Por una máquina de características similares: 1,79€ al mes * 12 meses = 21,48 € al año


** Si la infraestructura comprada se usase el 1% del tiempo 
 Coste año * 1% = ((Coste en un mes) * 12 ) * 1% = ((Coste por hora * 24 horas * 30 días) * 12 ) * 1% = ((0,0152/h * 24 * 30 ) * 12 ) * 1% = (131,328 €) * 1% = 1,31328 €          
                   

** Si la infraestructura se usase el 10% del tiempo
 Coste año * 10% = ((Coste en un mes) * 12 ) * 10% = ((Coste por hora * 24 horas * 30 días) * 12 ) * 10% = ((0,0152/h * 24 * 30 ) * 12 ) * 10% = (131,328 €) * 10% = 13,1328 € 

## Ejercicio 3:
### En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?

- Modelo de procesador: Intel(R) Core(TM) i7-4720HQ CPU @ 2.60GHz
- ¿Qué aparece como salida de esa orden?: [Resultado salida de la orden](https://github.com/miguelangelrdguez/IV-19-20/ejercicios/tema1/flags.txt)
- Si usas una máquina virtual ¿qué resultado da?: No devuelve nada
- ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?: Sucede lo mismo que con la máquina virtual

