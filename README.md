# Informe-Laboratorio-5

## 1. OBJETIVOS
 
        General: 
        
Comprobar experimentalmente el teorema de Thévenin en un circuito resistivo.

        Específicos: 
 
1. Armar un circuito resistivo y realizar mediciones de voltaje y corriente en dicho circuito mediante el uso del simulador Tinkercad.
        
2. Aplicar el teorema de Thévenin para el correcto cálculo de la resistencia de Thévening y el voltaje de thévening en el circuito previamente armado.
        
3. Comprobar que los resultados teóricos calculados mediante el teorema de Thévenin coincidan con los valores medidos en el simulador Tinkercad.
 

## 2. MARCO TEÓRICO

![Blank diagram (4)](https://user-images.githubusercontent.com/93826527/148281324-145841db-0ab8-4482-8a53-1e60c5decbe4.png)

![Screenshot 2022-01-05 150159](https://user-images.githubusercontent.com/93826527/148281379-8a97b1b3-c157-4989-87c0-7ad340a909a1.png)

![Screenshot 2022-01-05 150227](https://user-images.githubusercontent.com/93826527/148281427-f5a42f35-9587-4a18-9bc1-c1f90f782528.png)

![Screenshot 2022-01-05 150304](https://user-images.githubusercontent.com/93826527/148281490-000773f3-51a7-4c9d-b7a4-28a81bbc7c59.png)

![Screenshot 2022-01-05 150330](https://user-images.githubusercontent.com/93826527/148281537-e2563599-e3ad-48eb-92fa-e5b0e7d5c25e.png)

![Screenshot 2022-01-05 150401](https://user-images.githubusercontent.com/93826527/148281611-8c5dacae-28a6-45ea-ab1a-2a77f9cdebbe.png)

![Screenshot 2022-01-05 150432](https://user-images.githubusercontent.com/93826527/148281687-91697d15-41a9-4b3b-985f-e85308f0df86.png)

**MATERIALES**

![image](https://user-images.githubusercontent.com/93396250/148418977-c0efaeb1-2c2a-4c96-8afc-34f67921733e.png)


## 3. EXPLICACIÓN DEL PROCEDIMIENTO

**5.5.1. Arme el circuito que se muestra en la figura 5.1.**

![image](https://user-images.githubusercontent.com/93396250/148305089-399b9fef-c15c-45b2-b1e8-bd3d795bfea2.png)

Circuito implementado en ThinkerCAD: https://www.tinkercad.com/things/hCf08HHYSDI-cool-fyyran-jaiks/editel?sharecode=fPQQdrLt0FEgd6lRKPTzF-OUD_cki11A-CfPapgzO08

![image](https://user-images.githubusercontent.com/93396250/148307513-f69bc9b8-276e-4de6-8159-89762e757114.png)


**5.5.2. Mida el voltaje y la corriente en el resistor R5**

En la siguiente imagen podemos observar la medicion del voltaje en R5

![Voltaje 2](https://user-images.githubusercontent.com/93834732/148552153-93246f31-37a3-4717-8e25-ec6ddd5a826f.GIF)

En la siguiente imagen podemos observar la medicion de corriente en R5

![Corriente](https://user-images.githubusercontent.com/93834732/148552279-0d389324-825d-45cb-a907-a1b66cd16777.GIF)


**5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto.**

En la siguiente imagen podemos observar la medicion del voltaje del circuito sin R5

![Voltaje](https://user-images.githubusercontent.com/93834732/148551946-3de515fd-488c-423b-bc3b-a88b1c8c5637.GIF)



**5.5.4 Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente.**

![Screenshot 2022-01-05 144040](https://user-images.githubusercontent.com/93826527/148278631-407bd5c9-31fb-475c-a400-a7479ec06f57.png)


**5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo.**


**VTH**

Para calcular el voltaje de Thévenin hacemos el siguiente análisis en el circuito

![VTH](https://user-images.githubusercontent.com/93396250/148552359-b07a4994-978c-4734-a338-595867fc5380.jpg)


![image](https://user-images.githubusercontent.com/93396250/148469556-ef5d070c-cc61-4f93-9e9a-935bd0159b07.png)


**RTH**

Para calcular la resistencia de Thévenin hacemos el siguiente análisis en el circuito, reemplazando las fuentes de voltaje por sus resistencias internas (un cable). 

![RTH](https://user-images.githubusercontent.com/93396250/148552344-f91b2b74-e61e-4534-b754-63fa273e271f.jpg)


![image](https://user-images.githubusercontent.com/93396250/148469578-ecc51fe9-7ae5-426d-8d45-2f19558671fe.png)


**INTENSIDAD**

Para calcular la intensidad usamos la Ley de Ohm

![image](https://user-images.githubusercontent.com/93396250/148469776-db413449-7f1b-4a39-acf1-03e61553fd59.png)


**Circuito equivalente de Thévenin**

![image](https://user-images.githubusercontent.com/93396250/148468727-69c3b664-edce-49b7-b2c4-37533492a73b.png)

Voltaje y corriente en el circuito equivalente de Thévenin

![image](https://user-images.githubusercontent.com/93396250/148469026-941eca21-180b-4f80-9c9d-ebd00199e228.png)




## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR
      
**CIRCUITO ORIGINAL: Voltaje y Corriente**

![image](https://user-images.githubusercontent.com/93396250/148552546-1a33d1b1-e592-4a25-8d4b-4ee396189cb0.png)



**CIRCUITO EQUIVALENTE: Voltaje y Corriente**

![image](https://user-images.githubusercontent.com/93396250/148494804-cdccd86a-eff4-4e2e-a8c5-3883875e1dda.png)


        5.5.2. anote los resultados en la tabla 5.2

        5.5.3. Anote el valor medido en la tabla 5.1

        5.5.4. Anote el valor medido en la tabla 5.1.

        5.5.5. Anote los resultados en la tabla 5.2.

Tabla 5.1. Valores del Circuito Equivalente de Thévenin.

![image](https://user-images.githubusercontent.com/93396250/148496194-81dd2fee-8a9c-4376-9b45-e90d6c2e9d95.png)



Tabla 5.2. Comprobación del Teorema de Thévenin.

![image](https://user-images.githubusercontent.com/93396250/148495400-0742135d-06d0-419b-88c8-961d351ba6e8.png)


**PORCENTAJE DE ERROR**

Formula del porcentaje de error

![image](https://user-images.githubusercontent.com/93396250/148498818-6f92a1c2-8396-4d17-985f-f4b17c0c6d34.png)


Tabla 5.3. Valores del porcentaje de error para la Tabla 5.1.

![image](https://user-images.githubusercontent.com/93396250/148500062-4d8a05db-e220-467a-a098-5ee0895a3b57.png)


Tabla 5.4. Valores del porcentaje de error para la Tabla 5.2.

![image](https://user-images.githubusercontent.com/93396250/148500168-6a3eec82-7e7d-4a4b-b647-addbfd707167.png)



## 5. VIDEO

        Link del video ¨Informe de laboratorio 5¨ en donde se comprueba experimentalmente el Teorema de Thévenin en un circuito resistivo.
 
https://youtu.be/6QhrVNpCMcg
 
[![Presentación Informe 5](https://img.youtube.com/vi/6QhrVNpCMcg/0.jpg)](https://www.youtube.com/watch?v=6QhrVNpCMcg)



## 6. CONCLUSIONES


   1. Se ha logrado el correcto armado y funcionamiento del circuito propuesto en el laboratorio, se ha usado el simulador tinkercad para el armado de dicho circuito.
        
   2. Se usó el teorema de Thévenin para el cálculo del voltaje de R5 y la corriente que pasa por R5, así mismo también se usó este teorema para calcular el voltaje en el circuito cuando R5 se ve anulado.
        
   3. Se pudo corroborar que tanto los valores calculados teóricamente mediante el teorema de Thévening y los valores medidos en el simulador Tinkercad han coincidido, con esto podemos concluir que el teorema de Thévenin es correcto.

## 7. BIBLIOGRAFÍA

Alulema Darwin. Guías Segundo Parcial https://drive.google.com/file/d/1VR4dK9AqSu7R8K1Jd08_cN-j99_ptY_K/view


