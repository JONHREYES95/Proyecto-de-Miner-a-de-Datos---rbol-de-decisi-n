Desafío Práctico 2: Datawarehouse y Minería de Datos
Este repositorio contiene los 3 procesos de RapidMiner (.rmp) creados para resolver el Desafío Práctico 2.

El núcleo del desafío fue un ejercicio de ingeniería de características (feature engineering). se nos proporcionaron archivos (estado_civil, primer_compra, whisky) que carecían de las columnas objetivo (Cliente Potencial y Forma de Pago).


La solución requirió crear estas variables faltantes usando lógica abstracta y las pistas proporcionadas (Ingreso, Precio, Estado Civil).

Procesos Incluidos
Proceso_1_Arbol_Premium.rmp:

Crea un modelo predictivo (Árbol de Decisión) para identificar el perfil de un "Cliente Premium" (definido como casa=1 Y auto=1).

Proceso_2_Filtro_Edad.rmp:

Un proceso de ETL simple para segmentar la tabla de clientes por un rango de edad (40-50).

Proceso_3_Simulacion_Pago.rmp:

Un proceso de ETL avanzado que simula un mercado (19 Clientes x 35 Whiskies = 665 ventas) para crear la variable Forma_de_Pago y luego aplicar el filtro solicitado.
