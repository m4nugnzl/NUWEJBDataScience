# Nuwe-JobBarcelona

https://nuwe.io/dev/competitions/job-barcelona-23/jobarcelona-23-data-science

# Contexto
Los datos provienen de un banco que dispone de una base de datos con una gran cantidad de información sobre sus clientes. Nuestro objetivo es el de predecir la tasa de abandono de estos clientes para así poder reducirla. La base de datos incluye información demográfica como la edad, el sexo, el estado civil y la categoría de ingresos. También contiene información sobre el tipo de tarjeta, el número de meses en cartera y los periodos inactivos. Además, dispone de datos clave sobre el comportamiento de gasto de los clientes que se acercan a su decisión de cancelación. Entre esta última información hay el saldo total renovable, el límite de crédito, la tasa media de apertura a la compra y métricas analizables como el importe total del cambio del cuarto trimestre al primero o el índice medio de utilización.

Frente a este conjunto de datos podemos capturar información actualizada que puede determinar la estabilidad de la cuenta a largo plazo o su salida inminente.

# Variables input

- `CLIENTNUM`: Id de cada cliente. *Int*
- `Attrition_Flag`: Indicador de si el cliente ha abandonado el banco o se queda *Bool* ( `0` abandonado `1` no) -> **TARGET**
- `Customer_Age`: Edad del cliente. *Int*
- `Gender`: Sexo del cliente. *Str*
- `Dependent_count`: Número de personas a cargo que tiene el cliente. *Int*
- `Education_Level`: Nivel educativo del cliente. *Str*
- `Marital_Status`: Estado civil del cliente. *Str*
- `Income_Category`: Ingresos del cliente. *Str*
- `Card_Category`: Tipo de tarjeta del cliente. *Str*
- `Months_on_book`: El tiempo que el cliente ha estado en los libros. *Int*
- `Total_Relationship_Count`: Número total de relaciones que tiene el cliente con el proveedor de la tarjeta de crédito. *Int*
- `Months_Inactive_12_mon`: Número de meses que el cliente ha estado inactivo en los últimos doce meses. *Int*
- `Contacts_Count_12_mon`: Número de contactos que ha tenido el cliente en los últimos doce meses. *Int*
- `Credit_Limit`: Límite de crédito del cliente. *Int*
- `Total_Revolving_Bal`: Saldo renovable total del cliente. *Int*
- `Avg_Open_To_Buy`: Ratio medio de apertura a la compra del cliente. *Int*
- `Total_Amt_Chng_Q4_Q1`: Importe total cambiado del trimestre 4 al trimestre 1. *Int*
- `Total_Trans_Amt`: Importe total de la transacción. *Int*
- `Total_Trans_Ct`: Recuento total de transacciones. *Int*
- `Total_Ct_Chng_Q4_Q1`: Recuento total cambiado del trimestre 4 al trimestre 1. *Int*
- `Avg_Utilization_Ratio`: Ratio de utilización medio del cliente. *Int*
- `Months_Inactive_12_mon`: Número de meses que el cliente ha estado inactivo en los últimos doce meses. *Int*
- `Contacts_Count_12_mon`: Número de contactos que ha tenido el cliente en los últimos doce meses. *Int*
- `Credit_Limit`: Límite de crédito del cliente. *Int*
- `Total_Revolving_Bal`: Saldo rotativo total del cliente. *Int*
- `Avg_Open_To_Buy`: Ratio medio de apertura a compra del cliente. *Int*
- `Total_Amt_Chng_Q4_Q1`: Importe total cambiado del trimestre 4 al trimestre 1. (Integer)
- `Total_Trans_Amt`: Importe total de la transacción. *Int*
- `Total_Trans_Ct`: Recuento total de transacciones. *Int*
- `Total_Ct_Chng_Q4_Q1`: Recuento total cambiado del trimestre 4 al trimestre 1. *Int*
- `Avg_Utilization_Ratio`: Ratio de utilización medio del cliente. *Int*


El trabajo se divide en dos ficheros:

- **Data Visualization**: visualización de los datos, análisis de la información, posibles ideas de variables interacción
- **Modelizado**: preprocesamiento de los datos y modelizado
