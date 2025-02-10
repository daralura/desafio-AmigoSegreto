#  proyecto amigo secreto
# Descripcion 

una aplicación que permita a los usuarios ingresar nombres de amigos en una lista para luego realizar un sorteo aleatorio y determinar quién es el "amigo secreto"
## Instalación

1. Clona el repositorio:  
   `git clone https://github.com/daralura/desafio-AmigoSegreto.git

## Uso de la aplicacion 

1 . Para iniciar la aplicación, ejecuta:  

2. ingresa los nombres de los participantes

3. haz clic "sortearamigo" para selecioinar un nombre de la azar

Luego, abre tu navegador y visita  https://daralura.github.io/desafio-AmigoSegreto/


 
# Fucionalidades:

# Agregar nombres:
Los usuarios escribirán el nombre de un amigo en un campo de texto y lo agregarán a una lista visible al hacer clic en "Adicionar".

# Validar entrada:
Si el campo de texto está vacío, el programa mostrará una alerta pidiendo un nombre válido.

# Visualizar la lista:
Los nombres ingresados aparecerán en una lista debajo del campo de entrada.

# Sorteo aleatorio: 
Al hacer clic en el botón "Sortear Amigo", se seleccionará aleatoriamente un nombre de la lista y se mostrará en la página.

# contribuciones 


# array

Inicia declarando una variable de tipo array, que almacenará los nombres de los amigos ingresados. Ejemplo:

let amigos = []
Para saber mas sobre array puedes revisar la siguiente documentación:

Array - JavaScript | MDN


Implementa una función para agregar amigos
Desarrolla una función, que permita al usuario ingresar un nombre en el campo de texto y añadirlo a la lista de amigos creada anteriormente.

# Tareas específicas:
 

Capturar el valor del campo de entrada: Utilizar document.getElementById o document.querySelector para obtener el texto ingresado por el usuario.

Validar la entrada: Implementar una validación para asegurarse de que el campo no esté vacío. Si está vacío, mostrar un alert con un mensaje de error: "Por favor, inserte un nombre."

Actualizar el array de amigos: Si el valor es válido, añadirlo al arreglo que almacena los nombre de amigos usando el método.push().

Limpiar el campo de entrada: Después de añadir el nombre, restablecer el campo de texto a una cadena vacía.

Descripción
Crea una función que recorra el array amigos y agregue cada nombre como un elemento <li> dentro de una lista HTML. Usa innerHTML para limpiar la lista antes de agregar nuevos elementos.

# Tareas específicas:

Obtener el elemento de la lista: Utilizar document.getElementById() o document.querySelector() para seleccionar la lista donde se mostrarán los amigos.

Limpiar la lista existente: Establecer lista.innerHTML = "" para asegurarse de que no haya duplicados al actualizar.

Iterar sobre el arreglo: Usa un bucle for para recorrer el arreglo amigos y crear elementos de lista (<li>) para cada título.

Agregar elementos a la lista: Para cada amigo, crear un nuevo elemento de lista.

# tecnilogias usas

#  HTML5
es un estándar que sirve para definir la estructura, el diseño y el contenido de una página web


# CSS3
 es un lenguaje de diseño gráfico que se usa para crear la presentación visual de páginas web

 
#JavaScript
es un lenguaje de programación que los desarrolladores utilizan para hacer páginas web interactivas. 


# estructura del proyecto

# amigo -secreto   
carpeta
# index.html   
arcivo principal de la aplicacion
# styles.css
archivo de estilos 
# README.md    
documentacion del proyecto 

