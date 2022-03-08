# Construcci-n-de-un-timbre-el-ctrico-con-electroim-n.
Construcción de un timbre eléctrico con electroimán.


### 1. OBJETIVOS


##### 1.1. OBJETIVO GENERAL 

- Dieseñar y construir una calculadora en App inventor que permita calcular apmlificadores operacionales.

##### 1.2. OBJETIVOS ESPECÍFICOS

- Comprender la programacion por medio de bloques y las ventajas que tiene.
- Investigar y analizar el funcionamiento de los aplificadores operqacionales.


### 2. MARCO TEÓRICO


![Diagrama en blanco (12)](https://user-images.githubusercontent.com/93899658/156412004-0c3daa9b-7a8f-4286-ac99-998bfbbefcea.png)

![Diagrama en blanco (13)](https://user-images.githubusercontent.com/93899658/156416181-29ba60df-3e72-4c70-b040-fa6a183f16ba.png)

**BLOQUE DE CONTROL**
![image](https://user-images.githubusercontent.com/93899658/157124758-7ac1e173-cc59-467f-8387-6b225233eb82.png)
![image](https://user-images.githubusercontent.com/93899658/157124820-8af66a68-7997-410f-978c-b917b0a02fe8.png)

**BLOQUE DE LOGICA**
![image](https://user-images.githubusercontent.com/93899658/157124862-34ff665f-d24d-4642-a83c-4b1cbe0d0c3d.png)

**BLOQUE DE MATEMATICAS**
![image](https://user-images.githubusercontent.com/93899658/157124925-0feba971-511e-48bb-b707-13f37edd7f2b.png)



### 3. EXPLICACIÓN DEL PROCEDIMIENTO

##### 3.1. Materiales y equipo requerido

|Cantidad|Elemento|
|----|----|
|1|Tornillo de madera de 3 pulgadas|
|6 m|Alambre de cobre esmaltado calibre 21|
|25 cm |Alambre de combre calibre 12|
|1|Clavo|
|1|tornillo con rosca|
|1|Superficie de carton de 30 x 10 cm|
|1|Trasformador de 120 V ac a 9V dc|
|1|Pulsador|
|1|Clavija|
  

##### 3.2. Creacion de las ventanas para cada ampplificador operacional

![image](https://user-images.githubusercontent.com/93899658/157051689-1ededcbd-61df-4619-aee5-e4d74d649060.png)

      - Es recomendable poner un nombre a cada ventana para mantener un orden y evitar confusiones.


##### 3.3. Creacion del menu principal "Amplificadores Operacionales"

![image](https://user-images.githubusercontent.com/93899658/157053226-27700a42-5bb6-4806-bcb0-6437595e72cb.png)




#### 3.4. Creacion de la calculadora SUMADOR


![image](https://user-images.githubusercontent.com/93899658/157056383-10b6e305-ff15-4c75-9c7c-a612569d9efb.png)

      - Los elementos que componen la interface de CALCULADORA SUMADOR estan anidadas como se muestra en la lista de componentes.
      
 ##### 3.4.1. Algoritmo

      - Para la creacion del algoritmo SUMADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
      
![image](https://user-images.githubusercontent.com/93899658/157058037-f588ce4a-8e10-4895-8581-7d76b7ce854d.png)

![image](https://user-images.githubusercontent.com/93899658/157061046-416512a8-94d0-4f78-bbde-8a589109f5fe.png)

#### 3.5. Creacion de la calculadora RESTADOR


![image](https://user-images.githubusercontent.com/93899658/157061404-e84930d0-5622-45db-88b4-3975d0f418ce.png)

     - Los elementos que componen la interface de CALCULADORA RESTADOR estan anidadas como se muestra en la lista de componentes.


##### 3.5.1. Algoritmo

     - Para la creacion del algoritmo SUMADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo

![image](https://user-images.githubusercontent.com/93899658/157061921-7bd7ca9b-f176-4c10-8013-0ef2f9d5c138.png)

![image](https://user-images.githubusercontent.com/93899658/157062698-47e18d1b-c020-426a-a381-364d6fe2a932.png)



#### 3.6.  Creacion de la calculadora MULTIPLICADOR

![image](https://user-images.githubusercontent.com/93899658/157063512-d9b6d262-5e2e-46ca-a634-49d125f8f99f.png)

     - Los elementos que componen la interface de CALCULADORA MULTIPLICADOR estan anidadas como se muestra en la lista de componentes.

##### 3.6.1. Algoritmo


     - Para la creacion del algoritmo MULTIPLICADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
![image](https://user-images.githubusercontent.com/93899658/157064116-51adc2a4-1f00-49ab-80ff-1754c3450f84.png)

![image](https://user-images.githubusercontent.com/93899658/157064772-705537e0-f217-483e-995f-690d79ede8ee.png)


#### 3.7.  Creacion de la calculadora INTEGRADOR

![image](https://user-images.githubusercontent.com/93899658/157066855-100f7a3e-8e46-4074-bad9-71626da9f4f1.png)

     - Los elementos que componen la interface de CALCULADORA INTEGRADOR estan anidadas como se muestra en la lista de componentes.

##### 3.7.1. Algoritmo


     - Para la creacion del algoritmo INTEGRADOR se debe tener en cuenta la ecuacion algebraica que determina el voltaje de salida Vo
     
![image](https://user-images.githubusercontent.com/93899658/157067111-ac200936-a471-4eb0-b324-5506c74024cb.png)

![image](https://user-images.githubusercontent.com/93899658/157070631-633e75be-5496-46c9-a308-bc0ec42402b6.png)

     - Se debe tomar en encuenta la caracteristica de una integral y es que es es la sumatoria de rectangulos que tienen una altura f(x) y ancho infinitesimal dx, dando como resultado el area bajo la curva.
     - Los limites de la integral deben ser los adecuados.
 
![image](https://user-images.githubusercontent.com/93899658/157073528-6d40c0e9-16e3-42d4-8129-5bce5a854ad2.png)

- Teniendo encuenta las caracteristicas anteriores se procede a construir el alfgoritmo para calcular la integral de funcion seno.
![image](https://user-images.githubusercontent.com/93899658/157075454-010046da-3b98-427e-8ca9-d4d190265770.png)
- El ancho del diferencial **dx** puede ser el que sea, aunque debemos recordar que mientras más pequeño sea ese valor más exacto es el resultado.
     - Para comprender mejor este algoritmo, a continuación tenemos lo mismo pero en C++
     
      #include <iostream>
      #include <conio.h>
      #include <math.h>

      using namespace std;

      int main()

      {
      float i,a,n,dx,s;
      cout<<"ingresar primer extremo.: ";
      cin>> a;
      cout<<"ingresar 2do extremo.: ";
      cin>>n;
      dx=0.0005;
      s=0;


      for(i=a;i<=n;i=i+dx)
      { 
      s=s+sin(i+dx)*dx;
      }

      cout<<" la integral es: "<<s;
      getch();
      }

### 4. RESULTADOS

#### 4.1. SUMADOR

![image](https://user-images.githubusercontent.com/93899658/157082192-7c973a90-0c2d-489e-a78a-fe2258aee5a2.png)

#### 4.2. RESTADOR

![image](https://user-images.githubusercontent.com/93899658/157082578-d6ec99a4-2ede-4b9c-b692-584c752e2163.png)

#### 4.3. MULTIPLICADOR

![image](https://user-images.githubusercontent.com/93899658/157083008-687bda88-5427-48b0-8192-82bfae96dd36.png)

#### 4.5. INTEGRADOR

![image](https://user-images.githubusercontent.com/93899658/157085725-10c4088c-0eb4-4ae8-a06c-5fb9f6f3150a.png)

### 5. ENLACE DEL APK Y PROGRAMA FUENTE

[Calculadora Apk](https://drive.google.com/file/d/1U1Jb4b-Jm3HthGdCuqvqRe9tVXJFtQHy/view?usp=sharing)

[PROGRAMA FUENTE](https://drive.google.com/file/d/1xAOKLq6q7swq-6heF740E-zDeoXJFblz/view?usp=sharing)

### 5. VIDEO

https://youtu.be/WPXq6UZsv18


### 6. CONCLUSIONES 

- La programación por bloques resulta sencilla y fácil de entender debido a que la manera en la que se construye un algoritmo es visual y la estructura como tal no requiere de ciertas reglas como en otros lenguajes, por este y otros motivos la programación por bloques resulta ser una de las mejores alternativas para empezar a programar.
- La interface que contiene App Inventor es bastante amigable debido a que para construir alguna aplicación solo es necesario seleccionar las herramientas que se consideren necesarias   y ubicarlas donde sea más conveniente en el visor, sin embargo, tiene limitantes con respecto a la personalización dado que no siempre se llega al resultado deseado.
- Los amplificadores operaciones tienen una parte en común en su estructura algebraica y este es el signo negativo lo que da a entender que el voltaje de salida tiene un desface de 180 grados con respecto a la entrada, de igual manera indica que el voltaje de salida se encuentra retrasada. Por esta razón obtienen el nombre de inversor.
- De pendiendo de la configuración del circuito de cada amplificador operacional la expresión algebraica del  voltaje de salida será diferente, además que los amplificadores operacionales  para su análisis mediante Nodos cumplen con las condiciones de que sus voltajes de entradas son iguales además que las las corrientes por las entradas del amplificador es igual a cero.



### 7. BIBLIOGRAFIAS 
- ARACELI SOLEDAD CASILLAS, E. E. (s.f.). Obtenido de FUNDAMENTOS DE AMPLIFICADORES: http://files.electronica56.webnode.es/200000012-41de342da1/Amplificadores%20Operacionales.pdf
- Bolton, W. (agosto 2017). MECATRÓNICA. Ciudad de México: Alfaomega.
- SPARTANHACK, S.L. (7 de 3 de 2022). SPACETECHIES. Obtenido de ¿Qué es App Inventor y para: https://www.spacetechies.com/que-es-app-inventor-y-para-que-sirve/



