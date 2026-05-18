[README.md](https://github.com/user-attachments/files/27939104/README.md)
#### **READ ME**

* ###### **DESCRIPCIÓN DEL PROYECTO:**

&#x09;Este trabajo consta de un analizador léxico y sintáctico desarrollado con ANTLR y JavaScript, capaz de procesar un archivo de entrada input.txt con código fuente perteneciente a un sublenguaje definido mediante una gramática propia. El sistema realiza distintas etapas de análisis e interpretación sobre la entrada proporcionada.

* ***ANÁLISIS LÉXICO:*** Recibe el código fuente y lo procesa carácter por carácter para identificar los distintos lexemas del lenguaje. Cada lexema reconocido es clasificado según el token correspondiente definido en la gramática. Acá, se detectan posibles errores léxicos y se informa la línea en la que ocurren, junto con la causa del problema.
* ***ANÁLISIS SINTÁCTICO:*** Verifica que se respeten las reglas sintácticas establecidas en la gramática definida para el lenguaje. Si la entrada es válida, el sistema confirma que el análisis fue exitoso y continúa con la construcción del árbol sintáctico. En caso contrario, informa los errores encontrados.
* ***TABLA DE LEXEMAS Y TOKENS:*** Genera una tabla con todos los lexemas reconocidos y sus respectivos tokens.
* ***ÁRBOL SINTÁCTICO:*** Construye el árbol de análisis sintáctico concreto correspondiente al programa ingresado, el cual puede visualizarse en formato textual jerárquico, permitiendo comprender la estructura interna del código y cómo el parser interpreta cada instrucción según la gramática.



* ###### **INSTALACIÓN DEL PROYECTO:**

&#x09;Para instalar el proyecto se debe clonar el siguiente repositorio: git clone https://github.com/morellinacho0-lab/52054.git

&#x09;Una vez clonado, desde la terminal hay que ejecutar el siguiente comando: cd 52054

&#x09;Una vez dentro, debemos extraer el archivo zip: powershell -command "Expand-Archive -Path 'tablero-analizador.zip' -DestinationPath 'tablero-analizador'"

&#x09;Se prosigue colocando: cd tablero-analizador
	Una vez dentro, se deben instalar las dependencias necesarias con el comando: npm install

&#x09;Finalmente, se procede a ejecutar el programa con comando: node index.js



* ###### **INSTRUCCIONES DE USO**

&#x09;El analizador utiliza como entrada el archivo input.txt. Para ejecutarlo, vamos a la terminal desde la carpeta del proyecto y colocamos el comando: node index.js

&#x09;Una vez ejecutado, el analizador realiza las siguientes tareas:

1. Análisis léxico y sintáctico sobre el código fuente e informa si la entrada es correcta o contiene errores.
2. Tabla de lexemas y tokens reconocidos durante el análisis léxico.
3. Árbol de análisis sintáctico
4. Resultado de la ejecución del programa.



&#x09;Para probar distintos casos de entrada, se puede editar el archivo input.txt, guardar los cambios y volver a ejecutar el programa.

&#x09;Para poder abrir el proyecto en Visual Studio Code, se escribe el siguiente comando en la terminal: code .

