# InformeLaboratorio2

Integrantes: Jonathan Insuasti - Melany  Villa - César Garnica 

# 1. Objetivos 

Objetivo General
     
    - Identificar y estudiar el método de análisis de mallas el cual parte de la aplicación de LCK a un 
    conjunto mínimo de lazos para encontrar al final todas las corrientes de lazo. A partir de las 
    corrientes de lazo es posible encontrar todas las corrientes de rama.      
    
    Objetivos Específicos
     - Analizar y medir ciertas incógnitas mediante mallas en un circuito.
     - Comprobar que el análisis del circuito concuerde con los datos recogidos en el laboratorio.
     - Buscar la técnica más efectiva para el análisis delcircuito.


# 2. Marco Teórico

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Mapa%20Leyes%20de%20Kirchhoff.PNG)

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Mapa%20Analisis%20de%20Mallas.PNG)

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Materiales.Mallas.PNG)

# 3. Explicación  del procedimiento

Para realizar el calculo de intensidades mediante el circuito de Mallas primero debemos identificar cada malla, la malla se identifica como un circuito cerrado con elementos colocados en serie.

Una vez hemos identificamos las mallas procedemos a colocar la polaridad de los elementos ayudandonos de la simbologia, una vez hecho esto procedemos a dar un sentido en el que circule la corriente.

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Direccion%20de%20las%20corrientes.PNG)

Cuando tengamos todo esto realizado procedemos a hacer los calculos mediante las leyes de kirchoff para mallas, la cual nos dice que la sumatoria de voltajes sera igual a la sumatoria de resistencias por intencidades(Voltaje) ΣV=ΣI*R por cada malla.

Nos basamos en el sentido de la corriente que tomamos para tomar los valores de voltajes y resistencias de cada malla.

#  4. Respuestas 

Malla I

18V=0.82I1+I1-I2

18V=1.82I1-I2

Malla II

1.2I2+2.2I2+I2-I1-2.2I3=0

-I1+4.4I2-2.2I3=0

Malla III

-5V=2.2I3+0.39I3-2.2I2

-5V=2.59I3-2.2I2

Nos dan 3 ecuaciones con 3 incognitas, resolviendo las ecuaciones tenemos como resultado:

I1=11.4546mA

I2=2.875mA

I3=0.488mA

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Resultados%20medidos.jpeg)

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Resultados.jpeg)

![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Calculo%20de%20error%20corrientes.PNG)
![](https://github.com/mjvilla1/ImagenesLab2/blob/main/Calculo%20de%20error%20corrientes%201.PNG)


# 5. Video

https://www.youtube.com/watch?v=SFYcUKzjl3I

# 6. Conclusiones

- En este laboratorio realizado de manera “virtual” se pudo apreciar que los errores calculados se deben a que los componentes utilizados
 para el armado de circuitos no cuentan con alguna resistencia real, en el caso de las resistencias no cuentan con una tolerancia, 
 la cual en la realidad causa una notable variación.
 
 - No en todos los casos los valores teoricos seran igaules a los medidos, si se asemejaran. En la solución del circuito por medio 
 de LCK se llegará a una misma respuesta con una desfase de error mínimo.
 
-  Los resultados tanto del simulador como de las operaciones manuales dan variantes en cierta forma ya que las operaciones nos dan resultados teóricos en cambio en la simulación nos da resultados experimentales


# 7. Bibliografía 

Análisis de mallas - Análisis de circuitos I. (2021). Análisis de mallas - Análisis de circuitos I. Google.com. https://sites.google.com/site/proyectocircuitos1/analisis-de-mallas
