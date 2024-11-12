Este proyecto se centra en optimizar la movilidad sostenible para turistas que buscan 
acceder a atractivos turísticos en áreas urbanas. La falta de opciones de transporte sostenible 
ha generado la necesidad de investigar rutas alternativas que permitan una conexión rápida y ecológica 
entre hoteles y puntos de interés. Para ello, se emplean estaciones de bicicletas y una red de 
ciclorutas para mejorar la experiencia del turista, minimizando las distancias de traslado y promoviendo el uso de transporte no motorizado.

El proyecto busca crear mapas interactivos que identifiquen las rutas de menor distancia desde los hoteles a los atractivos turísticos,
integrando estaciones de bicicletas y ciclorutas como opciones de movilidad sostenible. Además, de identificar las oportunidades de recuperación 
del rio Medellín, esto mediante analisis de proximidad, diagnostico.

Datos Utilizados:
Atractivos turísticos (Ecoparques, zonas verdes)
Red ciclista y ciclorrutas
Ubicación de hoteles y estaciones de bicicletas

Metodología:

Análisis Geoespacial: Usando datos de coordenadas de latitud y longitud con archivos geojson, se realiza un análisis de proximidad para identificar las rutas de menor distancia entre hoteles y los puntos de interés turísticos.
Mapas Interactivos: Los resultados se presentan en mapas interactivos realizados con las libreria geopandas y folium , permitiendo una visualización dinámica de las rutas óptimas.
Simulación de Tráfico Turístico: Se simula la afluencia de turistas y se evalúan diferentes rutas de acuerdo con la accesibilidad y la conveniencia de las ciclorutas.

Los principales archivos que se usaron para realizar el análisis fueron:
Geo.ipynb(archivo principal): Se uso para realizar un análisis de aproximidad y análisis geoespacial.
Analisis.ipynb: Se uso para realizar un análisis estadístico y observatorio sobre los datos, generando algunas métricas de interes.

Impacto:
Este proyecto ofrece una solución de movilidad que reduce la congestión y fomenta el turismo sostenible, mejorando la experiencia turística en términos de accesibilidad y
reducción del impacto ambiental.

Oportunidades:
Desarrollar Servicios de Transporte Acuático con Conexiones a EnCicla
Descripción: Implementar un sistema de transporte acuático a lo largo del río, con estaciones en puntos clave que se conecten a estaciones de EnCicla.
Implementación: Construir muelles en puntos estratégicos y crear una red de transporte acuático que permita a los visitantes y locales desplazarse de manera sostenible.
Las estaciones de EnCicla podrían ubicarse cerca de estos muelles para facilitar la combinación de medios de transporte.
Beneficio: Este enfoque multimodal (bicicleta + barco) diversifica las opciones de transporte sostenible y mejora el atractivo turístico del río.

Conservación y Restauración de Áreas Naturales Cercanas al Río
Descripción: Implementar programas de restauración ecológica a lo largo del río, especialmente en áreas cercanas a ciclorutas y sitios turísticos.
Implementación: Colaborar con organizaciones ambientales para reforestar áreas degradadas y restaurar hábitats naturales. Esto puede incluir señalización educativa en las ciclorutas para informar a los usuarios sobre la importancia de la conservación del río.
Beneficio: Aumenta el valor ecológico y estético del río, y educa al público sobre la importancia de conservar los ecosistemas acuáticos.

 
