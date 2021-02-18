# Laboratorio 5
1. OBJETIVOS
- Objetivo General:
   
   - Utilizar el teorema de Thévenin para utilizarlo prácticamente dentro de distintios circuitos eléctricos.
   
- Objetivos Específicos:
 
   - Determinar la resistencia equivalente dentro del circuito.
   - Determinar el voltaje que circula en una resistencia para obtener la fuente de voltaje de Thévenin.
   - Obtener el circuito simplificado de Thévenin y comprobar que la corriente y el voltaje que pasan por la resistencia son las mismas.
   
2. MARCO TEÓRICO
   
   ![image](https://user-images.githubusercontent.com/76133212/108288009-ccfb9580-7159-11eb-82cf-7d5c1e920320.png)

   
4. DIAGRAMAS
   - Modelo Del Circuito
   
   ![image](https://user-images.githubusercontent.com/75439689/108273068-155a8980-7141-11eb-9c75-171ccb45f0cc.png)

   *Figura 3.1*
   
   - Materiales Del Circuito
   
   ![image](https://user-images.githubusercontent.com/75439689/108273129-273c2c80-7141-11eb-97c2-a097f8bb2f31.png)
   
   *Figura 3.2*
   
   - Circuito Armado

   ![image](https://user-images.githubusercontent.com/75439689/108273213-43d86480-7141-11eb-91cb-2f60aebcf6ab.png)

   *Figura 3.3*
   
   - Mediciones de Voltaje y Corriente a través de R5
   
   ![image](https://user-images.githubusercontent.com/75439689/108273360-73876c80-7141-11eb-965b-dd38a73e533a.png)
   
   *Figura 3.4*
   
   - Mediciones de Resistencia y Voltaje de Thévenin
   
   ![image](https://user-images.githubusercontent.com/75439689/108273378-797d4d80-7141-11eb-89ff-b5e4d3256676.png)
   ![image](https://user-images.githubusercontent.com/75439689/108273538-ae89a000-7141-11eb-88a3-030de9ffd77a.png)
   
   *Figura 3.5 y 3.6*
   
   - Circuito de Thévenin
   
   ![image](https://user-images.githubusercontent.com/75439689/108273617-c6612400-7141-11eb-975e-95599b706744.png)
   ![image](https://user-images.githubusercontent.com/75439689/108273631-cb25d800-7141-11eb-8bf3-0eeae2a5db22.png)
   
   *Figura 3.7 y 3.8*
   
4. LISTA DE COMPONENTES
   
   ![image](https://user-images.githubusercontent.com/75439689/108274097-7040b080-7142-11eb-98c0-d9c431c00f0b.png)
   
   *Figura 4.1*

5. EXPLICACIÓN

   5.1. Procedimiento
   
     - Ingresar a la plataforma Tinkercad y crear un nuevo circuito, en el cual se escogen los componentes listados anteriormente con los valores predispuestos (tanto de voltaje como de resistencia)
     - Conectar 3 mallas, donde la primera contenga la fuente de 12V, la resistencia R1 y la resistencia R2; la segunda con R2, la fuente de 2V y R3; y por último la tercera malla con las resistencias R3, R4 y R5.
     - Medir el voltaje y la corriente de R5 para compararlos con los que se obtendrán mediante la aplicación del teormema de Thévenin.
     - Desconectar R5 y medir el voltaje entre las terminales abiertas del circuito (voltaje de Thévenin VTH).
     - Reemplazar las fuentes de alimentación por sus resistencias internas (en este caso R=0ohm en ambas fuentes) y medir la resistencia equivalente del circuito desde la terminal abierta (resistencia de Thévenin RTH)
     - Con el voltaje y la resistencia medidos, se procede a armar el circuito equivalente de Thévenin. Conformado por una fuente de voltaje con valor VTH, conectada en serie con una resistencia de valor RTH y con R5.
     - Medir la corriente y el voltaje de R5 en el circuito equivalente de Thévenin. Los cuales equivalen a los valores medidos de R5 en el circuito original.

   5.2. Tablas de Valores.
   
- Valores de Circuito Equivalente de Thévenin.
   
   ![image](https://user-images.githubusercontent.com/75439689/108279907-5f486d00-714b-11eb-84d2-351a415961e2.png)
   
   *Tabla 5.1*
   
- Comprobación del Circuito de Thévenin.
   
   ![image](https://user-images.githubusercontent.com/75439689/108280040-8e5ede80-714b-11eb-932b-b148f47bf2ce.png)
   
   *Tabla 5.2*

   5.6. Porcentaje de Error las Tablas de Valores
   
   ![image](https://user-images.githubusercontent.com/75439689/108280912-da5e5300-714c-11eb-8f9e-0722b2523d0f.png)

6. CONCLUSIONES

   - Aplicar el Teorema de Thévenin resulta práctico al momento de analizar un circuito complejo con un número elevado de elementos, ya que este teorema permite obtener un circuito equivalente al original pero mucho más sencillo debido a que este sólo consta de la conexión en serie de la fuente de voltaje (VTH), la resistencia de Thévenin (RTH) y la resistencia o la carga la cuál se desea estudiar.
   - La precisión del Teorema de Thévenin es alta, ya que en el cálculo del error se obtuvo un porcentaje de 1.03% en las mediciones y un 0.01% en los cálculos (comparando entre los valores del circuito orginial y el circuito equivalente de Thévenin). Lo cual indica que emplear este Teorema resulta útil y práctico.
   - El concepto que maneja el Teorema de Thévenin (el de obtener un circuito equivalente al original pero con una mínima cantidad de elementos) se puede dar en la construcción de diversos aparatos o dispositivos electrónicos con el fin de abaratar costos en la producción de dichos aparatos ya que contendrían menos elementos.
 
 
7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
