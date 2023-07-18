Caso: Detección de anomalías en datos financieros.

Descripción: Tienes un conjunto de datos financiero que contiene información sobre transacciones y deseas detectar transacciones inusuales o fraudulentas.
Solución: Uso de bibliotecas como Pandas, Scikit-learn y técnicas como Isolation Forest o One-Class SVM para identificar y etiquetar transacciones anómalas.
Luego, realiza un análisis adicional para determinar patrones comunes en las transacciones fraudulentas y tomar medidas preventivas."

   Monto       Fecha       Descripción  Cuenta
0   7370  2023-01-01  Compra en tienda    4177
1    960  2023-01-02          Depósito    9795
2   5490  2023-01-03  Retiro en cajero    7024
3   5291  2023-01-04  Retiro en cajero    6109
4   5834  2023-01-05     Transferencia    5146
Transacciones Anómalas:
     Monto       Fecha       Descripción  Cuenta  Anomalia
28     289  2023-01-29          Depósito    9766        -1
63     261  2023-03-05   Compra en línea    1951        -1
85     164  2023-03-27     Transferencia    4451        -1
108   9862  2023-04-19  Retiro en cajero    6005        -1
119    306  2023-04-30   Compra en línea    5177        -1
143   9889  2023-05-24     Transferencia    3599        -1
149   9821  2023-05-30   Compra en línea    2301        -1
191    302  2023-07-11   Pago de factura    2333        -1
199    297  2023-07-19     Transferencia    8715        -1
230    362  2023-08-19  Retiro en cajero    1329        -1
241   9974  2023-08-30   Pago de factura    3421        -1
247   9988  2023-09-05   Compra en línea    4993        -1
255    198  2023-09-13  Retiro en cajero    8124        -1
269   9819  2023-09-27  Compra en tienda    4042        -1
304    401  2023-11-01  Compra en tienda    8069        -1
310    290  2023-11-07  Compra en tienda    3050        -1
331    254  2023-11-28  Compra en tienda    8878        -1
...
Estadísticas del análisis:
Total de transacciones: 1000
Transacciones normales: 950
Transacciones anómalas: 50
