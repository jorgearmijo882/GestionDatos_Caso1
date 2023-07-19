Caso: Detección de anomalías en datos financieros.
Una entidad Bancaria ha identificado en el último mes un grupo de cuentas de usuario que ha tenido un comportamiento fuera de lo usual en las transacciones de transferencias, depósitos, compra de productos en tiendas en línea, transacciones de compras en locales comerciales en diferentes tiendas comerciales, de igual forma se ha identificado un alza en los retiros de dinero en efectivo de los cajeros automáticos. 

La Gerencia del Banco ha solicitado al científico de datos en conjunto con el analista de datos se realice un análisis de las transacciones realizadas por estas cuentas bancarias en los últimos seis meses y se genere un informe donde se pueda identificar las cuentas con comportamientos anómalos y presentar la información en gráficos estadísticos.


Se debe generar un programa basado en Python que permita realizar el análisis de las cuentas y sus transacciones para identificar patrones de comportamiento comunes en las transacciones que puedan considerarse como fraudulentas en base a la consecución de las mismas en los últimos 6 meses, el programa debe realizar la creación de un archivo con las cuentas identificadas como anómalas, así como también un archivo que contenga el informe del resultado del análisis con los valores de las cuentas analizadas, y los valores obtenidos para transacciones normales y anómalas.

  
De forma complementaria se debe generar un programa en Python que simule la creación de las cuentas bancarias con los datos del movimiento de: Compras realizadas en línea, Pago de facturas en comercios, Retiro de dinero de cajeros, transferencias bancarias, depósitos efectivizados en la cuenta, y compras en locales comerciales haciendo uso de los medios de pago disponibles por el banco. 

Para la solución del caso se puede hacer uso de librerías de Python como “scikit-learn” para aplicar el algoritmo de Isolation Forest que nos permitirá detectar anomalías en conjunto de grandes volúmenes de datos, se debe parametrizar el valor de la semilla de contaminación de la muestra, el valor de la semilla dependerá del volumen de datos generados para el análisis, de forma adicional se hace uso de librerías como pandas, numpy, matplotlib para la generación y presentación de datos y presentación de los mismos. 

Solución:
 
Se crea el programa para la generación de los datos aleatorios en base a los parámetros indicados. 
Se crea el programa para realizar el análisis de los datos generados con la impresión del numero de las cuentas en un archivo csv, la creación de un diagrama de pastel donde se visualice la cantidad de cuentas con datos anómalos y un archivo de texto de resumen que imprima el resultado del análisis realizado.
