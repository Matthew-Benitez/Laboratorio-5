# Laboratorio 5
1. OBJETIVOS
- Objetivo General:
   
   - Utilizar el teorema de Thévenin para utilizarlo prácticamente dentro de distintios circuitos eléctricos.
   
- Objetivos Específicos:
 
   - Determinar la resistencia equivalente dentro del circuito.
   - Determinar el voltaje que circula en una resistencia para obtener la fuente de voltaje de Thévenin.
   - Obtener el circuito simplificado de Thévenin y comprobar que la corriente y el voltaje que pasan por la resistencia son las mismas.
   
2. MARCO TEÓRICO

   


3. DIAGRAMAS
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

   5.1.Procedimiento
   
     - Ingresar a la plataforma Tinkercad y crear un nuevo circuito, en el cual se escogen los componentes listados anteriormente con los valores predispuestos (tanto de voltaje como de resistencia)
     - Conectar en serie la fuente de voltaje de 15 V, la resistencia de 1.2kohm y la resistencia RL (en ese orden específico).
     - A continuación se procede a medir el valor de corriente que pasa por RL con el multímetro, el cual debe estar conectado en serie entre las dos resistencias.
     - Posteriormente se mide el voltaje de RL con el multímetro conectado en paralelo a la resistencia RL.
     - Dar los valores de RL; y con cada valor, se da inicio a la simulación y se anotan los valores medidos de corriente y voltaje de RL uno por uno.

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

   - Mediante el análisis de los valores obtenidos tanto experimental como teóricamente, se concluye que la potencia máxima que una fuente puede suministrar a una carga, se da cuando la resistencia de carga es igual a la resistencia conectada en serie entre la fuente y la carga. Demostrándose así el Teorema de Transferencia de la Potencia Máxima.
   - Mientras el valor de la resistencia de carga se acerque más al valor de la otra resistencia, mayor será la potencia consumida de la carga. Por otro lado, mientras más se aleje el valor de la resistencia de carga al valor de la otra resistencia, el valor de dicha potencia disminuirá.
   - Comparando entre los valores obtenidos prácticamente y los calculados teóricamente, existe un error porcentual mínimo; lo cual demuestra que en la simulación se miden valores aproximados, mientras que en los cálculos se obtienen valores más certeros y reales.
 
7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
