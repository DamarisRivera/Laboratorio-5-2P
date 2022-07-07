# Laboratorio-5-2P
# 1. OBJETIVOS 

**Objetivo General:**

* Analizar y comprobar de forma teórica y experimental, el Teorema de Thévenin con respecto a los voltajes y corrientes de un circuito eléctrico, esto se llevara a cabo mediante el desarrollo del presente laboratorio que abordará temas conocidos en la asignatura aplicado en un circuito eléctrico, por lo que se espera resultados similares, se utilizara Tinkerkad y se establecerá el porcentaje de error que tiene el método con respecto a los datos obtenidos mediante la simulación.

**Objetivo Específicos:**

* Explicar en que consiste el Teorema de Thévenin.

* Comprobar experimentalmente el teorema de Thévenin tanto para la corriente como para los voltajes comprobado por un circuito calculado y uno medido.

* Conocer la resistencia equivalente o la resistencia Thevenin y como estas interactúan con los componentes que integran dicho circuito.

* Comprender el uso de las leyes de Kirchhoff y como aplicarlo dentro de un circuito mixto utilizando simuladores virtuales que permitan su corroboración o en su defecto permita la localización de fallas.

# 2. MARCO TEORICO 

![image](https://user-images.githubusercontent.com/105617383/177440283-5c7727d8-3bb6-4a21-9ef3-8dc4cccaa621.png)

# 3. EXPLICACIÓN DEL PROCEDIMIENTO 

3.1 Construir el siguiente circuito:

![image](https://user-images.githubusercontent.com/105617383/177440698-03178f5a-7fc6-4d08-a474-2531747f76cb.png)

1. Calcular el voltaje del circuito por Thevenin, donde se omite la resistencia 5.
![image](https://user-images.githubusercontent.com/105671763/177682928-8a6ffeef-c77c-45f0-bd09-8605b9ab513d.png)

2. Volvemos las fuentes de voltaje tengan un valor de cero para calcular la resistencia de THhevenin.

![image](https://user-images.githubusercontent.com/105617383/177764541-d5a13b6b-4eb3-49fe-a837-e6393d2a9d32.png)

![image](https://user-images.githubusercontent.com/105671763/177683683-6d7f1cd2-db63-48a2-acdb-93ce4182281f.png)

![image](https://user-images.githubusercontent.com/105617383/177765305-4c131ab8-23d3-4ea0-a128-8c0f43612d69.png)

![image](https://user-images.githubusercontent.com/105671763/177684199-9d3ec9c0-9b66-4ef0-a65b-39331fb3d36f.png)

![image](https://user-images.githubusercontent.com/105617383/177766399-7fdc1e5f-d9d6-4c4e-9ccc-f607b10eea1e.png)

![image](https://user-images.githubusercontent.com/105671763/177684507-f9b66865-10ba-4d45-90ed-64df85adc644.png)

![image](https://user-images.githubusercontent.com/105617383/177767023-dc74422e-0a97-4232-ac4f-656e81393957.png)

**Cicuito Total**

![image](https://user-images.githubusercontent.com/105671763/177684830-d3bc7349-898a-428f-a05e-6c4a8ef5d9f0.png)

# 4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Simulación del circuito en Thinkercad.

4.1 Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 4.2.

![image](https://user-images.githubusercontent.com/105617383/177672441-e65e45d7-6a60-450d-825e-23d1cb209fee.png)

![image](https://user-images.githubusercontent.com/105617383/177672457-f81a2d78-99ac-474c-9eac-1c83b932d56e.png)

4.2 Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 4.1.

![image](https://user-images.githubusercontent.com/105617383/177672466-aca65ce5-551b-4eac-b930-eccb333dd53d.png)

4.3 Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 4.1.

![image](https://user-images.githubusercontent.com/105617383/177672479-0efc91d1-db44-400a-98d9-276c996275a5.png)

4.4 Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 4.2.

![image](https://user-images.githubusercontent.com/105617383/177672488-cca7ee76-53ed-4b57-a46d-44e59c03824f.png)

![image](https://user-images.githubusercontent.com/105617383/177672494-6281e661-52f8-458c-8a9a-5d180fb2e454.png)

Tabla 4.1. Valores del Circuito Equivalente de Thévenin
![image](https://user-images.githubusercontent.com/105671763/177704341-5f2a496b-07e2-4625-83f5-6a3cf0a4328b.png)

Tabla 4.2. Comprobación del Teorema de Thévenin.
![image](https://user-images.githubusercontent.com/105671763/177704385-0811d736-8e70-4120-9dea-41d3606a8404.png)

Tabla 4.3. Porcentaje de error de los valores del Circuito Equivalente de Thévenin
![image](https://user-images.githubusercontent.com/105671763/177704490-cef952f1-f8fb-43bc-90f8-f41d4ee11812.png)

Tabla 4.4. Porcentaje de error en la comprobación del Teorema de Thévenin.
![image](https://user-images.githubusercontent.com/105671763/177704525-88b04143-0433-41a8-a0bf-6173c44ae5a9.png)

# 5.VIDEO

https://youtu.be/Nh4uTmkMeSw

# 6.CONCLUSIONES

* EL teorema de thévenin trata de hallar un circuito equivalente con fuente de voltaje y para ello es necesario calcular el voltaje y la resistencia que se emplearan en otro circuito junto a la resistencia RL para crear un circuito, que al tomar la medidas de voltaje y corriente en RL sean las mismas que las del circuito original.

* Las medidas obtenidas analiticamente y en un simulador coinciden, por lo tanto el teorema de Thevenin si funciona para hallar un circuito equivalente al determinar los valores de RTH y VTH.

# 7.BIBLIOGRAFÍA

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.
