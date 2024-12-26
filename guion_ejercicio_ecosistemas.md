# Instrucciones para realizar el trabajo final sobre las prácticas de ecología

> + **_Tipo de material_**: <span style="display: inline-block; font-size: 12px; color: white; background-color: #4caf50; border-radius: 5px; padding: 5px; font-weight: bold;"> Prácticas</span> 
> + **_Versión_**: 2024-2025
> + **_Asignatura (grado)_**: Ecología (CCAA)
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **_Duración_**: Unas 5 horas en casa.

![portada](https://raw.githubusercontent.com/aprendiendo-cosas/T_descripcion_tipos_ecosistemas_ecologia_ccaa/refs/heads/main/imagenes/portada.png)



## Objetivos 

La finalidad última de este guión es ayudar a organizar el trabajo que los distintos equipos tienen que realizar sobre los tipos de ecosistemas de los que son responsables. De manera más específica, tiene los siguientes objetivos:

+ Disciplinares: En este caso el objetivo único es que los estudiantes entiendan de manera generalista y holística cuestiones clave de los distintos tipos de ecosistemas estudiados. Dicho de otra forma, se trata de fijar el conociminto ya adquirido sobre la composición, estructura y funcionamiento de los ecosistemas. 
+ Competenciales: Relacionados con la adquisición de competencias genéricas.

  + Mejorar la habilidad para buscar bibliografía científica.
  + Desarrollar la visión crítica de la literatura científica, periodística, etc. Es decir, cultivar el espíritu crítico.
  + Promover la lectura comprensiva, el análisis y la extracción sintética de información de la bibliografía consultada.
  + Entrenar las capacidades de redacción y de discusión.
  + Fomentar la capacidad de establecer puentes entre distintas disciplinas. 
  + Afinar la capacidad de los estudiantes de relacionar conceptos teóricos con problemas ambientales a abordar.
  + Trabajar en equipo.
  + Aprender a publicar contenido en internet. 



## Características del trabajo

Antes de detallar el "cómo" se presentará el trabajo, repasemos brevemente de qué consta el trabajo. Para ello, lo primero que debes de hacer es releer [este](https://raw.githack.com/aprendiendo-cosas/P_plan_practicas_ccaa/2024_2025/guion_plan_practicas.html) guión en el que se describen las prácticas de la asignatura. En él verás que el objetivo de las prácticas es generar un documento en el que se describen distintos tipos de ecosistema presentes en Sierra Nevada. En cada práctica hemos trabajado un aspecto concreto de dichos ecosistemas. De manera resumida, debemos de disponer de la siguiente información sobre cada tipo de ecosistema:

+ Un histograma de frecuencias que muestra la estructura poblacional de la especie que es responsable de la estructura del ecosistema en cuestión. 
  + A modo de recordatorio, [aquí](https://rawcdn.githack.com/aprendiendo-cosas/P_estructura_pobs_ecologia_CCAA/2024-2025/guion_estructura_poblaciones.html) está el guión en el que se describe cómo hicimos esto. 
  + Dependiendo del ecosistema en cuestión, el histograma tendrá formas diferentes. Además, podrá haber distintos histogramas por ecosistema según el caso.
  + También podéis generar histogramas a partir de fuentes de datos diferentes a las vistas en clase.
  + Además de incluir un histograma, es fundamental describirlo. Es decir, analizar la estructura de la población en cuestión. Esto implica aventurar en la medida de lo posible sobre la evolución de la población que presenta dicho histograma. 

+ Dinámica demográfica de las especies responsables de la estructura de cada ecosistema. La sección anterior nos permitió generar un histograma de frecuencias del tamaño/edad de los individuos de la población. Con esa información podemos inferir cómo se comportará el ecosistema a lo largo del tiempo, pero se trata de una fotografía fija de la dinámica poblacional. En esta práctica usamos Vensim para simular el comportamiento de la población en a lo largo del tiempo. En [este](https://raw.githack.com/aprendiendo-cosas/P_modelizacion_interacciones_ecologia_ccaa/2024_2025/guion_practica_modelizacion.html) guión puedes ver (Sección 7) cómo generar un modelo de dinámica poblacional de los distintos ecosistemas de Sierra Nevada. En el guión mencionado hay instrucciones específicas para cada tipo de ecosistema.
  
+ Información sobre la diversidad del ecosistema seleccionado. Después de conocer la estructura de la población más importante del ecosistema en cuestión, llega el momento de hablar de la diversidad de especies que tiene. En esta ocasión se realizará un análisis comparativo de la diversidad de todos los ecosistemas estudiados. En [este](https://raw.githack.com/aprendiendo-cosas/P_shannon_ecologia_ccaa/2024_2025/guion_practica_mapa_biodiversidad.html) guión se describe esta práctica. Al final del mismo podrás ver exactamente lo que tienes que generar para el ecosistema que te corresponda. Ahí va un resumen:
  + Tabla mostrando la diversidad de cada tipo de ecosistema. Tendrás que marcar con un color diferente el ecosistema que te haya tocado. También explicar por qué tu ecosistema tiene la diversidad que tiene en comparación con los demás. 
  + Mapa de la diversidad del ecosistema seleccionado. Esto no es obligatorio, pero es fácil de hacer. Basta con hacer un clip (herramienta "cortar raster por capa de máscara" en QGIS) entre la capa raster con el índice de Shannon que obtuvimos para toda Sierra Nevada y la delimitación de tu ecosistema. Este mapa te dará información sobre cómo se distribuye la diversidad dentro del ecosistema. Podrás contestar a preguntas como: ¿cómo varía la distribución del ecosistema A de este a oeste? ¿a qué se debe ese patrón?. Si incluyes este mapa, analízalo a la luz de lo visto en la asignatura.

+ Información sobre el funcionamiento de cada tipo de ecosistema. Tras analizar algunos elementos estructurales, es el momento de conocer mejor cómo funciona el ecosistema. En concreto, trabajamos con la producción primaria, que es fácilmente cuantificable usando imágenes de satélite. Al final del guión correspondiente ([aquí](https://raw.githack.com/aprendiendo-cosas/P_NDVI_ecologia_ccaa/2024-2025/guion_ndvi.html)) puedes ver con detalle lo que os recomiendo incluir sobre este aspecto. Lo resumo aquí también:
  + Valor promedio de la tendencia de NDVI para cada ecosistema. Se muestra como una tabla que tendrá un valor para cada ecosistema. Nos permitirá comparar si hay diferencias entre las tendencias de NDVI de distintos ecosistemas. Podremos contestar a preguntas de este tipo: ¿tienen los pastizales de alta montaña (por ejemplo) una tendencia más intensa hacia producir más biomasa que los encinares?
  + Valor promedio del NDVI para cada ecosistema. Esto nos dará información sobre la biomasa fotosintéticamente activa que hay en cada tipo de ecosistema. Podremos saber si, por ejemplo, los encinares tienen más biomasa que los bosques de ribera.
  + También se pueden generar mapas de tendencias de NDVI o del NDVI promedio de cada ecosistema. Para hacer esto, bastará con recortar los rasters obtenidos en la práctica con la delimitación de cada tipo de ecosistema (herramienta "cortar raster por capa de máscara" en QGIS). 

Hasta aquí se muestran los descriptores con los que hemos trabajado en las sesiones prácticas. Además de esa información, podéis incluir la siguiente:

+ Un mapa de distribución del ecosistema en cuestión. En su momento os pasé cartografía sobre esto.
+ Breves textos descriptivos sobre la distribución del ecosistema en Sierra Nevada o quizás en otros territorios cercanos.
+ Imágenes tomadas en campo cuando fuimos a Sierra Nevada o procedentes de cualquier otra fuente.
+ Esquemas sobre la estructura del ecosistema. Los diagramas o esquemas son muy útiles para resumir cuestiones como la estructura y el funcionamiento de los ecosistemas. A mí me gusta hacerlos con draw.io, la aplicación con la que hago habitualmente los flujos de trabajo. Pero también se pueden hacer con PowerPoint, por ejemplo. A modo de ejemplo puedes descargar aquí y ver a continuación un esquema que muestra la estructura y funcionamiento de la dehesa de encinas (un tipo de ecosistema que no hemos estudiado en Sierra Nevada). Además, verás que se describen los "servicios ecosistémicos" como aquellos bienes y productos que los ecosistemas proveen a las sociedades humanas.

<iframe frameborder="0" style="width:100%;height:653px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=ejemplo_dehesa.drawio#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%22feId3qYxikT-9Foy4yp1%22%3E7V1Zl5s4Fv419TAPzdGGQI%2BpSqo753TPZCYz0z2PlE25SGzjg3Et%2BfUjGWSjxSAwi6sq9ZAYIQTc%2B91VV%2BIK36yef82izcMf6TxeXiEwf77CH68QgghR%2Fp9oeZEtQVC0LLJkXrSBY8PX5EdcdpStu2Qeb8u2oilP02WebNTGWbpex7NcaYuyLH1Su92ny7nSsIkWsfIYouHrLFrGRrc%2Fk3n%2BULSGKDi2%2FxYniwd5Z0hZcWYVyc7lwNuHaJ4%2BVZrwpyt8k6VpXvxaPd%2FES0E9lS63J87%2B63Z7O8%2B%2Bh%2F99vL3L6BOgz9HDL4Ff3OsxWu7KF%2FgaZ4%2FJLEm3vDmepdtkm1%2Fd4KsPbJXMROP%2B0fIX%2Bb7ytbJ4nXd%2BDAiA8RzGnRZZutuYt6t%2FrzjL42cb46O7ZazTlqMyTldxnr3wfuVV1C8RWQKSlIdPR%2BbigBRtD1XG4rIxKgG1OAx9pA7%2FURKoBbFC0kwrTqr1PBajwCt8%2FfSQ5PHXTTQTZ5%2B44PG2h3y1LE%2FfJ8vlTbpMs%2F21%2BPb22g8Ab9%2FmWfo9lmfW6Zpffu3IgCNHdQ6YlJaUtRAW2AgLhiKsKQz%2F2aa8IYtnWRzlyWNqEJq%2FW65SM1omizX%2FPeMEijnhrgUFEq4gPpQnVsl8Li6%2FzuJt8qPEoaD3Jk3W%2Bf6l%2FOsr%2F6MYa5dzAdyrOHiKIVXuyaZ0nX8tnxGWxxUGU4oxAMPwsjyLqMlNCC3cHI6Z7HI1ClA0ysF0VWnlj4t89ApUyoGjzSisUhKxUSmJDUreRD%2Bid6k3WjBMenvAFAWbJAzGPnaxfghkzVpjZHsZhK9AazB32zUhJU1j9SVLH5NtIlzva7wWEVEsQBNl%2FOXfozJpwUdpZy1mFY%2BqTOClKhMCVGVCmEkrJAMfRQTgYIbTQfNOr0zgCQ7UKhMrJdlghDRRd8Ojl1lFlbzs0w1cM6yTVcLfOJXqZbuLl%2BLgvoj4ucpYvk9l487n8ixW5MmievryY9K7byJthcAyuouXJX%2F523KuCM5FdyWfOQPKaLUWLUU6Q4WXe3aH%2FyifpwVASWCRdLoUoLrjPxbixxceciebJK%2FCtujCb3noZWCT3z3ZbAUgtg%2FRRjTOlulu3lpZzKM4vJ8Z%2BBNImoXx3b07kmS6yB1JEGjxISHYw9i0ZcACKEo9GgykWHwHd6%2BNOTtJmtbmjFGNYhbfmECLNQPUk0%2FRP7lMPfzveLWJsyjfZWZAeIRuA1Sj7abIW98nz8IWNutIDtv7cBbPZu6wPfDaOXSjPiclYiHkypb4jJqAJcBjLAAw5MrYJwAHJkNOdOmfN33nO7I0j%2FIkFcZOeKqTM6U8%2BwtkHgwCAhknZ4jDAISKoGDsAcqdOhgCiMjBilWYFjBPXsqoGMkiRdjjnAsJCRAgjIYMD8U1M7diitF6%2FkHM4hyJrnBJstRkEefHzQ0A4HhGTt%2Bg9hyK53KSqNk7tPkFsi2LlyLtXB3LTtfyDl%2BEP3Vkf%2BChKu%2BZOpPhM88%2Fcp4CpA6%2FTXfZLC5HPHLOuAkCnt9m3DzKFnFujLtHxIFCZ4DEYXbkJ0icQUJCfhrQEKNSt%2FcEkoZxhwaJOdPzEyTdQYIDjzIQgoD4mEAK%2FZ5A0jDu0CChP0HSI0gQ97X37gEhgDEchEFPKGkaeGiY2MLZnzDpChNIPJ8EGDHIkE%2BoH%2BKeYNI0cGeY2DIyt8vdt0NWLV7H2WKfUftYxn31%2BRG%2FQruRUjLYhCwHi8yopVn%2BkC7SdbT8dGzVcHvs83uabkpof4vz%2FKWs0RKZPRX4%2FAWyl79EyAREGCJb%2FidG9AIemJcNH5%2FLexRHL9WjL3GWcNaItGMhPmXeJyrEzSkOu739yOj%2Bbs9J%2Fld5d1geF08jqtCK4%2BPDiIOXyoH%2BKI7SSUqYFsCu61iKXwHUmo4wcJR3Z0E%2BK2wjZFJwgSquYAOmeoIP0%2BBDXhV8XM3FmXYAMjVp7gfaEK6qHmuzWVifWxnYAyAO2aRWidHe5vlClTC%2BrdLIVpU13DSfRGEdrSpSLGeSfhem9Uu6Tcok212a5%2BnKNve0N8LX0ez7Yq9Cqum2%2FZ9leioXKsXiXpnJf%2F4HSjVRlOaKg3m0fTi6b6UCWT0vRIGzl6TbwEs427bedreWU15x9ukxLma%2BrFOVpUJxxQs6gZf6wqiRGW%2Bmwz%2BJi76m4t8r%2FOFvBg4ud6axuIw1TzyKvzYTjy1YKf1cLa%2FiGxJOLXxGQ7EZyiB9KmvviYL6qsXnriWe0JP0ga96kjR8Ra6AVAdD%2BwJIM%2BF%2B0DGHNKIvYCq0fdS3lWHfKuIcTKJl3MOiiX9S9tc2%2Ffb5%2BvOfn38lL%2FGPNfgFhRNLmt%2FFs75fxs9lLkSXnht6C65NXbyXK%2FGnylVVqmolSjXsxXPKhUN0fz7KpEoXmkKqTmyVPOgoY5C6yljv0doJyZALUqSlCDTJcBYxrIlYOJy7bcU9e7%2B4V8NKvxb3Y2B3pFCRwJ6wS9h42LURjE4LXTXF5jtCN%2BpZXcOhYBs6whaNBNtDFblEG%2B0I24CoA5GRVa4sxBkXtzbVyU33IURHHg0DFATAh1DUgPmKaWfc8Q8Z9X0YcP2BA1Y17diDABMSosAPKQLBaM5IVzMyhlSM5OsbOpj0pMzRyMp84khXUeajqfKqB%2FJuFLmvu7xdFXmoL7zQBxpakU870ddS6XWK9ixGQ6p9FHh7dX%2BwC1SxGKFHqyaDaOYGeCzwAWL8Mh9ya4M6yVF3qUCuWRu5kn5sRY66KnJMtal6fV3ECang%2FI1eKt3KJO9pMdakT66pdH4utT%2F%2FUTxBvyI6yXSp3dcqxRZWhbY5bjiIG%2FGE34WPrpaae%2FFIUBXHcDQn7AwZlFvKXIwM6pDWJ3B6Ep0A1oqC0Z%2FiM%2FvDGlFrvNpVE%2FUms1NPerz5lJS74OFxBI9qsT3qHNuH3Yxfb9idJCfVHm%2F3y%2FTpwzpZyXU29tS%2B1Y7ZkHphUbo7vtFI%2BO6oUk18g2nxLafUp%2FenpF9EPJl3KjwfpLhFxKPVrBU%2BR9NfujuFnUMaNg7qmZZodQVr40Cu4tPWL2O%2BHtL4tc9lrC7WLjg%2FprEWHEzsHhEYKGLjgTIWGX%2Fyw8HwNJd%2F9G9V6CuzKvpAAxoV6yYbU9qUfpO4wEP1TntFjrBPqnIk6vYhahCkySA9Um64v0BA3%2FfBMTfcOpTX7xOMkNWaehFAtwi5B%2BU%2FTnSMLk3PBw1pqQvU81bYTpvYgROB1sMMV4Ar9Dwg9UbCqWzVGc94Wjy3Vql6DgfUZzv1%2Fn5DcpSe1d1YIFiXStUfTa%2BfdRZcOqmDBiXUXpuHdrRYSDFZTTP8R9mlmClGhzE6puhenH%2FGdNnsBuipp%2B7JtLWDLecApwmfz4Ate10Wx0hUNVgcvT9tMFDsrO6wobueEm5joPQ36WygGvTC0OI8iYE6V5xt6WzsHQsp9wntQMln%2Bx5Uim5wj5mLoeKpqfPSbbUBhHq6OaiXQOMC2MpJZHrlT9ecBwQd6xd6E0OXPeUmLr9RKj37n%2FJxm5ainlLJU2zX0SWdOIZrOdJsURh2A29vOcS2eiLE9vuc9Hn1%2Fg2GnZ3ZX2qlQSejJl3L0HNG0TVxH4xUxuBuOEdKRDLN1exsqXQRHahElUH787bVHK79xxC4i1qvOd5KiXFS%2F%2B4SN1K%2BpTeJGzPhYqXsJGslatcvUE9Z0YZVFy3woOqi%2BaPht%2BsS05O4n6rAuq2%2BRrrH0xB46f3b1Tnru1ugvtbwDxl2WWVrkmRmnWypi0d5LARCfPwjnSSpu1aXm0I0r8DvPdQ5a%2FufaRYK91kI%2F3Rc7hVQxiWu%2FDfQVC1QztJaHJxCzhn4cF4hCS8LH5PvWQOQghAP%2Bp0KmLrsbNDPuovuoEGuoIGXMccRQtVI%2BaTetmKtVsTvO7ixJhDB1IjuS%2BM15PGxR9X9FEqLeVh9QTxECCOUMLFcDAL6ChL9znpU%2BkuvZqW5UYDuuDnCuQXouO9qQnt1xyRZ%2BstYcDdOXsF9D6ix9gjERFXv3Tcw0wcC4wY%2FcNripLGin%2FO2xxknX%2B0cZ421OY6Ozc7639hlxxHkp%2FV%2F%2F2JwcQk2GHhY%2BVMTbL53Zkat20ZRMKSKNMhi3NqYpbpNlu2del2UcbABE%2BQrhpajQK9jHU%2BObF8W%2BcRhtpsVn5AE8SzdJts8Xrl8V6TwmVQBHfi7ItD8hNLfd3kmvjksdsUFsfgacbx%2FkOLLw5o6UIW94RuMLhs0XyNKi5RM%2Fb7dNdF2DW1b7dutlZ8RyzeDpcuufiLztCict3O3%2BR2jP6I85TA2vwH9jviC%2Fan5wgy%2B%2FBqto7n4vNAmzWbJ2pSbvjliTWoqnBqKHcaMh4UdwZjskI6gjR2P0WwnuMFHBuljIn%2FG%2BcwbnEWTCg3RV5xMziVkcEl8gCuEi12yFJYzEV9iTiyq7U3xheoFamBqvhCDL7%2FtVtE6NffIf1OM0Odb2dR8MB2zj%2FF2lq42nJDzNNt7Z%2FvXu8u4bjO584Y9AH2XwEPut%2FrxHDQqt0IHbs3fpx99ajX7hNwyHbZ%2FcJIKHs2ibF18CPIxzd66ztMXCdiMz7icwabvJjnzEGd374czepHp1O4aNBXcl2ibJz%2FeV%2Bx5yAFcSuyJzNUxvydrTus3LR76qofJveZDetUIZ7K71PZ9qTcsI%2FrCtellxPwO2A2n4bfhszIXFVoOaEP4YZameTVrLr6t%2BUcqXF786f8%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E"></iframe>

+ Cualquier otra gráfica, mapa o esquema generado por vosotros o tomado de una publicación científica. En este sentido, os lanzo alguna idea:
  + En una de las prácticas de la asignatura de SIG, visteis con Jorge cómo extraer los valores de altura de los disitintos tipos de ecosistemas. Podéis incluir esa información también aquí. Como no sé si Jorge os ha enseñado a hacer mapas con QGIS, bastará con que hagáis un pantallazo de la capa en QGIS teniendo de fondo alguna fotografía aérea o imagen de satélite usando servicios WMS. 
  + En las sesiones prácticas de ecología nos ha faltado tiempo para hablar de factores abióticos y de cómo estos se manifiestan en los distintos tipos de ecosistemas. Sería interesante, por ejemplo, mostrar la temperatura media en la que habita cada ecosistema. O más interesante aún, comparar dicha temperatura media actual con la temperatura (o precipitación) prevista en las próximas décadas considerando distintos escenarios de emisión de gases de efecto invernadero. Esta información está disponible de manera provisional [aquí](https://portalrediam.cica.es/descargas/index.php/s/mxHMWXyHfrCxyNK?path=%2F04_RECURSOS_NATURALES%2F03_CLIMA%2F03_CAMBIO_CLIMATICO%2F03_PRECIPITACION%2F06_TREINTENA%2FESC_PRECIP_MEDIAS_TREINTENA_2000_2100) para la precipitación y [aquí](https://portalrediam.cica.es/descargas/index.php/s/mxHMWXyHfrCxyNK?path=%2F04_RECURSOS_NATURALES%2F03_CLIMA%2F03_CAMBIO_CLIMATICO%2F02_TEMPERATURA%2F06_TREINTENA%2FESC_TEMP_MEDIAS_TREINTENA_2000_2100) para la temperatura. En unos días (un par de semanas antes de que acabe el plazo de entrega), tendré fuentes de datos más fiables y fáciles de procesar sobre este asunto. En cuanto los tenga, los pondré por aquí. Si alguien tiene interés en esto, por favor, que me avise y vemos cómo hacerlo juntos.
+ Problemas de gestión. Tanto durante la salida de como en vuestras búsquedas por internet, habréis tomado conciencia de los principales problemas de gestión del ecosistema sobre el que habéis trabajado. Sería interesante enumerar y describir brevemente dichos problemas. Podéis añadir fotos o imágenes a esta descripción. 
+ Bibliografía. También sería interesante incluir una sección con las referencias bibliográficas utilizadas para realizar el trabajo. El próximo cuatrimestre aprenderemos a incluir bibliografía de forma semiautomática en un texto, pero por ahora bastará con poner la referencia usando un formato parecido a este: *[autor o autores], [nombre artículo o libro], [año], [nombre del libro o de la revista], [enlace de descarga o consulta]*.


Para terminar, en cada página web, cada miembro del grupo deberá de incluir lo siguiente:

+ Texto de atribuciones. Cada estudiante deberá de describir brevemente cuál ha sido su contribución al trabajo final.
+ Descripción de aprendizajes. Cada estudiante deberá de indicar al menos una cosa que haya aprendido de cada uno de sus compañeros de equipo.
+ (auto)críticas constructivas al trabajo propio y al del equipo como tal. En este último aspecto es importante no caer en descalificaciones. Solo cuestionar el trabajo propio y los problemas que hayan podido aparecer en el equipo.
+ Descripción de las principales dificultades que ha tenido cada miembro del equipo para hacer este trabajo.



## Presentación del trabajo
Como ya comentamos en clase, la idea es que cada equipo genere una especie de ficha sintética para cada tipo de ecosistema. Se trata de un documento con no demasiado texto, pero rico en esquemas, gráficos, imágenes y mapas. Para presentarlo generaremos una página web sencilla que contenga dicho material. En esta sección se describe cómo construir dicha web.

Usaremos *Google sites* para crear y publicar la página web. Se trata de un servicio de Google muy fácil de utilizar que nos permite crear páginas con contenido diverso en muy poco tiempo.

El siguiente vídeo muestra cómo crear la página web en *Google Sites*:

<iframe width="560" height="515" src="https://www.youtube.com/embed/A6v6LIoDHBo?si=LkNcwGqR_KYZ1qE7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



Además de lo que se dice en el vídeo, podéis incluir en los textos comentarios sobre cómo habéis procesado los datos o los problemas con los que os habéis encontrado. También cualquier otra información que consideréis relevante.



## Fecha, modo de entrega y criterios de calificación

Cada grupo deberá compartir la web en proceso de creación con mi cuenta fjbonet@gmail.com. La fecha de entrega definitiva será el 23 de enero a las 23:59. Cualquier cambio realizado en dicha web posterior a esa fecha, no será considerado.

Este trabajo supone el 40% de la nota total de la asignatura. Se calificará el desempeño de los grupos y de los estudiantes según los siguientes criterios:
+ Contribución individual al trabajo del equipo (10% de la nota). Este es el criterio más difícil de cuantificar por mi parte porque no he estado presente en todo el proceso de elaboración del trabajo. Por eso tiene tan poco peso en la nota final. 
+ Grado de coordinación del equipo (10%). Lo inferiré a partir de la actividad del grupo de Teams y de los comentarios finales individuales sobre aprendizajes, autocrítica, etc.
+ Ajuste del material entregado a los contenidos solicitados (30%). Se evaluará en qué medida lo que entrega cada grupo se ajusta a los descriptores ecosistémicos vistos tanto en teoría como en prácticas. Se valorará la incorporación de material no visto explícitamente en clase (ej. variables abióticas de cada ecosistema).
+ Grado de coherencia de los comentarios asociados al material gráfico incluido en la web (40%). Se evaluará cómo de válidas son las justificaciones aportadas en la web para explicar las gráficas y mapas mostradas. Se trata de evaluar en qué medida habéis entrenado vuestra capacidad de análisis crítico y la visión del mundo con la mirada de la ecología.
+ Calidad en el diseño de la web (10%). Se valorará especialmente el diseño atractivo y la incorporación de material novedoso y bien trabajado.




****

[Aquí](https://github.com/aprendiendo-cosas/T_descripcion_tipos_ecosistemas_ecologia_ccaa/archive/refs/tags/2024_2025.zip) puedes descargar un archivo .zip que contiene este guión en formato html y todo el material que incluye.

****
Haz click [aquí](https://github.com/aprendiendo-cosas/T_descripcion_tipos_ecosistemas_ecologia_ccaa/releases) para ver cómo ha cambiado este guión en los distintos cursos académicos.

****
 <p xmlns:cc="http://creativecommons.org/ns#" >El contenido de este repositorio se puede utilizar bajo la siguiente licencia:  <a  href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1"  target="_blank" rel="license noopener noreferrer"  style="display:inline-block;">CC BY-NC-SA 4.0<img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"  alt=""></a></p> 

<p>Esta licencia no aplica a enlaces a artículos, libros o imágenes no originales. Estos productos tienen su licencia correspondiente.</p>

