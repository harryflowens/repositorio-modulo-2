# repositorio-modulo-2
en este repositorio, se va mostrar los comandos mas importantes para el manejo de la terminal y los mas usados con git
Comandos más importantes para el manejo de la terminal:
1
pwd: imprimir el directorio en donde nos encontramos. 
2
ls: imprime archivos o carpetas dentro del cual estamos trabajando. 
3
mkdir carpetaPrueba: crea una carpeta llamada 'carpetaPrueba' en el directorio que estamos situados. Si queremos crear una carpeta que lleve espacios en su nombre se debe utilizar comillas. Por ej "PrepCourse Henry" 
4
cd: para ir hacia el directorio que contiene la carpeta o directorio en donde nos encontramos. También podemos usarla para movernos entre carpetas, por ejemplo al usar cd carpetaPrueba cambiamos de la carpeta actual hacia "carpetaPrueba"
5
touch archivo.txt : crea un archivo con nombre "archivo.txt"
6
rm archivo.txt : elimina el archivo "archivo.txt"
7
rm -r carpetaPrueba: elimina la carpeta de nombre "carpetaPrueba"
 comandos más usados con git:
1
git init: comando para inicializar un repositorio local. 
2
git add: comando para que nuestro repositorio sepa de la existencia de un archivo o de sus últimos cambios, no almacena las actualizaciones de forma definitiva, únicamente las guarda en algo que conocemos como “Staging Area” (área de montaje o ensayo). Se puede armar como git add ArchivoEjemplo.js (solo agrega ese archivo) o git add (agrega todos los archivos modificados de la carpeta donde estas con el punto. 
3
git commit -m "mensaje": comando para almacenar definitivamente todos los cambios que por ahora viven en el staging área. En el mensaje ponemos el mensaje que explica los cambios commiteados. 
4
git push: comando para mandar nuestros commits a un servidor remoto.
5
git status: ofrece una descripción del estado de los archivos.
6
git pull: sirve para recibir cambios de repositorio remoto a local.
