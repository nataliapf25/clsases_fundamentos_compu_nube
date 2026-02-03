
# Parte 1: Tipos de nube

## 1. Investigación
Investigue y complete la siguiente tabla comparativa: 

| Tipo de nube | ¿Dónde se ejecuta? | Ventajas (mín. 3) | Desventajas (mín. 3) | Ejemplo de uso |
|--------------|--------------------|-------------------|----------------------|----------------|  
| Publica      | Centros de datos remotos de proveedores como AWS |-Permite evitar gastos iniciales de capital - Permite acceso a recursos que el proveedor ofrece (escabilidad) - El mantenimiento está a cargo del proveedor | Existen riesgos de seguridad al compartir infraestructura - Menor control sobre los datos - El rendimiento es variable | -En comercio electrónico para estabilidad - Almacenamiento de datos por parte de empresas - Big data: procesamiento usando apps de IA nativas de la nube |
| Privada      | En las instalaciones de la propia organización (su cenro de datos) - En centros de datos de terceros (pueden ser físicos o virtuales) - Dentro de una nube pública pero aislada | -Permiten mayor privacidad y control sobre los datos y su manejo - Personalización completa a sus necesidades - Cumplimiento de normativas en casos de industrias específicas como la financiera | Son costosas de implementar y de mantner - Dificulta la escalabilidad porque depende de hardware propio - Posibilidad de infraestructura subutilizada porque es difícil de calcular el requerimiento real | En instituciones financieras para el manejo de datos confidenciales de sus trasacciones y de clientes - Los gobiernos: al manejar datos sensibles sobre sus ciudadanos - Empresas que requieren una infraestructura más personalizada y mayor control de sus datos |
| Híbrida      | En nubes públicas | Son más flexibles porque pueden moverse entre la nube pública y la privada dependiendo de las necesidades - Puede cumplir con requisitos de seguridad y confidencialidad al manejar datos en nube privada - Permite aumentar la capacidad de infraestructura de acuerdo a las necesidades lo que reduce costos | - Complejidad de gestión: requieren coordinación tecnica - Costos iniciales de inversión en nube privada pueden ser elevados  - Las políticas de seguridad deben aplicarse a ambos tiós de nube por igual, la disparidad entre los entornos puede dificultar esto | -Desarrollo y pruebas para aplicaciones - Finanzas: bancos que usan la nube pública para análisis de datos y los servicios dirigidos al cliente - Comercio electrónico, usan la pública para el manejo del tráfico masivo y la privada para los datos de clientes | 



## 2. Análisis 

Responda las siguientes preguntas: 

- ¿Por qué la nube pública es la más utilizada actualmente?

Las principales razones que hacen que este tipo de nube sea de las más utilizadas es que dan acceso a una gran cantidad de recursos con un costo que se ajusta especificamente a la capacidad requerida y además sin preocuparse por su mantenimiento. Además de esto, garantizan seguridad avanzada y disponibilidad del servicio, lo que permite que las organizaciones cuenten con servicios más fluidos y brinden mayor estabilidad a sus usuarios. 

- ¿En qué escenarios es necesaria una nube privada?

Cuando la organización requiere manipular datos que son sensibles y sobre los cuales requiere garantizar un control absoluto que sea independiente de terceros, tal es el caso de gobiernos, instituciones finacieras y de salud. También se vuelve necesario cuando una organización debe cumplir con regulaciones sobre el manejo de esos datos.  

- ¿Qué necesidad resuelve la nube híbrida? 

Resuelve necesidades de flexibilidad y optimización de costos, es decir, una organización busca esta combinación cuando requiere mantener datos confidenciales seguros dentro de sus propios servidores y cumplir con regulaciones especificas acerca de su manejo pero también necesita la capacidad de escalabilidad que ofrece la nube pública. 



# Parte 2: Proveedores de nube pública

## 1. Investigación de proveedores 

Investigue y mencione las caracteristicas que usted considera importantes sobre los siguientes proveedores de nube pública (justifique su respuesta):

- Amazon Web Services (AWS) 

AWS por sus siglas en inglés (Amazon Web Services), inició sus operaciones en el año 2006, cuando Amazon decidió aprovechar sus infraestructura tecnológica a través de la externalización de  servicios. Estos habían sido desarrollados para el manejo propio del comercio de su organización, es especial para hacer frente a sus picos de demanda. De esta manera, se convirtieron en los primeros en proveer servicios de nube pública a gran escala con dos ramas básicas como Amazon S3 centrado en almacenamiento, y Amazon S2 en cómputo. Actualmente, son proveedores de una gran variedad de servicios, omo cómputo en la nube, almacenamiento, bases de datos, redes, segridad, servios de análisis e inteligencia artificial y machine learning. 

- Microsoft Azure

Nace en el año 2010, dada la estrategia de Microsoft para expandir su ecosistema empresarial a la nube, comenzando como una plataforma PaaS y evolucionando hacia un modelo completo de nube pública. Actualmente no solamente ofrecen ese servicio, sino también soluciones como IaaS y SaaS, además de destacarse en los ecosistemas de nube híbrida, y ofreciendo grandes ventajas dadas sus integraciones con herramientas del ecosistema Microssft Office.

- Oracle Cloud Infrastructure (OCI) 

Surge en el año 2016 luego de un intento fallido por desarrollar una nube capaz de comppetir contra AWS y Azure, su núcleo principal se centra en la optimización de rendimiento, seguridad y costo de las aplicaciones empresariales. Dentro de los servicios que brindad a sus usuarios se encuentran el almacenamiento, las máquinas virtuales, las redes de alto rendimiento, la seguridad y los contenedores. Una de sus ventajas más atractivas es su integración con la base de datos orientadas a cargas de trabajo empresariales, en especial para clientes que ya emplean las bases de datos de Oracle. 



## 2. Comparación general 

Compare los siguientes proveedores de nube pública:

|Proveedor | Fortalezas principales | Casos de uso comunes |  Facilidad de uso | Público objetivo | 
|----------|------------------------|----------------------|----------------------|----------------|  
| AWS | - Amplia infraestructura a nivel mundial: baja latencia  - Alta oferta de servicios: herramientas como Machine learning e inteligencia arificial - Ofrece seguridad: encriptación, firewalls, certificaciones de cumplimiento de normas | Aplicaciones grandes como Netflix y twitch  - Análisis de datos complejos con grnades cantidades de info - Entornos de trbajo seguros para trabajo remoto  | fácil | empresas de cualquier tamaño, agencias del gobierno, desarrolladores | 
| Azure | - Fuerte integración con el ecosistema de Micrrosoft - Tiene la mayor cantidad de certificaciones de cumplimiento comparado con cualquier otro proveedor: seguridad multicapa y cifrado predeterminado  - Es superior en la creación de ecosistemas híbridos | Lo emplean como IaaS, especialmente cuando la carga de trabajo varía - Machine learning y chat bots para automatizar procesos | intuitivo | empresas, desarrolladores, agencias del gobierno | 
| Oracle Cloud | Tiene la mejor rentabilidad del mercado al analizar su precio comparado con el rendimiento ofrecido - Permite integrarse con otras nubes lo que facilita migrar de un sistema a otro - Ofrece baja latencia para cargas intensivas | Para aplicaciones empresariales que corren en la nube - Desarrollo de pruebas de softare | intuitivo | empresas, desarrolladores, agencias del gobierno |  




# Parte 3: Escenario hipotético: máquina virtual

## Contexto
Un cliente solicita una sola máquina virtual para ejecutar una aplicación interna.

Requisitos:
- Sistema operativo: Linux
- Carga de trabajo: media
- Uso continuo (24/7)
- Sin considerar redes ni seguridad


Evaluar únicamente:
- vCPU
- Memoria RAM
- Tipo de VM
- Precio mensual aproximado 

# Parte 4: Comparación de tamaños de VM
## 1. Selección de tamaños

Seleccione un tamaño de VM equivalente en cada proveedor (por ejemplo 2–4 vCPU y 8–16 GB RAM) 

Según DevX (2025), para cargas medianas de trabajo se recomienda seleccionar un tamaño de 2 vCPUs para cargas de trabajo medianas, por lo que se decide emplear ese tamaño para el dimensionamiento de la máquina virtual.  Por otro lado, se tiene que 1 OCPU = 2 vCPUs, según la calculadora de Oracle (Oracle, s. f.). 

- AWS -> 2 vCPU - 4 GiB 
- Azure -> 2 vCPU - 8 GB 
- Oracle -> 1 OCPU - 8 GB 

## 2. Comparación técnica


Complete la siguiente tabla utilizando los calculadores oficiales de cada proveedor (asuma 720 horas por mes):

|Proveedor Servicio de VM | vCPU | RAM (GB) | Familia / Tipo | Precio aprox. mensual (USD) | 
|-------------------------|------|----------|----------------|-------|  
| AWS | 2 | 4 GiB| t3 | $29.57/mes (1 año) | 
| Azure | 2 | 8 GB |D-series: D2 v3 |  $76.32/mes (1 año, pago por uso) | 
| Oracle | 1 OCPU  | 8 GB | VM.Standard.E5.Flex | $41.62/mes | 







# Bibliografía 

DevX. (2025). VMware Optimization: Best Practices for Peak Environment Performance – Size VMs Appropriately. DevX.https://www.devx.com/enterprise-zone/vmware-environments 

Oracle. (s. f.). Estimate cloud costs easily – Oracle Cloud Cost Estimator. Oracle Cloud Infrastructure. https://www.oracle.com/cloud/costestimator.html 
