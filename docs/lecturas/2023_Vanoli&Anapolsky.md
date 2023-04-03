	---
layout: default
title: 2023_Vanoli&Anapolsky
parent: Lecturas
---

Inicio de lectura: 06-03-2023

Fin de lectura: 06-03-2023

# Acceso a Oportunidades en ciudades de América Latina: Metodología para la construcción de indicadores

**Autorx(s):** Catalina Vanoli y Sebastián Anapolsky

**Año:** 2023

**Cita APA:** Vanoli, C., & Anapolsky, S. (2023). Acceso a oportunidades en América Latina. Recuperado de https://cafscioteca.azurewebsites.net/handle/123456789/2003

**Url:** https://scioteca.caf.com/handle/123456789/2003

**Carpeta Zotero:** Movilidad-Accesibilidad-Transporte

**Tags:**  

**Región / País del texto:** #AMERICALATINA #ARGENTINA 

**Palabras clave:** 

**Clasificación Propia:** #ACCESIBILIDAD #METODOLOGÍA #MOVILIDAD 

## Datos de autor(x)s

Catalina Vanoli, especialista en transporte y científica de datos trabajando en CAF, y Sebastián Anapolsky, consultor especialista en transporte y ciencia de datos.

## Resumen 

"Las ciudades ofrecen el acceso a oportunidades de diferente tipo a su ciudadanía, como oportunidades de trabajo, de educación y salud, culturales y de recreación. El acceso equitativo y eficiente a estas oportunidades determina el nivel de productividad y calidad de vida en nuestras ciudades. El desarrollo de indicadores de accesibilidad permite mejorar el diseño de las políticas públicas, identificando inversiones e intervenciones urbanas con decisiones basadas en datos.

En un contexto de grandes avances tecnológicos, con acceso a nuevas fuentes de datos y herramientas para su análisis, la tercera edición del OMU presenta el desarrollo de una metodología que permite calcular una serie de métricas para monitorear la accesibilidad urbana en las ciudades utilizando datos pú- blicos. A su vez, el OMU desarrolló una herramienta de código abierto que permite replicar este análi- sis en el futuro o para nuevas ciudades.

La metodología incluye el cálculo de indicadores de congestión, identificación de áreas de alta densidad de actividad, cálculo de los tiempos de viajes a distintas oportunidades urbanas (centralidadesurbanas, establecimientos educativos y de salud, etc), accesibilidad a espacios verdes y públicos y cobertura del transporte público. Estas métricas se calculan utilizando información censal y cartográfica de las ciudades y utilizan la aplicaciones de ruteo de viajes (Open Street Maps y Google Maps) para obtener información sobre los viajes. Esta herramienta permite también la construcción de un indicador de nivel socioeconómico que permite analizar a la población en forma más desagregada.

En la última parte del trabajo, se presenta el caso de estudio de la Región Metropolitana de Buenos Aires (RMBA) donde se muestran los indicadores que pueden ser elaborados con esta herramienta de código abierto.

La metodología es aplicable a diferentes contextos y puede ser replicable por especialistas técnicos de los gobiernos, la academia o analistas de ciudades. La librería pyomu es de código abierto y se puede acceder en el repositorio de GitHub del OMU. Se buscó que los resultados sean de fácil interpretación para poder ser presentados a autoridades y tomadores de decisión, acentuando la importancia de identificar brechas de acceso y diseñar las corres- pondientes intervenciones basadas en evidencia."

## Objetivos

Construcción de un "modelo analítico para definir y calcular indicadores de accesibilidad urbana a centros de actividad y a distintos servicios básicos para distintos niveles socioeconómicos"

## Ideas principales

Definición de accesibilidad:
"A grandes rasgos, se define como la facilidad para acceder a bienes, servicios, actividades y destinos en una ciudad (Litman, 2003). Sin embargo, hay definiciones que encaran el problema desde diferentes perspectivas. Algunas hablan de “las oportunidades potenciales de interacción” (Hansen, 1959); la facilidad con la que se puede acceder a las actividades usando un modo particular de transporte (Dalvi y Martin, 1976); la libertad de los individuos de decidir participar o no de diferentes actividades (Burns, 1979); y los beneficios que produce un determinado sistema de usos de suelo y transporte (Ben-Akiva y Lerman, 1979). El Reporte de Economía y Desarrollo (RED) 2017 de CAF define la accesibilidad como “la capacidad de alcanzar las oportunidades que ofrece la ciudad”, y la considera la medida fundamental de bienestar en las ciudades. Además, la accesibilidad urbana se estudia como uno de los factores que afectan el nivel de inclusión y productividad en las aglomeraciones urbanas, y se destaca su importancia en el crecimiento y desarrollo de las ciudades (Hernández y Hansz, 2021)."

"En este trabajo, se toman las definiciones del RED 2017 de CAF y de Hernández y Hansz para definir la accesibilidad urbana como “la capacidad de un espacio urbanizado y sus sistemas de proveer a todas las personas y comercios de oportunidades laborales, educativas, de salud, sociales y culturales de manera equitativa y eficiente”. La accesibilidad urbana es considerada fundamental para el crecimiento y desarrollo de las regiones."

Se basa en los aportes de Hernández y Hansz (2021) en base a Geurs y Ritsema van Eck (2001).
para detallar que "Los principales componentes que caracterizan la accesibilidad urbana incluyen la ubicación de los hogares, las características socioeconómicas, la forma urbana y distribución de actividades, y el sistema de transporte (ver figura 1)."

## Metodología

Presenta cuatro perspectivas para abordar la accesibilidad basado en Geurs y van Wee (2004). 

1. Mediciones de la infraestructura de transporte
2. Distribución espacial de las actividades
3. Las oportunidades que puede alcanzar una persona
4. Mediciones de los beneficios economicos o de otro tipo que derivan de acceder a determinadas oportunidades. 

El trabajo de Vanoli & Anapolsky (2023) busca incluir:
1. la oferta que brinda la infraestructura
2. 2. la distribución espacial de las actividades
3. ciertas características a nivel individual.

Para ello propone la construcción de 4 indicadores
- **Índice de congestión: **este indicador tiene en consideración las velocidades promedio a lo largo de un día hábil y se construye como el ratio entre la velocidad promedio en hora valle y la velocidad promedio en hora punta.
- **Accesibilidad a actividades y al área central:** esta serie de indicadores cal- cula los tiempos promedios de viaje y tiene en consideración las áreas de alta con- centración de actividades (principales atractores) y el área central de una ciudad.
- **Accesibilidad a educación, salud y espacios verdes:** esta serie de indica- dores calcula los tiempos de viaje hacia los distintos tipos de establecimientos.
- **Indicador general de accesibilidad (clústeres de accesibilidad):** construye un indicador de nivel de accesibilidad territorial teniendo en consideración los indicadores calculados anteriormente.

Para esto utiliza como fuentes de información secundaria datos publicos de distintos organismos, APIs de Google y Open Street Maps. 
En el marco de las nuevas tecnologías de información.

## Comentarios y observaciones

No realiza una crítica negativa o detalla los riesgos y sesgos de las nuevas fuentes de información basadas.

Usa datos de Google y los identifica como abiertos y publicos. No detalla su costo, si los detalla en el código para construir los indicadores. 

Aclara que en el desarrollo de indicadores de accesibilidad es todavía una deuda pendiente incluir los factores subjetivos de los individuos **(Ronan, 2017)**

### Links de interés 

[repositorio con el código](https://github.com/OMU-LATAM/)

[librería creada por autores] (https://pypi.org/project/pyomu/)

"Como ejemplo de un nuevo enfoque de accesibilidad, se encuentra la propuesta del Ins- tituto de Transporte y Políticas de Desarrollo (ITDP), con once indicadores categorizados en tres dimensiones: proximidad al transporte, accesibilidad y características de la ciudad. Para más información, acceder a ITDP Online Indicators: https://naindicators.itdp.org/.""

### Bibliografía citada en el texto

Carruthers, R. C., Dick, M. C., y Saurkar, A. (2005). Affordability of public transport in developing countries (N.o 33900; pp. 1-27). The World Bank. http://documents. worldbank.org/curated/en/230991468153275100/Affordability-of-public-trans- port-in-developing-countries

Daude, C., Fajardo, G., Brassiolo, P., Estrada, R., Goytia, C., Sanguinetti, P., Álvarez, F., y Vargas, J. (2017). RED 2017. Crecimiento urbano y acceso a oportunidades: Un desaf ío para América Latina. CAF. http://scioteca.caf.com/handle/123456789/1090

Geurs, K. T., y van Wee, B. (2004). Accessibility evaluation of land-use and transport strategies: Review and research directions. Journal of Transport Geography, 12(2), 127-140. https://doi.org/10.1016/j.jtrangeo.2003.10.005

Hansen, W. G. (1959). How Accessibility Shapes Land Use. Journal of the American Institute of Planners, 25(2), 73-76. https://doi.org/10.1080/01944365908978307

Hernández, D., y Hansz, M. (2021). Accesos a oportunidades para favorecer la in- clusión. Aspectos conceptuales, indicadores y su medición. CAF. https://cafscioteca. azurewebsites.net/handle/123456789/1692

Herrera, L., Olivares, F., y Pecht, W. (1976). Crecimiento urbano de América Latina. https://repositorio.cepal.org/handle/11362/8609

Litman, T. (2003). Measuring transportation: Traffic, mobility and accessibility. So- cial Research in Transport (SORT) Clearinghouse, 73(10).