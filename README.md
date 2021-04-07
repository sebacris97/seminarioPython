# seminarioPython
Sopa de letras es un software educativo cuyo propósito es estimular la dialéctica de estudiantes de nivel primario de entre 6 y 12 años. 

Se basa en un Configurador, que será utilizado por el docente, donde se agregarán una a una las palabras a buscar. 
Las palabras serán validadas a traves del buscador de palabras, quién recibe la palabra y utilizando el módulo externo pattern.web y pattern.es.

A su vez se cuenta con un JSON generado por el modulo temperatura.py, que utilizando un sensor te humedad y temperatura conectado a una Raspberry Pi 3b+. Este JSON es utilizado por la sopa de letras que tomará el color del promedio de las temperaturas captadas.

La sopa de letra se basa en una matriz de letras aleatorias, con las palabras ingresadas "escondidas". El usuario deberá seleccionar el tipo de palabra que desea validar (por defecto sustantivo), y seleccionar, a través del puntero, la primera letra, seguido por la ultima. De esta manera se validará que la palabra sea una de las palabras ingresadas por el docente, y si el tipo de la palabra es correcto. Si el usuario selecciona correctamente una palabra, la misma se pintará del color de su tipo (seleccionado por el docente en el configurador). Cuando el usuario seleccione todas las palabras ingresadas previamente por el docente, será informado a través de un PopUp, felicitandolo. La ventana de la sopa no se cerrará hasta que se seleccione la opción "SALIR", esto es para que el alumno le pueda mostrar al docente su hazaña.
