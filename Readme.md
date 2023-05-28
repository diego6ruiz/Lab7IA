# Lab7IA

**Cuál implementación fue mejor?** <br>
*Modelo sin librerias:* <br>
DBI:  0.42663115368256443 <br>
CHI: 8632874.224126376 <br>

*Modelo usando librerias:* <br>
DBI: 0.4174973212829125 <br>
CHI: 8639655.602421677 <br><br>

**¿Por qué?** <br>
El algoritmo con librerias se desempeñó ligeramente mejor y esto se ve demostrado por ambos índices de desempeño. La razon de esto probablemente se deba a que la implementación es mucho mas detallada, siendo casi la mejor implementación posible del problema. Otra razón posible de esto es que Kmeans en su naturaleza es un tanto susceptible a la ubicación inicial de los centroides y es posible que el algoritmo con librerías haya tenido unos centroides iniciales relativamente malos o el algoritmo sin librerías uno muy bueno. <br><br>