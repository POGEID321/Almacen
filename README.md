# Almacen
Desarrollo de aplicación para la gestión de inventario en el área de repuestos, realizando el calculo de Ocupación, control de Stocks, Registro de entradas de químicos y representación de la distribución del almacén atraves de una interfaz virtual alimentada por información de SAP y una vista general de los indicadores del almacén.

AREA PRINCIPAL:
<img width="1187" height="792" alt="Captura de pantalla 2026-10-12 124328" src="https://github.com/user-attachments/assets/b2a9396e-7a52-4834-a199-1ec0fcf335b3" />

Area principal con campos de material, descripción, ubicación, stock, UMB, valor de stock y stock máximo, acompañada de herramientas de búsqueda y filtros por nombre o código. En la parte inferior se visualiza una distribución gráfica de estantes con indicadores de ocupación porcentual, número de cajas y objetos sin caja, además de botones de navegación entre áreas. Dichos datos vienen de una lista ya de medidas y organizacion dentro del almacen.


AREA DE PERFILES:
<img width="1187" height="791" alt="Captura de pantalla 2026-10-12 130136" src="https://github.com/user-attachments/assets/89e5e2e0-57f6-4d1f-b684-89c8237f834e" />


AREA DE QUIMICOS:
<img width="1187" height="793" alt="Captura de pantalla 2026-10-12 130145" src="https://github.com/user-attachments/assets/b412e92a-440a-4c94-a8b6-a58a73ad3103" />

VISTA POR SECCION:
<img width="1187" height="788" alt="Captura de pantalla 2026-10-12 124346" src="https://github.com/user-attachments/assets/a4193445-3c7c-49d2-a915-f62c72f86f44" />
Muestra la distribucion de las cajas dentro del almacen, por disposicion de codigo de material o por Numero de objetos dentro de dichas, para objetos que no se encuentran dentro, se realiza el calculo de ocupacion y los colores corresponden a el tipo objeto, Caja, Rollo o sin caja.

<img width="1190" height="797" alt="Captura de pantalla 2026-10-12 130552" src="https://github.com/user-attachments/assets/aec0bc60-d106-4a7c-8c48-986f949eb71f" />

HISTORICO:
<img width="1010" height="525" alt="image" src="https://github.com/user-attachments/assets/f0045365-e3f9-4ee7-b6fd-75a6c302a6ea" />
Historico de Stock, Consumo y movimientos de un material seleccionado de la tabla de Materiales, los datos fueron crizados con el historial de movimientos.

REGISTRO DE CONSUMO EN CONTENEDORES DE QUIMICOS:
<img width="1006" height="631" alt="Sin título" src="https://github.com/user-attachments/assets/8878fcc3-b274-455b-b6d5-9fc23d7fe436" />
LLeva el registro de quimicos consumidos por produccion y la distribucion de estos, ademas de registrar todos estos datos en un mismo lugar.

Registro de Objetos Nuevos o Objetos no definidos:
<img width="1187" height="800" alt="Captura de pantalla 2026-10-12 130157" src="https://github.com/user-attachments/assets/503a6d1c-0291-4ebd-8fc1-7ade90c029cf" />
Es un espacio para cambiar los valores de aquellos elementos cuyas dimensiones o numero de elementos que ocupan una caja, por lo cual se define las dimensiones del elemento o el recipiente en el cual ocupa su espacio.

KPIs en Desarrollo:

KPIs de Inventario y Stock
Tasa de rotación de stock: Mide cuántas veces se renueva el inventario en un año. En el sector de automoción y recambios, el rango típico de referencia es de 6 a 8 veces al año.

Exactitud de inventario: Compara lo que registra el sistema informático frente a la cantidad real que hay físicamente en los estantes. Lo ideal es buscar un porcentaje superior al 98%.

Nivel de obsolescencia: Porcentaje de repuestos que llevan mucho tiempo sin movimiento (generalmente más de 12 meses) y ocupan espacio valioso.
Cobertura de stock: Indica para cuántos días o meses alcanza el inventario actual según el ritmo de ventas actual.

Porcentaje de ocupación del almacén: Mide el espacio físico utilizado frente al total disponible. Un almacén empieza a perder agilidad y orden cuando supera el 85% de ocupación.

Tiempo de ciclo de pedido: El tiempo que tarda el almacén desde que se recibe la solicitud del repuesto hasta que está listo para la entrega o despacho.



