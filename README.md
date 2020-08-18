# Proyecto base para los desarrollar los laboratorios

*	ADT: archivos Python con la definición de los Tipos Abstractos de Datos.
*	App: aplicación Python cliente que usa las ADTs y ordenamientos para dar solución a laboratorios y retos.
*	Data: archivos con los datos (csv, json, txt, etc) usados en el laboratorio o reto. El contenido de esta carpeta NO se debe versionar.
*	DataStructures: archivos Python con las estructuras de datos básicas (listas enlazadas y arreglos).
*	Sorting: archivos Python que implementan los algoritmos de ordenamiento.
*	Test: pruebas unitarias en Python para validar el código desarrollado.

Lab No 1:
Diego Andres Parraga Gonzales - d.parraga@uniandes.edu.co-202015540
Miguel Angel Cardenas Cardenas - ma.cardenasc1@uniandes.edu.co -202010998
Dylan Camilo Patiño Aguilar - d.patino@unaindes.edu.co – 202010
−	¿Cuál es el ciclo regular para actualizar código en un repositorio GIT?
Posterior a haber hecho el cambio en el codigo, o alguna modificacion se debe primero guardar esta en el equipo con git commmit, para luego actualizar el repositorio en linea con git push.

−	¿Qué ventajas y limitantes tiene el uso de Ramas/Branches?
Nos permite modificar el codigo o los archivos de un repositorio sin modificar las funciones de la rama master y asi evitar posibles errores, nos permite trabajar de forma remota en el desarrollo de codigo con otras personas, al igual que el ver sus diferentres cambios en el repositorio.

−	¿Cuáles serían las buenas prácticas para solucionar conflictos?
1.	Observar el problema de una forma abstracta
2.	Pensar en una solución funcional sin enfocarnos en una estructura especifica
3.	Pensar en la complejidad del proceso
4.	Elegir una estructura que represente la menor cantidad de cambios al codigo
−	¿Qué orden de complejidad tendría las funciones (consulta y lectura de archivo)?
O(N) pues debe recorrer todo los datos.

−	¿Cómo podría reducir o aumentar la complejidad de la consulta?
El uso de un TAD de lista si solo se requiere de guardar los datos al final de la misma,o si se tiene un arreglo ordenado que sea buscado por posicion. Sin embargo si es encadenado, este es mejor para guardar datos en posiciones internas y podria ayudar en casos donde se necesite el uso de llaves. 

−	¿Cómo afecta un TAD en la complejidad?, ¿Qué alternativas existen?

Es una forma de abstraer datos y diseñar software a partir de estos y así facilitar el         mantenimiento, funcionamiento y entendimiento, por tanto, un TAD nos ayuda a encontrar la menor complejidad para el desarrollo de un codigo. 
