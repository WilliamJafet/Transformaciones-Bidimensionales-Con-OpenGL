# Transformaciones Bidimensionales Con OpenGL

La práctica consiste en realizar un programa que muestre una figura con las transformaciones bidimensionales como son: traslación, rotación y escalamiento.
Para ello primero se explica el código fuente del programa realizado.
En principio se realiza la importación de librerías necesarias para realizar la práctica.

![image](https://user-images.githubusercontent.com/72232712/145736614-2cdffac8-1670-4c91-9e65-f37cbbccb778.png)

El siguiente bloque de código es la declaración de variables necesarias para realizar distintas acciones.

![image](https://user-images.githubusercontent.com/72232712/145736631-9c146906-82a1-4678-a4e5-2c5b80896909.png)

La función principal es importante debido a que es en esta parte donde empieza a ejecutarse el programa. En este bloque se realizan diversas configuraciones de la ventana para que se muestre al usuario.

![image](https://user-images.githubusercontent.com/72232712/145736639-6f8c3372-1695-45e9-8f2a-e494acbc751f.png)

La función init es parte de la librería OpenGL y se utiliza para inicializar los componentes del Canvas, este es un componente en el que se va a realizar el pintado del objeto.

![image](https://user-images.githubusercontent.com/72232712/145736644-e9d0a5b1-5d1c-49a0-97aa-767d841ec5ba.png)

En la función reshape no se realiza ninguna acción por ahora.

![image](https://user-images.githubusercontent.com/72232712/145736658-dbc789d6-cafe-419f-bd23-710fac8cf89e.png)

La función display es una de las funciones más importantes porque es aquí donde se programan las instrucciones para que el programa pinte lo que le estamos indicando.
En este caso primero asignamos un color al triángulo que vamos a pintar en la ventana, posteriormente indicamos al programa que se va a realizar un pintado de un triángulo, dentro de este bloque se indican los diferentes vértices del triángulo.
Las líneas que están comentadas, indican las diferentes transformaciones. Conforme se va ejecutando el programa se van ejecutando cada una de estas líneas para que se puedan ver los diferentes cambios.

![image](https://user-images.githubusercontent.com/72232712/145736666-c99cbd08-9738-4575-bfdb-34acae7e90a1.png)

La última función por el momento no se realiza ninguna acción.

![image](https://user-images.githubusercontent.com/72232712/145736672-dbd7eb17-3b8c-4209-88ac-53402ece391c.png)

Ahora que se ha explicado el código fuente, la siguiente parte es mostrar el resultado.
Como resultado hemos obtenido lo que se muestra en la siguiente figura. Dicha figura muestra el triángulo original.

![image](https://user-images.githubusercontent.com/72232712/145736688-627887da-d0c9-43fb-a3d7-fbf90477fed2.png)

Ahora si aplicamos 	una traslación en x y y, se aprecia lo siguiente;

![image](https://user-images.githubusercontent.com/72232712/145736696-1cf0256e-c178-40b3-8d5f-a74de0062fd6.png)

Al triángulo original le aplicamos un escalamiento de 0.5 en x y también en y. Como resultado se muestra lo siguiente;

![image](https://user-images.githubusercontent.com/72232712/145736706-c041a3d0-5b0e-41e0-8daa-bcdb97907c5e.png)

Al triángulo original le aplicamos una rotación de 30 grados y como resultado se ve lo siguiente;

![image](https://user-images.githubusercontent.com/72232712/145736719-270fb6c9-7439-43a0-b5c4-d3d07fb85613.png)
