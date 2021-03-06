# Laboratorio-5
 
 # Objetivos
 
 **Objetivo General**
 
 - Analizar y comprobar experimentalmente el Teorema de Thévenin aplicandolo a traves de su solución analógica y su simulacion en programas como tinkercad y proteus, de esta manera familiarizarse con el concepto y su efectividad dentro de la resolución de circuitos resistivos. 
 
 **Objetivos específicos**
 
-	Aplicar el teorema de Thévenin de forma correcta, teniendo en cuanta la teoría y conceptos como circuito abierto, divisor de corriente y voltaje, para la resolución del ejercicio planteado
-	Armar correctamente los circuitos, usando los elementos y valores de resistencias y voltajes asignados.
-	Determinar los valores de voltaje y corriente en la resistencia que nos indica el ejercicio.
-	Obtener un error menor del 5% en los valores obtenidos ya sea mediante los cálculos, los que se realizaron en Tinkercad y los obtenidos en Proteus
-	Construir el circuito equivalente en Tinkercad y realizar las mediciones correspondientes.

# Marco Teorico

[![Marco-Teorico.png](https://i.postimg.cc/7ZB1n9TN/Marco-Teorico.png)](https://postimg.cc/tsxVXhk1)

# Explicación del Procedimiento

**Requisitos Previos**

Para el circuito mostrado en la figura 5.1:

a) Determine el valor de voltaje y corriente en el resistor R5. Anote los resultados en la tabla 5.2.

b) Obtenga los valores del circuito equivalente de Thévenin y anótelos en la tabla 5.1.

**Información General**

Una de las maneras de simplificar y facilitar el análisis de circuitos eléctricos y
electrónicos es por medio del Teorema de Thévenin que establece que:

*Un circuito eléctrico puede representarse con un circuito dual o equivalente,
representado por una sola fuente de voltaje en serie con una resistencia. El valor de la
fuente de voltaje se conoce como el “voltaje de Thévenin” y la resistencia en serie como
“resistencia de Thévenin”.*

El voltaje de Thévenin (VTH) es el voltaje en circuito abierto entre las terminales
del circuito para el cual se requiere el equivalente de Thévenin.

La resistencia de Thévenin (RTH) es la resistencia equivalente vista de la terminal
del circuito para el equivalente de Thévenin, con las fuentes de alimentación en cero.

**Material y equipo Requerido**

|**CANTIDAD**| **ELEMENTO**|
|:---: | :---: |
| 2 | Fuente de voltaje de C.D |
| 2 | Multimetros digitales |
| 1 | Resistor de 560 Ω |
| 1 | Resistor de 4.7 kΩ |
| 1 | Resistor de 330 Ω |
| 1 | Resistor de 100 Ω |
| 1 | Resistor de 1 kΩ |
| 1 | Potenciómetro de precisión 1 kΩ |
| 1 | Protoboard |

**Procedimiento**

- Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/93739242/148700128-52db4d71-8270-414d-910b-c1f4a5849941.png)

- Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.
- Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.
- Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.
- Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

**Circuitos en tinkercad**

![imagen](https://user-images.githubusercontent.com/93798427/148468323-1e560e00-3558-4d92-90cc-1e5c8b4a1ad9.png)

![imagen](https://user-images.githubusercontent.com/93798427/148468337-c7409736-feae-4707-a982-b3b4cb643167.png)

![imagen](https://user-images.githubusercontent.com/93798427/148468359-79ff894a-5b1b-453b-98a8-c6763d0a8bce.png)

![imagen](https://user-images.githubusercontent.com/93798427/148468378-d0136f9e-dc57-4dc4-8e8a-a638349cdbbf.png)

![imagen](https://user-images.githubusercontent.com/93798427/148843640-ab0343d7-2071-454b-afb4-c8b27cee7524.png)

**Utilizando el potenciometro de 500ohms**

[![Thevenin-final.png](https://i.postimg.cc/K85sTCbp/Thevenin-final.png)](https://postimg.cc/gxnDFSn3)

**Resistencia del potenciometro**

[![Thevenin-final-2.png](https://i.postimg.cc/hG68Q0X3/Thevenin-final-2.png)](https://postimg.cc/R31JjKQc)


**Circuito en Proteus**

Circuito Original

![image](https://user-images.githubusercontent.com/93739242/148840406-223f5137-1635-41eb-a0ed-b51f04bbb54f.png)

Desconectando R5

![image](https://user-images.githubusercontent.com/93739242/148840508-d06aa658-498e-4e49-b707-78a2c258d003.png)

Quitando las fuentes de Energia

![image](https://user-images.githubusercontent.com/93739242/148840632-76e400b8-cfd8-428a-aa8b-74cb9d4e89e4.png)

Circuito Equivalente de Thevenin

![image](https://user-images.githubusercontent.com/93739242/148840943-90dffb3e-f689-40ac-94b0-d608acb34677.png)



**Procedimiento** 

[![Thevenin-1.png](https://i.postimg.cc/v861mmD8/Thevenin-1.png)](https://postimg.cc/t7pRSph8)

[![Thevenin-2.png](https://i.postimg.cc/fRgZXxgG/Thevenin-2.png)](https://postimg.cc/Hr5f17mz)

# Respuesta al Interrogante y Calculo del Error

| **VTH(V)** |     | **RTH(Ω)**|   |
| ------------- | ------------- | ------------- |------------- |  
| MEDIDO | 5.06V |   MEDIDO | 299 |  
| CALCULADO | 5.04V |   CALCULADO | 298.09 |  
| % ERROR |  0.39% |   %ERROR | 0.03% |  




| **PARAMETRO ELECTRICO** |**CIRCUITO ORIGINAL**|  | **CIRCUITO EQUIVALENTE DE THEVENIN**| |
|:---: | :---: |:---: | :---: | :---: |
| | Calculado  |    Medido      |  Calculado  |  Medido  |
| Voltaje (V) | 3.88 V |     3.89 V     |  3.88 V  |  3.89 V  |
| Corriente (mA) | 3.88 mA |   3.89 mA   |  3.88 mA  |  3.89 mA   |
| %ERROR | | 0.25% | | 0.25% | 


# Video

https://youtu.be/uAExXYsRb64

# Conclusiones

- La aplicación del teorema de Thevenin facilito la resolución del circuito, permitiendo plantear un circuito más sencillo para analizar. 
- Al obtener los valores teoricos y compararlos con los medidos se observa que no hay mucha diferencia asegurando asi que el circuito resuelto y armado en un simulador y sus resultados estan correctos.



# Bibliografía

- X. (2020, 20 julio). de Thevenin explicado para que lo Entiendas. Teorema. https://www.teorema.top/teorema-de-thevenin/


