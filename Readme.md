# Lab7IA

**Cuál implementación fue mejor?** <br>
*Modelo sin librerias:* <br>
DBI:  0.4357299277562183 <br>
CHI: 10100359.236780059 <br>

*Modelo usando librerias:* <br>
DBI: 0.4359511664337477 <br>
CHI: 10077069.205960162 <br><br>

**¿Por qué?** <br>
El algoritmo sin librerias se desempeñó ligeramente mejor y esto se ve demostrado por ambos índices de desempeño. La razon de esto probablemente se deba 
a que la implementación fue un poco más detallada, sacrificando un poco la eficiencia del algoritmo. Otra razón de esto es que Kmeans en su naturaleza
es un tanto susceptible a la ubicación inicial de los centroides y es posible que el algoritmo con librerías haya tenido unos centroides iniciales 
relativamente malos o el algoritmo sin librerías uno muy bueno. <br><br>