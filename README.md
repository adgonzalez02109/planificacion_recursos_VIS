# planificacion_recursos_VIS

¿Que tan bueno es el estado planeando recursos?
  Este visualiación corresponde a la Información del Formulario Único Territorial sobre la Categoría de Gastos de Inversión proveido por la Contaduría General de la Nación, y muestra la diferencia entre el PRESUPUESTO INICIAL y el PRESUPUESTO DEFINTIVO en un subconjunto de 10000 proyectos reportados. En color rojo se ven los que tuvieron un PRESUPUESTO DEFINITIVO mayor a PRESUPUESTO INICIAL y en color verde se pueden ver los que tuvieron el PRESUPUESTO INICIAL mayor al PRESUPUESTO DEFINITIVO. Esta visualización evidencia la gran diferencia entre lo que se proyecta gastar y lo que se gasta en definitiva especialmente en los proyectos de presupuestos menores a los dos millones y en los cuales se terminan gastando en lo casos mas grandes hasta casi 10 millones.
  Los circulos de colores en la parte superior de la visualización permiten filtrar los datos y el circulo grid muestra ambas categorias.

  WHAT.
 
  El tipo de datos del que proviene la visualización es tabla, y fue extraida de la siguiente URL: https://www.datos.gov.co/api/views/g3mg-je4i/rows.csv?accessType=DOWNLOAD
  
  Los datos usados para esta visualización fueron:
 
  1. PRESUPUESTO INICIAL, PRESUPUESTO DEFINITIVO: datos ordenados y secuenciales que corresponden a valores en COP.
  
  2. diferencia: dato ordenado y divergente debido a que la diferencia puede ser positiva o negativa, aunque para la visualización se tomó el valor absoluto para asociarlo al radio de los circulos.
  <br><br><br>
  WHY.
  
  Locate trends and outliners: A partir de los filtros de los circulos de la parte superior se puede preguntar por los gastos con diferencias positivas o negativas (target known) y se visualiza en que margen se manejan (location unknown)
 
  Browse topology: Teniendo en cuenta la superposición de circulos y el radio de los mismos se pueden buscar topologias respecto a la dispersión de los gastos.
  Summarize features: La visualización pretende resumir en una sola vista el estado de los gastos mostrandolos todos.

  HOW.
  
  Las marcas de la visualización son los puntos, que en este caso no tienen fill, y los canales son la ubicación espacial respecto al eje X, el area de los circulos y los colores.
 
  Express by size and color hue: Permite expresar por medio del color y los tamaños la diferencia entre lo presupuestado inicialmente y lo definitivo.
 
  Superimpose: Superpone los datos de las diferencias negativas y positivas.
  
  Tecnologias: Las herramientas usadas fueron d3v5 javascript, css y html.
  
  Autor: Alvaro Diego Gonzalez Vesga
