[img1]: C:/Users/fisiatria2-/Pictures/merienda.jpg
#MANUAL ACTUALIZACION DE PRECIOS SERVICIO TERAPÉUTICO, EXÁMENES DE LABORATORIO Y PLANTILLAS DE PRESUPUESTO
---

##Preliminares:

1. Ingresar a [JasperSoft](http://192.168.6.7:8080/jasperserver/flow.html?_flowId=searchFlow) y descargar el reporte **"Baremos Procedimientos y Servicios"** como archivo CSV
![merienda][img1]
2. Abrir una hoja de Excel nueva
3. Ir a la pestaña Datos, Desde texto y seleccionar el archivo que se encuentra Z:/COSTOS/MONTOS PRESUPUESTO/PRECIOS/BAREMOS_EXCEL.csv
4. Ingresar una nueva hoja en el archivo de excel
5. Repetir las indicaciones del paso 3, pero esta vez ir a la ruta en la cual se encuentra el archivo con el reporte **"Baremos Procedimientos y Servicios"**
Seleccionar el archivo **"Baremos Pro..."** 
En el asistente seleccionar: 
	- Delimitados
	- Origen del archivo: 65001:Unicode(UTF-8)
	- Tildar la opción "Mis datos tienen encabezados"
	- Click en **Siguiente**
	- Tildar Coma, click en **Finalizar**
	- Click en Aceptar
El archivo descargado contiene una serie de campos en blanco y títulos que se repiten y que no son útiles para realizar los cálculos, por lo que se hace necesario eliminarlos y ajustar la tabla para tal fin.
6. Seleccionar toda la columna B, desde el encabezado, y eliminar (tip: Ctrl + -)
7. Con la columna B aún seleccionada, ubicar en la barra del menú la opción **Buscar y Seleccionar** que se encuentra al final en la pestaña _Inicio_:
	- Seleccionar "Ir a Especial..."
	- Celdas en Blanco
	- Eliminar (tip: Ctrl + -)
	- Seleccionar "Toda la fila"
8. Seleccionar la primera celda de la tabla
9. Colocar filtro y filtrar por la palabra del encabezado (Si seleccionó la celda "A1", colocar la palabra "Código")
10. Seleccionar todas las filas que se muestran y eliminarlas (tip: Ctrl + -)