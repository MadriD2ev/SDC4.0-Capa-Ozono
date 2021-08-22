### Descripción del problema y entendimiento del contexto

```text
Determinar las Sustancias Agotadoras de la Capa de Ozono (SAO) y la correlación que tiene respecto a la contaminación del aire y los posibles efectos secundarios que se podrían generar en los seres humanos, animales o plantas respecto a la emergencia sanitaria por el COVID-19.
```

-------------------------------------------------------------------------------------------------------------------------------------------------------

David agregó esto: 

Mi propuesta: Crear un modelo matemático, utilizando las técnicas y algoritmos de machine learning más actuales, para predecir la tendencia que tendrán en un futuro reciente, los niveles de contaminantes más comunes presentes en el aire, con el objetivo de emitir nuestro criterio y poder evaluar cuál será el posible impacto en la sociedad. 

Posibles preguntas que podemos hacernos:
- Qué algoritmos de machine learning se han utilizados en estudios posteriores?, cuáles han sido los resultados alcanzados?, qué datos se han utilizado para alimentar y entrenar estos algoritmos?

- Qué regiones o ciudades de México podemos utilizar en nuestro estudio, partiendo de los dataset y la información que tenemos disponible hasta el momento.

  -----------------------------------------------------------------------------------------------------------------------------------

##### Antecedentes 

Consultar información previa sobre qué son las sustancias agotadoras de la capa de ozono, la contaminación del aire y los efectos secundarios de cada uno de ellos.

 Además de los instrumentos de medición de la calidad de aire y las SAO.

Estadísticas de la calidad del aire durante la emergencia sanitaria.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

David agregó esto:

Mi propuesta (Adicional)

Hacer un estudio del Estado del Arte del Machine Learning, aplicado a la predicción de la contaminación del aire, y toda la documentación que nos permita tener un mayor entendimiento del problema y de las vías y métodos a utilizar para llegar a una solución y conclusiones finales.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

##### Bases Teóricas

Se establece entonces a partir de la información consultada que:

- Son sustancias químicas producidas por el hombre con el potencial para reaccionar con las moléculas de ozono de la estratosfera (SAO).
- La capacidad de destrucción de algunas sustancias que agotan la capa de ozono pueden superar los 100 años.
- Las SAO principales son clorofluorocarbonos (CFC), hidroclorofluorocarbonos (HCFC), halones y bromuro de metilo. 
- Algunas de sus aplicaciones están en las espumas solventes, aerosoles, refrigeración, otras son utilizadas como agentes extintores de fuego y algunas otras son de uso agrícola utilizada para la desinfección de suelos y madera de exportación en cuarentena y preembarque.
- Que hay alternativas a las SAO como los hidrofluorocrbonos (HFC) y los hidrocarburos (ciclopentano, isobutano, propano, entre otros); sin embargo, algunos presentan alto potencial de calentamiento global y algunos de ellos son inflamables por lo que su utilización está sujeta a medidas de seguridad y minimización de riesgos.
- El impacto de las SAO se mide por medio de un índice conocido como potencial de agotamiento del ozono (PAO).
- Existe un acuerdo internacional que promueve la eliminación del consumo de las SAO llamada Protocolo de Montreal.
- Los principales contaminantes en el aire son el ozono (O3), dióxido de nitrógeno (NO2), dióxido de azufre (SO2), monóxido de carbono (CO). 
- También se consideran las medidas de otros contaminantes en cantidades de partículas sólidas o liquidas como de polvo, cenizas, hollín, metales, cemento o polen dispersas en el aire, las cuales se escriben como PM10 Y PM2.5
- Se cuenta con las medidas estandarizadas de la calidad del aire y las reglas que se deben de implementar para calcular los índices de calidad del aire en la Norma Oficial Mexicana NOM-172-SEMARNAT-2019.
- El IMECA es el que se encarga de revisar los niveles de contaminación existentes en el aire.

##### Bases Legales  

EN EVALUACIÓN

##### Conceptos Claves

SAO, PM10, PM2.5, estratosfera, contaminación, efectos secundarios, instrumentos de medición de las SAO y contaminantes del aire , atmosfera, entre otros.

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

Julio César

Los altos niveles de contaminantes en el aire como el O3, CO, entre otros tienen gran repercución en la salud humana, principalmente en enfermedades pulmonares. Diariamente, por distintas situaciones, nos exponemos a este tipo de contaminantes por tiempos prolongados sin siquiera estar concientes de ello el cual poco a poco afecta nuestra salud.

César

Hipótesis: Contar con un modelo predictivo más potente de la calidad del aire en la ZMG permitirá anticipar pérdidas económicas para personas e industrias que se ven afectadas por contingencias ambientales declaradas, y de esta manera mejorar la toma de decisiones respecto a la movilidad de personas y productos.

-------------------------------------------------------------------------------------------------------------------------------------------------------

Combinación de las anteriores:

Los altos niveles de contaminantes en el aire tienen gran repercución en la salud humana, se esperaría contar con un modelo predictivo más potente de la calidad del aire en la ZMG que permitirá anticipar pérdidas económicas para personas e industrias que se ven afectadas por contingencias ambientales declaradas, y de esta manera mejorar la toma de decisiones respecto a la movilidad de personas y productos.

------------------------------------------------------------------------------------------------------------------------------------------------------------

### Objetivos

#### General

​	Predecir la calidad del aire por hora y sus afectaciones sobre la salud pública y la movilidad en la zona metropolitana de la ciudad de Guadalajara (ZMG).

#### Específicos

- ​	Comparación de los modelos predictivos de machine learning  sobre la cálidad de aire en el área metropolitana de Guadalajara
- Comparación del modelo elegido de machine learning para prediccion de la calidad del aire con el modelo actualmente utilizado.
- Cuantificar el impacto de contigencias ambientales sobre la movilidad de personas y productos en la ZMG.

- Determinar los porcentajes de afectación sobre la salud 
- Buscar las generalidades de las afectaciones sobre la salud con etiología de contaminación atmosférica y posteriormte enfocarnos a enfermedades especificas y afectaciones en organos en particular 
- Recomendaciones para la población
- Poder predecir en un lapso de tiempo cuándo habrá una contingencia ambiental en la ZMG.

### Metodología

PENDIENTE

### Bases de Datos

PENDIENTE

### Sitios consultados

[SEMARNAT](https://apps1.semarnat.gob.mx:8443/dgeia/informe18/tema/cap5.html)

[ResearchGate](https://www.researchgate.net/search/publication?q=Assessing+the+COVID%E2%80%9019+Impact+on+Air+Quality%3A+A+Machine+Learning+Approach)

[WORLDOMETERS](https://www.worldometers.info/coronavirus/)





