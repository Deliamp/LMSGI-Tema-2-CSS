# INTRODUCCIÓN A LOS LENGUAJES DE MARCA - LLSGI
## TEMA 2 - Introducción al HTML
**Tarea**
**Alumna: Delia Montero Peralta**

**1º - Título y descripción en la cabecera (head) totalmente descriptivos con el tema.**

		Title: Pymes y MicroPymes
		meta charset="utf-8"
		meta name="description" content="Pymes (pequeñas y medianas empresas) o MicroPymes (microempresas) en la Unión Europea"
	

**2º - Un rótulo informativo (h1-h6).**

	He utilizado en el código seis títulos (h1-h6) a lo largo de todo él para demostrar que se utilizarlos.
	1. h1: Pequeñas empresas en la Unión Europea
	2. h2: Clasificación de empresas por tamaño: Pymes y MicroPymes
	3. h3: Tabla diferenciadora
	4. h4: Legislación e información sobre Pymes	
	5. h5: Html validado con validator.w3.org
	6. h6: Web diseñada por Delia Montero Peralta

**3º - Una imagen (o varias) relativa al tema que he elegido.**

He utilizado tres imágenes sobre el tema. Tras localizarlas en Internet las he descargado y he utilizado para ajustarlas la aplicación online [Webresizer]( http://webresizer.com/resizer).

Para poder diferenciar entre *relative path* y *absolute path* he realizado la actividad de dos formas. La primera con *relative path* (**index**) y la segunda con *absolute path* (**index2**).

**NOTA:**
Al no poder crear dentro del repositorio un directorio img en el cual colocar las imágenes para que al cargarse la página con *relative path* pueda reproducirlas, las he colgado tal cual sin estar en un directorio. No obstante soy consciente de que deben ir dentro de un directorio img. Para poder visualizarlas directamente al utilizar la url del repositorio en GitHub he creado un archivo llamado index2.html en el cual, utilizando *absolute path* se enlazan las imágenes utilizadas y ya tratadas desde un repositorio en la nube.

Al ajustar las imágenes con Webresizer su tamaño ha quedado así:

1. Imagen Pyme1_opt: Ajustada de 44,46 kb a 23,17 Kb

2. Imagen Pyme2_opt: Ajustada de 47,51 Kb a 27,61 Kb

3. Imagen Pyme3_opt: Ajustada de 73,52 Kb a 34,68 Kb


El origen de cada imagen es el siguiente:

1. Url de Pyme1_opt:
http://lovemarketingmadrid.com/images/articulos/Sabes-c%C3%B3mo-aumentar-las-ventas-en-una-pyme.jpg

2. Url de Pyme2_opt: 
http://static.elmundo.sv/wp-content/uploads/2016/04/Mypes-PEQUE%C3%91A-EMPRESA.jpg

3. Url de Pyme3_opt:
http://conceptodefinicion.de/wp-content/uploads/2016/06/Mediana_Empresa.jpg

Para realizar la página con *absolute path* he colgado las imágenes ajustadas en [imgbb](https://es.imgbb.com)

*Absolute path:*

1. Url de Pyme1_opt:  
https://ibb.co/djMDLw

2. Url de Pyme2_opt:  
https://ibb.co/iQiztG

3. Url de Pyme3_opt:  
https://es.imgbb.com/

**4º - Una tabla de datos relacionados con el tema.**
<table id="tipos">
			<thead>
				<tr>
					<th>Mediana</th>
					<th>Pequeña</th>
					<th>Micro</th>
				</tr>
			</thead>
			<tbody>
						<tr>
					<td><p>Menos de 250 trabajadores</p></td>
					<td><p>Menos de 50 trabajadores</p></td>
					<td><p>Menos de 10 trabajadores</p></td>
				</tr>
				<tr>
					<td><p>Menos de  50 M € Fact.</p></td>
					<td><p>Menos de  10 M €  Fact.</p></td>
					<td><p>Menos de  2 M €  Fact.</p></td>
				</tr>
				<tr>
					<td><p>Menos de  43 M €  Balance</p></td>
					<td><p>Menos de  10 M €  Balance</p></td>
					<td><p>Menos de  2 M €  Balance</p></td>
				</tr>
			</tbody>
		</table>

**5º - Una lista con 3 enlaces. Cada enlace de la lista debe conducir a una página web relacionada con el tema elegido.**
		<ul>
 			 <li>
				<a href="http://www.ipyme.org/es-ES/UnionEuropea/UnionEuropea/PoliticaEuropea/Marco/Paginas/NuevaDefinicionPYME.aspx" target="_blank">Definición de PYME en la UE</a>
			</li>
			<li>
				<a href="http://www.boe.es/buscar/doc.php?id=DOUE-L-2014-81403" target="_blank">Reglamento (UE) nº 651/2014 de la Comisión Europea</a>
			</li>
			<li>
				<a href="https://cincodias.elpais.com/cincodias/2016/08/02/pyme/1470120203_791862.html" target="_blank">Diferencias entre micro, pequeña y mediana empresa</a>
			</li>
</ul>

**6º - La página completa debe ser menor de 100Kb.**

1. En el caso de **index** (utilizando *relative path*) el tamaño del archivo html junto con el directorio en donde se encuentran las imágenes utilizadas ocupa 87,5 Kb. En disco ocupa 92,0 Kb.
2. En el caso  de **index2** (utilizando *absolute path*) el tamaño del archivo html 2,17 Kb. En disco ocupa 4,0 Kb.

**NOTAS:**

- El título (Title) tiene una longitud de 8 palabras, y la descripción (Description) 24 palabras.
- He usado UTF8.
- La página la he validado con [validator.w3.org](https://validator.w3.org/). No muestra ningún error tanto para **index** como para **index2** (Document checking completed. No errors or warnings to show).
- Para ubicar las imágenes he utilizado **relative path** y **absolute path** (archivos index.html e index2.html).
- He comprobado el buen funcionamiento de la página en Chrome, Explorer, Firefox y Opera. En todos estos navegadores funciona perfectamente.

