## Data Analyst - Análisis Telecomunicaciones

![alt text](image.png)


Nuestro rol se centra en asesorar a una empresa prestadora de servicios de telecomunicaciones con el fin de **orientar a la misma para poder brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y plantear soluciones personalizadas a sus posibles clientes**. La principal actividad de esta empresa es brindar acceso a internet, pero también se debe considerar el comportamiento del resto de los servicios de comunicación, en consecuencia, se realizará un análisis que permita reconocer el comportamiento del sector a nivel nacional.  

--- 
#### Descripción del Proyecto
El análisis abarca varios aspectos clave, incluyendo:
- Distribución Geográfica: Evaluación de la disponibilidad de diferentes tipos de conexiones (ADSL, Wireless, Fibra Óptica, Cablemodem.) y sus velocidades en las provincias.
- Tendencias Temporales: Análisis de la evolución de las conexiones a internet a lo largo de los años identificando patrones.
- Penetración del Servicio: Estudio de la penetración de internet en hogares y el acceso por tipo de tecnología.
- Visualización de Datos: Creación de gráficos interactivos y dashboards que facilitan la interpretación de los datos y permiten una exploración más profunda.
- Evaluación de los Ingresos, comparaciones interanuales y trimestrales.

---
#### Este proyecto utiliza diversas herramientas y tecnologías para el análisis y la visualización de datos, entre ellas:
`Python`, `Pandas`, `numpy`, `openpyxl`, `scipy`, `warnings`, `Matplotlib` y `Seaborn`. Para la creación de gráficos estáticos `Power BI`, `Jupyter Notebooks`.

#### Contenido del Repositorio
- Datasets: Archivos de datos proporcionados por ENACOM (Internet y televisión).
- EDA: Código en Python para explorar,procesar y análizar los datos. Con los mismos detallados y visualizados.
- Images
- Dashboards: Dashboards creados en Power BI para la visualización interactiva de los datos.

---
### Analicemos el servicio a Internet y TV
De acuerdo al objetivo de la empresa vamos a buscar medir el acceso a internet por tecnología en las distintas provincias argentinas, con el fin de identificar oportunidades de mejora en la calidad del servicio y atraer nuevos clientes. Al examinar el uso de las tecnologías más actuales y avanzadas, se puede planificar una estrategia que permita optimizar la oferta de servicios de internet, enfocándose en la expansión de las tecnologías más veloces y fiables.

Distribución del Acceso por Tecnología:
Históricamente, Cablemodem ha sido la tecnología predominante en Argentina. Sin embargo, hemos identificado un aumento considerable en la adopción de Fibra óptica, la cual está posicionándose como la opción preferida debido a su velocidad y confiabilidad. En contraste, todavía hay una presencia significativa de ADSL, especialmente en zonas rurales o áreas con menor capacidad económica. Esto indica que hay un segmento importante de usuarios que podría migrar a tecnologías más avanzadas, con las estrategias adecuadas.

<img src="https://github.com/user-attachments/assets/e7378136-3f9e-418f-9d5d-725f5a64ac67" alt="image-1" width="600" height="400"/>

<<<<<<< HEAD
Actualmente, Cablemodem sigue siendo la tecnología más usada, seguida de cerca por la Fibra óptica. Esta última, gracias a sus ventajas en velocidad, está en crecimiento y podría reemplazar gradualmente a Cablemodem. Para facilitar esta transición, la empresa debería implementar estrategias que promuevan la migración de usuarios de Cablemodem a Fibra óptica.

Por otro lado, aún existe un número significativo de usuarios de ADSL, probablemente debido a limitaciones económicas o geográficas. Se recomienda que la empresa ofrezca promociones o subsidios para incentivar la migración hacia tecnologías más modernas como Cablemodem o Fibra óptica.

<img src="https://github.com/user-attachments/assets/918b7abe-3db3-4ace-bf7a-5f6c5c4544f9" alt="image-3" width="600" height="400"/>

Provincias más Atrasadas en Tecnología:
Las provincias más rezagadas en términos de adopción tecnológica incluyen San Juan, San Luis, Chubut, Formosa y Río Negro. Muchas de estas áreas tienen características demográficas que pueden dificultar la modernización, como baja densidad poblacional o geografías complejas. No obstante, la modernización de estas áreas representa una oportunidad significativa para ganar mercado, especialmente si se implementan estrategias que faciliten la adopción de tecnologías más avanzadas como Fibra óptica.

<img src="https://vscode.dev/github/Melbutus/Data_Analyst_Telecomunicaciones/blob/master/Images/top5atrasadas.png" alt="image-3" width="600" height="400"/>

ya que vemos una distribución desigual de tecnologías. Las provincias presentan una mezcla variada de las mismas en diferentes rangos de velocidad. Algunas provincias tienen una gran cantidad de conexiones en bajas velocidades (ADSL y Wireless), lo que indica que estas áreas podrían beneficiarse significativamente de inversiones en infraestructura de alta velocidad.

<img src="https://vscode.dev/github/Melbutus/Data_Analyst_Telecomunicaciones/blob/master/Images/velocidades_tecnologia.png" alt="image-3" width="600" height="400"/>

Provincias como Buenos Aires y Capital Federal muestran una mayor adopción de tecnologías de alta velocidad, lo que sugiere que la modernización está más avanzada allí. Sin embargo, en provincias más pequeñas, como Catamarca y Chubut, la proporción de tecnologías más antiguas como ADSL sigue siendo significativa, lo que representa una oportunidad para modernizar y ofrecer servicios más competitivos.

<img src="https://github.com/user-attachments/assets/525ea456-ece5-4d42-bd19-fad646b7b5b1" alt="image-4" width="600" height="400"/>

Las provincias con una mayor proporción de conexiones en bajas velocidades podrían ser mercados clave para la empresa. La oferta de paquetes que promuevan la migración hacia tecnologías más rápidas podría tener un impacto significativo en estas áreas.

Penetración por Hogares:
En cuanto a la penetracion por hogares, en la mayoría de las provincias, se observa un incremento constante en la penetración de internet a lo largo de los años. Esto sugiere que la demanda de servicios de internet sigue creciendo, lo cual es una oportunidad para que la empresa siga invirtiendo en mejorar la infraestructura y oferta de servicios de internet.

<img src="https://github.com/user-attachments/assets/ec50f581-eeff-4da7-9129-e6c55fdb5293" alt="penetraciónInternet" width="600" height="400"/>

por otro lado, viendo las provincias con menor penetracion por hogares en 2023, estas provincias representan oportunidades claras para mejorar la infraestructura de telecomunicaciones, ya que tienen un porcentaje de hogares con acceso a internet considerablemente bajo. Esto puede ser un indicativo de barreras económicas, falta de inversión en infraestructura o poca cobertura de redes avanzadas como fibra óptica, además de que también son provincias chicas.

<img src="https://vscode.dev/github/Melbutus/Data_Analyst_Telecomunicaciones/blob/master/Images/menorpenhogares.png" alt="penetraciónInternet" width="600" height="400"/>

Por otro lado, esto podría indicar una potencial brecha digital, ya que la baja penetración en estas provincias significa que los ciudadanos en estas áreas pueden estar quedando rezagados en términos de acceso a la educación, servicios, empleo y oportunidades que dependen del acceso a internet. Lo que requiere una acción inmediata de la empresa para mitigar esta brecha.

=======
<img src="https://github.com/user-attachments/assets/ec50f581-eeff-4da7-9129-e6c55fdb5293" alt="penetraciónInternet" width="600" height="400"/>
>>>>>>> 531ae1e1ebc5635abb7c88e76e7ba6ccfcb6e4c6

<img src="https://github.com/user-attachments/assets/fd6abbfd-8410-48ae-9c06-816a79eb646c" alt="image-10" width="600" height="400"/>

<<<<<<< HEAD
En cuanto a ingresos, se ha identificado una tendencia de crecimiento de los mismos durante los últimos trimestres del año, lo cual sugiere la necesidad de una planificación estacional adecuada para maximizar los ingresos. La empresa puede capitalizar en este comportamiento aumentando la promoción y las ofertas durante los meses de mayor demanda.
=======

### Análisis de televisión
En cuanto a los Accesos, provincias como Buenos Aires y Capital Federal dominan los accesos a televisión por suscripción, mientras que otras provincias, como Chaco y Tierra del Fuego, presentan menor penetración y accesos. Esto sugiere que existen oportunidades para mejorar la oferta en estas zonas. La mayoría de las provincias muestran un crecimiento estable o ligeramente ascendente, sin grandes picos o caídas bruscas, lo que podría indicar una penetración ya establecida en estos mercados.

<img src="https://github.com/user-attachments/assets/24174500-fb2c-4a47-9118-cdb2ea2a37a9" alt="image-11" width="600" height="400"/>

En cuanto a la penetración por Hogares, la penetración de la televisión por suscripción es mayor en provincias con mayor densidad de población, como Buenos Aires y Capital Federal. Sin embargo, provincias más pequeñas presentan una penetración mucho menor, lo que podría ser un área clave para aumentar la penetración del servicio.

<img src="https://github.com/user-attachments/assets/d8e5fbfe-821d-47d4-adf8-70712817c108" alt="image-12" width="600" height="400"/>

Hablando de Ingresos, los mismos han crecido considerablemente desde 2014, con un salto notable a partir de 2022. La televisión satelital, si bien ha mantenido una participación más baja, sigue representando una parte significativa de los ingresos. Hay un crecimiento constante, esto sugiere una tendencia positiva y sostenida en las suscripciones de TV durante el año. Un aumento notable en el cuarto trimestre, lo que podría deberse a diferentes factores, como promociones estacionales, mayor demanda de suscripciones durante el fin de año o lanzamientos de contenido atractivo que generaron más suscripciones.  Se considera una posible oportunidad de expansión a este comportamiento creciente que sugiere que la empresa está en un buen momento para continuar expandiéndose o invirtiendo en estrategias que mantengan o aumenten este ritmo de crecimiento. Los datos sugieren que las suscripciones continúan siendo una fuente de ingresos sólida y en expansión.

<img src="https://github.com/user-attachments/assets/82bcc805-2f2e-4f89-9cef-6e6d2c4fde34" alt="image-14" width="600" height="400"/>


#### Recomendaciones:
Mejorar la Infraestructura en Zonas de Baja Conectividad: Priorizar la inversión en infraestructura de fibra óptica en provincias con baja penetración y predominio de tecnologías antiguas como ADSL y Wireless. Las áreas rurales y menos desarrolladas, como Formosa, Chaco y San Juan, pueden beneficiarse enormemente de esta modernización, mejorando la cobertura y calidad del servicio.

Facilitar la Transición hacia Tecnologías de Alta Velocidad: Implementar campañas que incentiven la migración de usuarios actuales de ADSL y Wireless hacia tecnologías más rápidas como Cablemodem y Fibra óptica. Ofrecer paquetes de transición con descuentos o promociones temporales puede ser clave para convencer a los usuarios de migrar.

Optimización de Servicios en Mercados Madurados: En provincias donde la penetración de Fibra óptica ya es considerable, como Buenos Aires y Capital Federal, la empresa debería enfocarse en la optimización del servicio. Esto incluye mejoras continuas en la velocidad, estabilidad, y servicios adicionales como TV por internet o streaming de alta calidad, aumentando así la satisfacción y retención de clientes.


### Fuente:
Los datos fueron obtenidos de la página del Ente Nacional de Comunicaciones (ENACOM), organismo regulador de las telecomunicaciones en Argentina.
https://indicadores.enacom.gob.ar/datos-abiertos


