## Primer Entregable SDC 4.0  



![SDC4](https://user-images.githubusercontent.com/68882204/130522869-4d64a3a3-72d7-4ecc-ad79-faae7b08efc5.jpg)



​																	 Integrantes del Equipo

​						1. César Miranda Cantero                                             2. David Tamayo Ramírez            

​						3. Madrid Gutiérrez Hernández                                   4. Luis Enrique Moreno Mendieta 
                                   5. Julio César Álvarez Charqueño

  															 













### Descripción del problema y entendimiento del contexto

Actualmente no se cuenta con un modelo predictivo altamente confiable que permita anticipar la declaración de contingencias ambientales debido a la mala calidad del aire en la Zona Metropolitana de Guadalajara. La declaración de estas contingencias ambientales impacta en movilidad de personas y productos, que a su vez tiene una afectación directa en la economía de las mismas personas e industrias de diversa índole. En este proyecto se pretende desarrollar una herramienta que permita predecir con horas o días de antelación la declaración de contingencias ambientales por parte del gobierno del estado de Jalisco para ayudar en la toma de decisiones.

##### Antecedentes 

- Consultar información previa sobre la contaminación del aire.
- Los efectos secundarios de cada uno de ellos.
- Además de los instrumentos de medición de la calidad de aire.
- Estadísticas de la calidad del aire antes y durante la emergencia sanitaria.
- Hacer un estudio del Estado del Arte del Machine Learning, aplicado a la predicción de la contaminación del aire, y toda la documentación que nos permita tener un mayor entendimiento del problema y de las vías y métodos a utilizar para llegar a una solución y conclusiones finales.

##### Bases Teóricas

Se establece entonces a partir de la información consultada que:

- Que hay alternativas a las SAO como los hidrofluorocrbonos (HFC) y los hidrocarburos (ciclopentano, isobutano, propano, entre otros); sin embargo, algunos presentan alto potencial de calentamiento global y algunos de ellos son inflamables por lo que su utilización está sujeta a medidas de seguridad y minimización de riesgos.
- Los principales contaminantes en el aire son el ozono (O3), dióxido de nitrógeno (NO2), dióxido de azufre (SO2), monóxido de carbono (CO). 
- También se consideran las medidas de otros contaminantes en cantidades de partículas sólidas o liquidas como de polvo, cenizas, hollín, metales, cemento o polen dispersas en el aire, las cuales se escriben como PM10 Y PM2.5
- Se cuenta con las medidas estandarizadas de la calidad del aire y las reglas que se deben de implementar para calcular los índices de calidad del aire en la Norma Oficial Mexicana NOM-172-SEMARNAT-2019.
- El IMECA es el que se encarga de revisar los niveles de contaminación existentes en el aire.

##### Bases Legales  

[NOM-172-SEMARNAT-2019](https://dof.gob.mx/nota_detalle.php?codigo=5579387&fecha=20/11/2019)

##### Conceptos Claves

SAO, PM10, PM2.5, estratosfera, contaminación, efectos secundarios, instrumentos de medición de los contaminantes del aire , atmosfera, entre otros.







### Marco Teórico

[National Geographic](https://www.nationalgeographic.es/medio-ambiente/la-contaminacion-del-aire) (5 Septiembre 2010), Se considera contaminación del aire a cualquier sustancia, introducida en la atmósfera por las personas que tenga un efecto perjudicial sobre los seres vivos y el medio ambiente siendo la más común y evidente la niebla tóxica que flota por encima de las ciudades. 

El dióxido de carbono se considera contaminante cuando se asocia con coches, aviones, centrales eléctricas y otras actividades humanas que requieren el uso de combustibles fósiles como la gasolina y el gas natural, el metano (que proviene de fuentes como ciénagas y gases emitidos por el Ganado) y los clorofluorocarbonos (CFCs), que se utilizaban para refrigerantes y propelentes de los aerosoles hasta que se prohibieron por su efecto perjudicial sobre la capa de ozono de la Tierra, el dióxido de azufre (uno de los componentes de la niebla tóxica) es uno de los causantes de la lluvia ácida, sin embargo, también refleja la luz cuando son liberados en la atmósfera, lo que en ocasiones provoca un enfriamiento que dura varios años lo que es bueno pero también se han registrado que en los niveles más bajos de dióxido de azufre empeora el calentamiento global.

[SEMARNAT](https://apps1.semarnat.gob.mx:8443/dgeia/informe18/tema/recuadros/recuadro5_2.html) (Informe 18 Recuadro 5_2), Existen algunos contaminantes climáticos de vida corta (CCVC), entre los que se encuentran el carbono negro (CN), el métano (CH4), los hidrofluorocarbonos (HFC) y los hidroclorofluorocarbonos (HCFC). 

Aunque el mayor interés sobre el CN se ha concentrado en su efecto en el calentamiento global sus consecuencias negativas sobre la salud también causan preocupación. La asociación del CN con ciertos padecimientos se centra principalmente en las partículas suspendidas con diámetros iguales o menores a 2.5 μm (PM2.5). Estas partículas, además de producirse por la combustión de combustibles fósiles, también se generan en los hogares por la quema de biocombustibles (por ejemplo, leña) empleados para cocinar o para calefacción. A diferencia de las partículas PM10 , el reducido tamaño de las PM2.5 les permite alcanzar zonas más profundas del sistema respiratorio, como la región bronquial, aumentando la incidencia de diversas afecciones, entre las que son más frecuentes los accidentes cerebrovasculares, diversas enfermedades del corazón y cáncer de pulmón (Janssen *et al*., 2012; WHO, 2015). Según las estimaciones de la Organización Mundial de la Salud (OMS, 2016) alrededor de 4.2 millones de muertes prematuras ocurren cada año por la exposición a partículas PM2.5 (OMS, 2018, Figura a). 

[Worldometer](https://www.worldometers.info/coronavirus/) (2020), Originario de China a fines de 2019 propagado por un virus corona 2 del síndrome respiratorio agudo severo (SARS-CoV-2), esta enfermedad de síntomas complejos se extendió exponencialmente a casi en todas partes del mundo. 

(Shi & Brasseur, 2020; Y. Wang et al., 2020), Para ralentizar la interacción social, el modo principal de infección, se ha implementado una serie de medidas regulatorias en todos los países. Las actividades fueron limitadas o incluso prohibidas, lo que a su vez, afectó positivamente la calidad ambiental, especialmente, debido a la reducción de emisiones por transporte e industrias.

(Limb, 2016; ONU., 2015; OMS., 2016) Este fue un experimento global único, ya que las condiciones de calidad del aire urbano, regional y global han ido empeorando persistentemente debido a un rápido aumento de las fuentes contaminantes por parte de la población humana.

Estas estadísticas de mejoras en la calidad del aire se informan comúnmente comparando los períodos de actividad humana restringidos con las "condiciones normales", meses o años antes de la emergencia sanitaria.

### Hipótesis 

Se esperaría contar con un modelo predictivo de la calidad del aire en la ZMG que permitirá anticipar pérdidas económicas para personas e industrias que se ven afectadas por contingencias ambientales declaradas, y de esta manera mejorar la toma de decisiones respecto a la movilidad de personas y productos. 

### Objetivos

#### General

Predecir la calidad del aire por hora y sus afectaciones sobre la salud pública y la movilidad en la zona metropolitana de la ciudad de Guadalajara (ZMG).

#### Específicos

- Comparación de los modelos predictivos de machine learning  sobre la cálidad de aire en el área metropolitana de Guadalajara.
- Comparación del modelo elegido de machine learning para prediccion de la calidad del aire con el modelo actualmente utilizado Sistema Predictivo y de Modelación de Calidad de Aire a Autoridades Ambientales.
- Comparación del modelo elegido de machine learning para prediccion de la calidad del aire con el modelo actualmente utilizado.
- Cuantificar el impacto de contigencias ambientales sobre la movilidad de personas y productos en la ZMG.

- Determinar los porcentajes de afectación sobre la salud.
- Buscar las generalidades de las afectaciones sobre la salud con etiología de contaminación atmosférica y posteriormte enfocarnos a enfermedades especificas y afectaciones en organos en particular 
- Recomendaciones para la población.
- Poder predecir en un lapso de tiempo cuándo habrá una contingencia ambiental en la ZMG.























### Bases de Datos

[Air Quality Historical Data Platform](https://aqicn.org/data-platform/register/)

[Datos Abiertos - SEMARNAT](https://datos.gob.mx/busca/dataset/indicadores-basicos-del-desempeno-ambiental--atmosfera--calidad-del-aire)

[Datos actuales de la estación meteorológica del Instituto de Astronomía y Meteorología del Departamento de Física CUCEI Universidad de Guadalajara](http://astro.iam.udg.mx/Estacion/)

Secretaría de Medio Ambiente y Recursos Naturales (México)

[SEMARNAT](https://www.gob.mx/semarnat/articulos/protocolo-de-montreal-a-30-anos-de-su-establecimiento)

Instituto Nacional de Estadística y Geografía

[INEGI](https://www.inegi.org.mx/rnm/index.php/catalog/642)

National Aeronautics and Space Administration 

[NASA](https://ozonewatch.gsfc.nasa.gov/monthly/SH.html)

Datos abiertos del Gobierno de México

[Datos Abiertos](https://datos.gob.mx/busca/dataset/inventaririo-de-sustancias-agotadoras-de-la-capa-de-ozono)

CEPALSTAT | Bases de Datos y Publicaciones Estadísticas. (ONU)

[CEPALSTAT ](https://estadisticas.cepal.org/cepalstat/portada.html)

Sistema de Información y Seguimiento de Sustancias Agotadoras de la Capa de Ozono

[SISSAO](http://apps2.semarnat.gob.mx:8080/sissao/consultas.jsp)

### Sitios consultados

[SEMARNAT](https://apps1.semarnat.gob.mx:8443/dgeia/informe18/tema/cap5.html)

[ResearchGate](https://www.researchgate.net/search/publication?q=Assessing+the+COVID%E2%80%9019+Impact+on+Air+Quality%3A+A+Machine+Learning+Approach)

[WORLDOMETERS](https://www.worldometers.info/coronavirus/)

[SISTEMA PREDICTIVO Y DE MODELACIÓN DE CALIDAD DEL AIRE A AUTORIDADES AMBIENTALES](https://www.jalisco.gob.mx/es/prensa/noticias/107164)











