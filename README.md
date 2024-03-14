# Caso de estudio
En la búsqueda de competividad, las empresas buscan brindar el mejor servicio a sus clientes y
maximizar su ganancia. Es por ello que en el siguiente trabajo se analizará el comportamiento del cliente
de una empresa de comestibles. Esto ayudará a la compañía a comprenderlos mejor y les facilitará la
modificación de sus productos de acuerdo con las necesidades, comportamientos e inquietudes
específicas de los diferentes tipos de clientes. La empresa podrá analizar qué segmento de clientes es
más probable que compre tal producto y por qué medio, para luego comercializar tal producto en ese
segmento en particular.
# Objetivos
- Predecir qué segmentos de clientes son los que más productos compran.
- Predecir por qué medio realizan sus compras.
# Conjunto de datos
El archivo “marketing_campaign.csv” contiene datos recopilados de 2440 personas de una campaña de
marketing, donde nuestra tarea es predecir cómo responderán los diferentes segmentos de clientes, de
las cuales se registran los siguientes atributos:
## Cliente
- ID: Identificador único del cliente.
- Year_Birth: Año de nacimiento del cliente.
-Education: Nivel de educación del cliente.
- Marital_Status: Estado civil del cliente.
- Income: Ingresos familiares anuales del cliente.
- Kidhome: Número de niños en el hogar del cliente.
- Teenhome: Número de adolescentes en el hogar del cliente.
- Dt_Customer: Fecha de alta del cliente en la empresa.
- Recency: Número de días desde la última compra del cliente.
- Complain: 1 si el cliente se quejó en los últimos 2 años, 0 en caso contrario.
## Productos
- MntWines: Cantidad gastada en vino en los últimos 2 años.
- MntFruits: Cantidad gastada en frutas en los últimos 2 años.
- MntMeatProducts: Cantidad gastada en carne en los últimos 2 años.
- MntFishProducts: Cantidad gastada en pescado en los últimos 2 años.
- MntSweetProducts: Cantidad gastada en dulces en los últimos 2 años.
- MntGoldProds: Cantidad gastada en oro en los últimos 2 años.
## Promoción
- NumDealsPurchases: Número de compras realizadas con descuento
- AcceptedCmp1: 1 si el cliente aceptó la oferta en la 1.ª campaña, 0 en caso contrario.
- AcceptedCmp2: 1 si el cliente aceptó la oferta en la 2ª campaña, 0 en caso contrario.
- AcceptedCmp3: 1 si el cliente aceptó la oferta en la 3ra campaña, 0 en caso contrario.
- AcceptedCmp4: 1 si el cliente aceptó la oferta en la 4ª campaña, 0 en caso contrario.
- AcceptedCmp5: 1 si el cliente aceptó la oferta en la 5ª campaña, 0 en caso contrario.
- Respuesta: 1 si el cliente aceptó la oferta en la última campaña, 0 en caso contrario.
## Lugar
- NumWebPurchases: Número de compras realizadas a través de la web de la empresa.
- NumCatalogPurchases: Número de compras realizadas utilizando un catálogo.
- NumStorePurchases: Número de compras realizadas directamente en las tiendas.
- NumWebVisitsMonth: Número de visitas al sitio web de la empresa en el último mes.
