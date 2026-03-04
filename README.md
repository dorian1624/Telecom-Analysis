# Telecom-Analysis

## Objetivo
Se busca tener un analísis de la empresa ConnectaTel de operaciones en México y Colombia.
En este analisis se buscara entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes), entre ellos patrones de uso, comportamientos atipicos y segmentos de clientes con necesidades diferentes, todo con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

Se han proporicionado 3 datasets:
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Para el analísis se tomaron varios puntos para poder llegar a una conclusión:
1. Se identificaron los problemas de calidad en los dataset, como seria contar valores nulos, detectar sentinels y revisar fechas fuera de rango
2. Se realizó una limpieza básica  reemplazando sentinels, convertir fechas, imputar o marcar NA.
3. Se realizó un resumen estadistico para poder revisar las medidas clave en variables categóricas y numéricas.
4. Una vez limpiado los datasets se crearon visualizaciones de los outliers mediante gráficos de bigotes (boxplots) e histogramas.
5. Se segmentaron los datos basado en reglas claras y visualizar proporciones.
6. Por último se redactan las conclusiones y datos encontrados.

## Instrucciones de apertura del archivo (Google Colab)
1. Descarga el archivo de Python de esta en este archivo.
2. Entra a la página de Google Colab
3. Ingresa con tu cuenta de google
4. Aparecera una ventana emergente en la cual en la parte inferior izquierda aparecerá un boton azul con la leyenda Nuevo Notebook, presionelo.
5. En seguida del lado derecho de la pantalla aparecerán varios iconos, habra de entrar al icono de carpeta.
6. Se desplegará una ventana en la cual en la parte superior aparecerá el icono de subir archivo representado con una flecha hacia arriba, habrá que presionarlo
7. Una vez presionado, aparecera su ventana de buscqueda en su ordenador y seleccione el archivo descargado previamente
