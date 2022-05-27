# CIRCUITOS-LAB-2

1. Objetivos 

   1.1. Objetivo General 

Comprobar el cumplimiento de la técnica de análisis de mallas, mediante el análisis de los circuitos eléctricos, las simulaciones y las prácticas de laboratorio físicas, para afianzar los conocimientos adquiridos en clase.

   1.2. Objetivos Específicos:

-Resumir que es el análisis de mallas, la ley de Kirchhoff de Voltajes y la ley de la conservación de la carga, a partir de una búsqueda bibliográfica.

-Calcular las medidas de cada una de las corrientes de las mallas, mediante la construcción del circuito de forma física, simulador de Tinkercad y ecuaciones algebraicas aplicando el análisis de las mallas

-Justificar el desarrollo del laboratorio, mediante la presentación de un video, en el que se explique el funcionamiento y la implementación del proyecto.


2. Marco Teórico

![WhatsApp Image 2022-05-26 at 8 47 46 AM](https://user-images.githubusercontent.com/94011974/170503573-9f2199ea-69e2-4acd-bd09-77208cd3f1c6.jpeg)

![WhatsApp Image 2022-05-26 at 8 48 13 AM](https://user-images.githubusercontent.com/94011974/170503616-725587dd-fdc5-4de9-8418-7388aee8509a.jpeg)

![WhatsApp Image 2022-05-26 at 8 48 34 AM](https://user-images.githubusercontent.com/94011974/170503676-6d3f92d3-eacd-49d0-8794-907554649f8c.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 10 AM](https://user-images.githubusercontent.com/94011974/170503727-96f3cba0-d022-4ab9-8cf3-a52c94a3d935.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 34 AM](https://user-images.githubusercontent.com/94011974/170503760-17543032-d15c-4857-a46a-0d33c1618c86.jpeg)

![WhatsApp Image 2022-05-26 at 8 49 58 AM](https://user-images.githubusercontent.com/94011974/170503858-4367fca0-1537-4539-8709-8693729a1ce2.jpeg)

3. Requerimientos previos

Análisis de mallas

![WhatsApp Image 2022-05-26 at 9 15 26 AM](https://user-images.githubusercontent.com/94011974/170505990-6f22adfb-5e7f-4884-859d-56a7d36f58f4.jpeg)

Circuito armado

![WhatsApp Image 2022-05-26 at 9 08 11 AM](https://user-images.githubusercontent.com/94011974/170504633-5a0e060e-6e7c-4867-aa1d-aa5ac5eb236c.jpeg)

Circuito para el análisis de mallas

![image](https://user-images.githubusercontent.com/94011974/170368099-dd353d06-50a3-46cf-a3a4-ba8d6ab130b0.png)

Malla 1

![image](https://user-images.githubusercontent.com/94011974/170368117-ae78efe6-f110-4c5d-be37-99ad8561f6d7.png)

Malla 2

![image](https://user-images.githubusercontent.com/94011974/170368148-bccfe9fd-6984-48f1-92f9-db1b6184a1cf.png)

Malla 3

![image](https://user-images.githubusercontent.com/94011974/170368161-37ccb8d9-b2af-4b7f-8202-a12b9393f76f.png)

4. Materiales y equipos requeridos

![image](https://user-images.githubusercontent.com/94011974/142951161-85a7ecea-bf4d-45bb-81eb-164e07b5fcc8.png)

5. Procedimiento

MALLA 1: 

5V – V1 - V2 = 0 

5 V – I1 * 820 Ω - (I1 – I2) * 1000 Ω = 0  (1ra Ecuación)

MALLA 2:

- V3 – V4 – V2 = 0

I2 * 1200 Ω + (I2 – I3) * 2200 Ω + (I2 – I1) * 1000 Ω = 0  (2da Ecuación)

MALLA 3:

-V5 – 10 V – V4 =0

I3 * 390 Ω + 5V + (I3 – I2) * 2200 kΩ = 0  (3ra Ecuación)

Resolviendo los sistemas de ecuaciones con las ecuaciones (1) , (2) y (3). 
Se obtienen los resultados siguiente:

![image](https://user-images.githubusercontent.com/94011974/170371320-9b68e805-42eb-4ee0-b173-8aa353966f3b.png)
 
I1 =  3 mA

I2 =  2.3 mA

I3 =  0.48 mA

![image](https://user-images.githubusercontent.com/94011974/170400361-ac0da96e-71e1-4e44-945c-783e441d2e3f.png)

6. Cálculo de error

![image](https://user-images.githubusercontent.com/105259459/170612405-654b2569-e28d-41bc-8f29-854b72a4b69a.png)

![image](https://user-images.githubusercontent.com/105259459/170612438-9e6d6e90-a66b-4ce6-9656-929757587527.png)

![image](https://user-images.githubusercontent.com/105259459/170612452-03a88373-8381-4e98-bd52-b596eed3a43c.png)

![image](https://user-images.githubusercontent.com/105259459/170612504-9bf8188c-2a24-451b-a039-cbcd249dcc95.png)


7.  Video

8. Conclusiones

-En base a las bibliografías investigadas, se concluye que, para el análisis de mallas, asigna y dibuja corrientes independientes en cada malla, es necesaria la segunda ley de Kirchhoff, la cual nos dice que la suma algebraica de los voltajes es una malla cerrada debe ser cero y se debe tener cuidado con la dirección de la corriente. Con respecto a la ley de la conservación de la carga los componentes ganan y pierden energía dependiendo del elemento.

-Usando el simulador de Tinkercad y armando un circuito electrónico físico, se midió las corrientes de cada malla. Mientras que para obtener el valor calculado se utilizan aplicaciones algebraicas, en este caso la técnica del análisis de mallas, que asigna corrientes independientes a cada malla al terminar su resolución

-En el video realizado se explica la construcción del circuito físico y los componentes que se utilizaron, junto con la simulación de Tinkercad.  Se ubican las resistencias, los cables y las fuentes de voltaje que son los cargadores, para la fuente de voltaje de 10 V se unieron dos cargadores de 5 voltios. Se procede a medir las corrientes comprobando la ley de Kirchhoff y el análisis de mallas. 


9. Bibliografía

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

10. Rubrica

![image](https://user-images.githubusercontent.com/94011974/169427061-265123c2-f557-4b9a-9ef6-5a545e89aff2.png)
