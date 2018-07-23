## Evasión de obstáculos apoyada en localización basada en simulación de instancias. 
### Navegación autónoma en entornos cerrados.


Este artículo, detalla el uso dado a la implementación de dos algoritmos, con una gran componente estocástica, en la creación de un sistema de navegación en entornos cerrados. 

El primero, denominado Filtro de Partículas, e introducido en 1993 por N. Gordon, D. Salmond y A. Smith, proporciona un mecanismo de localización basado en filtros bayesianos recursivos, haciendo uso del método de Montecarlo. 
Se tratará de estimar la posición, realizando múltiples simulaciones del entorno en el que se desplaza el agente. 

El segundo algoritmo, denominado Vector Field Histogram, Histograma de Campos Vectoriales, o VFH por su sigla en inglés, fue introducido por Borenstein y Koren en el año 1991, proporciona un método de evasión de obstáculos basado en el planeamiento, local, de la ruta a seguir por el agente. 

Trabajando de forma conjunta, proporcionan un método de evasión de obstáculos y planeamiento de rutas tremendamente robusto.
