# Ocultismo
//Ocultismo - Herramienta de esteganografia

La esteganografía es la práctica de ocultar un mensaje secreto dentro (o incluso encima) de algo que no es secreto, Ocultismo permite la ocultación de texto protegido con contraseña dentro de una imagen.


INSTALACIÓN:

apt update && apt upgrade -y

pkg install git -y 

git clone https://github.com/Sfemz/Ocultismo

ls

cd Ocultismo

chmod 777 ocultismo

./ocultismo

COMO USAR:

Cuando ejecutes la herramienta te saldrá un aviso preguntandote que si ya tienes instaladas todas las herramientas para ejecutarlo correctamente, la primera vez le daremos en letra "y" que significa "yes" y se nos empezará a descargar todo lo necesario (esto solo lo haremos la primera vez que hayamos instalado la herramienta)

Cuando te pida permisos de almacenamiento dale en "Aceptar" para continuar.

Luego nos saldrá 2 opciones:
1 Ocultar texto en imagen
2 Ver texto oculto

Para poner una imagen personalizada tenemos que hacer lo siguiente:

1. Escoger la imagen que nosotros queramos y guardarla en nuestro dispositivo.
2. Cambiar el nombre (que sea uno sencillo para más facilidad)
3. Meternos a Termux y mover la imagen dentro del repositorio 

EJEMPLO:  
cd storage
cd downloads
cp NOMBREDELAIMAGEN.jpg Ocultismo

4. volver a la herramienta y hacer los pasos
5. Cuando te ponga "Elige la imagen personalizada" Solo deben de poner el nombre de la imagen con su extensión (NOMBREDELAIMAGEN.jpg)
6. Luego debes de poner la contraseña y posteriormente te pedirá que confirmes la contraseña volviendola a escribir

Si todo sale bien saldrá un mensaje diciendo "Texto ocutado exitosamente!!"
Ahora podrás compartir la foto con más personas.
