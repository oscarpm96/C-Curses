
# :zap: Resumen 
- Entonces, en esta sección, aprendió los conceptos básicos de C #. C # frente a .NET C # es un 
lenguaje de programación, mientras que **.NET es un marco de trabajo**. Consiste en un entorno de tiempo de ejecución 
(CLR) y una biblioteca de clases que usamos para crear aplicaciones. CLR Cuando compila una aplicación, 
el compilador de C # compila su código en código **IL (lenguaje intermedio)**. 
- El código **IL es independiente de la plataforma**, lo que hace posible tomar un programa C # en una computadora 
diferente con diferente arquitectura de hardware y sistema operativo y ejecutarlo. Para que esto suceda, 
necesitamos CLR. Cuando ejecuta una aplicación C#, **CLR compila el código IL en el código de máquina nativo** 
de la computadora en la que se está ejecutando. **Este proceso se denomina compilación justo a tiempo (JIT)**. 

- Arquitectura de aplicaciones .NET En términos de arquitectura, una aplicación escrita con C # consta de bloques de 
construcción llamados clases. **Una clase es un contenedor de datos (atributos) y métodos (funciones)**. Los atributos 
representan el estado de la aplicación. Los métodos incluyen código. Tienen lógica. Ahí es donde implementamos 
nuestros algoritmos y escribimos código. Un espacio de nombres es un contenedor de clases relacionadas. 
Entonces, a medida que su aplicación crece en tamaño, es posible que desee agrupar las clases relacionadas en 
varios espacios de nombres para una mejor capacidad de mantenimiento. A medida que el número de clases y 
espacios de nombres crece aún más, es posible que desee separar físicamente los espacios de nombres relacionados 
en ensamblajes separados. **Un ensamblado es un archivo (DLL o EXE) que contiene uno o más espacios de nombres y clases.**

- **Un archivo EXE representa un programa que se puede ejecutar**. Una **DLL es un archivo que incluye código que se puede 
reutilizar en diferentes programas**.