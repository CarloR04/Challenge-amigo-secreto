
<h1 align="center"> CHALLENGE AMIGO SECRETO </h1>
<img width="500" height="500" alt="DATA ANALIST" src="https://github.com/user-attachments/assets/350760b1-c77f-43b1-83fc-2db8782f9bca" />
<p align="left">
<img src="https://img.shields.io/badge/STATUS-EN DESARROLLO-green">
</p>
 Realizar el reto del sorteo amigo secreto en Alura Latam
<h2 align="center">
:construction: Proyecto en construcción :construction:
</h2>

Este proyecto busca poner a prueba los conocimientos adquirdos sobre el manejo de arrays, condicionales, variables, manejo de html  y Js en los dos primeros cursos del programa Oracle next educatiòn G9 en Alura Latam. 

<h3 align="center">
🚀 Comenzando 🚀
</h3>

Para poder visualizar y correr el proyecto, primero debes descargar en tu ordenador los 3 documentos que continene la información .JS .HTMLL y .CCS. Junto a la carpeta de imagenes. Con esto, estas preparando el espacio inical de trabajo. 

<img width="908" height="258" alt="image" src="https://github.com/user-attachments/assets/45ddcd5f-d1fb-48c9-9d80-1fca125a62b8" />

<h4 align="center">
📋 Pre-requisitos 📋
</h4>

Para poder entender lo que contiene el codigo JS y como este se comporta segun el HTML y el CCS en el DOM, necesitas tener conocimiento previos en lenguaje de programación. 

Te recomiendo estos dos cursos en Alura Latam, son muy detallados para iniciar y trabajar la logica de programación necesaria para la construcción de este reto. 

Curso 1: Lógica de programación: sumérgete en la programación con JavaScript
<img width="720" height="77" alt="image" src="https://github.com/user-attachments/assets/b7f58722-d51e-487f-88e8-9e123f208f3a" />

Curso 2: Lógica de programación: explorar funciones y listas
<img width="731" height="74" alt="image" src="https://github.com/user-attachments/assets/84d88b37-dcde-4b49-ac4b-c0ca5cbeb2b3" />

<h5 align="center">
🔧 Instalación 🔧
</h5>

Para visualizar el codigo y editarlo, pueden usar el programa de su preferencia, este proyecto se trabajo bajo la  aplicación Visual Studio Code. 

Para conocer como instalarlo correctamente en tu ordenador, te recomiendo este paso a paso realizado por Alura Latam, es muy preciso y claro: 

1. Accede a la página oficial.

2. Haz clic en la opción Windows (o elige según tu sistema operativo, hay opciones para Mac y Linux).

3. La descarga comenzará automáticamente.

4. Cuando termine, localiza el archivo con un nombre parecido a VSCodeUserSetup-x64-1.99.3.exe.

5. Haz doble clic en el archivo y sigue las instrucciones del instalador haciendo clic en "Next" hasta completar. Después de la instalación, abre el programa buscando "Visual Studio Code" en la barra de búsqueda.

<img width="765" height="238" alt="image" src="https://github.com/user-attachments/assets/bbd6039d-fa01-4906-8e2f-2061a8ed91f0" />

<h6 align="center"> 
 ## :hammer: Funcionalidades del proyecto
</h6>

- `Funcionalidad 1`: Crear Array para que se almacenen los nombres
- `Funcionalidad 2`: Función para agregar nombres a sortear
- `Funcionalidad 3`: Función para actualizar la lista de nombres a sortear
- `Funcionalidad 4`: Función para sortear los nombres


<h7 align="center"> 
⚙️ Ejecutando las pruebas ⚙️
</h7>

Para poder visualizar el funcionamiento del codigo, primero debes abrir el archivo .html en el navegador, como se muestra en la imagen. 

<img width="739" height="292" alt="image" src="https://github.com/user-attachments/assets/e4aa24c9-0b40-488a-91e9-94de1c6ce7c6" />


Luego, debes dejar abierta la vista de la consola del desarrollador para validar las salidas que nos debe dar el codigo. 
Debes dar clic derecho en la esquina superior, buscar herramientas de desrroollar y al dar clic, se te abribar la ventana señalada en rojo ques es la consola. 

<img width="1370" height="768" alt="image" src="https://github.com/user-attachments/assets/b8437efc-ce90-4e3a-a19b-280d088f344e" />

- Funcionalidad 1: Se crea la lista, donde se van a agregar más adelante los nombres que ingrese el usurio. Hasta el momento esta lista no esta definida y esta vacia. 

<img width="433" height="49" alt="image" src="https://github.com/user-attachments/assets/424b4bc0-ae63-41ac-8a69-fe7e84095096" />

- Funcionalodad 2:
  
<img width="679" height="519" alt="image" src="https://github.com/user-attachments/assets/a0ce76df-564d-4cb6-be9a-89925e3aae50" />

   - Como primer paso, le asignamos nombre a función, recuerda que para activarla esta debe ser llamada al final, para nuestro caso la llamos en el return al final luego de la condición if-else.
     
     <img width="296" height="19" alt="image" src="https://github.com/user-attachments/assets/678d6e2a-21da-454f-9f1d-fa5fc96648eb" />
     <img width="229" height="34" alt="image" src="https://github.com/user-attachments/assets/8e2afe22-e672-491c-b55f-51080422c9cd" />

   - Como segun paso, asignamos una variable para que capture el elemento dentro del html, que hace referencia a la caja de texto donde se ingresan los nombres por el usurio. Recuerda que si dentro del html no existe un id, debes crearlo para realizar la conexión.
     
     <img width="563" height="22" alt="image" src="https://github.com/user-attachments/assets/9b829814-c3ad-44ac-8f89-13393ff09021" />

   - Para limitar a que solo se permitan texto, en JS usamos la "Expresión Regular" asignadosela a una variable para luego usarla en nuestro condicional.
     
     <img width="551" height="47" alt="image" src="https://github.com/user-attachments/assets/6cd8a583-3d46-4566-a158-9a33bc8903e2" />

   - Como siguiente paso, realizamos un condicional if-else para definir que si se cumple con la limitante de la expresión regular se permita anexar el nombre de la lista, de lo contrario que lance una aleta que no es permitido.
     
     <img width="591" height="271" alt="image" src="https://github.com/user-attachments/assets/5c7285d6-9190-4b76-be8a-2c9836864ffb" />
     
   - Para validar que la condición se ejecuta como es debido, el codigo contiene unos console.log que les permitira ver en la consola el imput que ingresa el usurio. Quitarle la etiqueta de texto para que puedan ser leido como codigo.
     
     <img width="564" height="105" alt="image" src="https://github.com/user-attachments/assets/3829d363-3742-40dc-9616-623fc30a976d" />
     

- Funcionalodad 3:

  <img width="682" height="370" alt="image" src="https://github.com/user-attachments/assets/2bb5eb59-14a3-49a8-b833-d729ec87884d" />

  - Como primer paso, antes de crear la función que actualice el nombre agregado por el usuario, primero creamos una función que nos ayuda a limpiar la caja de texto cada vez que se ingresa un nombre.

    <img width="462" height="77" alt="image" src="https://github.com/user-attachments/assets/e1a04dde-4461-4e9c-a1d3-b9488886628c" />

  - Luego, procedemos a crear la función que actualiza los nombres que agrega el usurio, primero limpiamos la lista dentro del HTML donde se guardan los nombres.

    <img width="445" height="98" alt="image" src="https://github.com/user-attachments/assets/4b3de060-603b-4c05-9be2-c917b73784c2" />

  - Con un bucle For, definimos que que se cree un elemento Li que se muestre en la pantalla del navegador para cada nombre que se ingresado por el usurio.

    <img width="652" height="153" alt="image" src="https://github.com/user-attachments/assets/38673928-b54a-4c45-ac71-470446d55d78" />

  - Por ultimo, para que lo anterior se ejecute lo tenemos que llamar dentro de la función anterior para que se ejecuten siempre y cuando los nombres sean aceptados segun la condición limitante de texto.

    <img width="630" height="96" alt="image" src="https://github.com/user-attachments/assets/e0e83bfe-b4b6-42b6-8191-33104e2ce643" />


 - Funcionalidad 4:

   
   
    














<h8 align="center">
✒️ Mentores ✒️
</h8>

Con mucho agradecimiento por el conocimiento impartido a los tutores de Alura Latam: 

- Christian Velasco https://github.com/christianpva
- Leonardo Jose Castillo Lacruz https://github.com/ljcl79


## Autor
| [<img src="https://avatars.githubusercontent.com/u/225071618?v=4&size=64" width=115><br><sub>Carlo Robles</sub>](https://github.com/CarloR04) |  
| :---: |

📢 con ❤️ 
