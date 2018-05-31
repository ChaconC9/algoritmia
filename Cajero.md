#Pedir_prestado_a_un_amigo

##Problemática
El usuario necesita que le presten dinero, solo tiene billetes de 100, no se tienen otras cantidades menores ni mayores y lo que se puede prestar es infinito. decir cuantos billetes le debe entregar y cuanto dinero no le puede prestar ejemplo 120$ se debe de dar 1 billete de 100 y no se pueden prestar 20$

##Pseudocódigo
BILLETES = 100
Leer dinero_pedido

BILLETES_A_PRESTAR = dinero_pedido/BILLETES
DINERO_QUE_NO_SE_PUEDE = dinero_pedido%BILLETES
Imprimir BILLETES_A_PRESTAR
Imprimir DINERO_QUE_NO_SE_PUEDE

Fin

##Corridas de escritorio
BILLETES = 100
dinero_pedido = 2003
BILLETES_A_PRESTAR = 2003/100=20
DINERO_QUE_NO_SE_PUEDE = 2003%100=3

BILLETES = 100
dinero_pedido = 54863
BILLETES_A_PRESTAR = 54863/100=548
DINERO_QUE_NO_SE_PUEDE = 54863%100=63

BILLETES = 100
dinero_pedido = 8383
BILLETES_A_PRESTAR = 8383/100=83
DINERO_QUE_NO_SE_PUEDE = 8383%100=83
