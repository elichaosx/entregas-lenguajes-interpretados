# Examen Primer Parcial

#### 1. ¿Qué es y para qué sirve Visual Studio Code? 
Es un editor de código para programadores que nos sirve principalmente para escribir y editar códigos.

#### 2. ¿Qué es y para qué sirve la Terminal de Comandos?
Es un programa o interfaz que nos ayuda a poder interctuar con la computadora usando solo texto en lugar de usar botones o íconos

#### 3. ¿Qué es y para qué sirve Markdown? 
Markdown es un tipo de marcado que nos sirve para poder esccribir y leer un texto de forma más rapida y sin tener que usar otros programas que puedan ser más complejos

#### 4. ¿Qué es y para qué sirve Git? 
Git es un software que nos permite a nosotros como desarrolladores poder trabajar en un mismo codigo junto más personas

#### 5. ¿Qué es y para qué sirve GitHub?
Es una plataforma que nos sirve para poder guardar y compartir proyectos y donde igualmente podemos trabajar en conjunto con más personas que tengan acceso a nuestro proyecto

#### 6. ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm? 
```bash
pwd -nos ayuda a saber en que carpeta estamos
whoami -muestra el nombre del usuario activo en ese momento
touch -con el creamos una carpeta nueva
mkdir -crea otra carpeta
cp -nos deja copiar archivos
mv -con el movemos tanto archivos como carpetas
ls -nos lista todos los archivos de nuestra carperta actual
clear -limpia la terminal
cd -cambiamos de carpeta
rm -elimina un archivo
```
#### 7. ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~?
```bash
./ -Esto nos muestra la carpeta en la que nos encontramos
../ -Esto nos lleva a la carpeta anterior
/ -Representa la carpeta raíz
~ -Representa la carpeta "home"
```
#### 8. ¿Cómo se inicializa un repositorio en Git?
Dentro de nuestra carpeta debemos ejecutar la terminal y ejecutar el comando:
### git init

#### 9. ¿Cómo creas un repositorio en GitHub?
Entrando a nuestro GitHub, seleccionamos el "New Repository", posteriormente solo debemos rellenar los datos que nos pide, cómo el nombre de nuestro repositorio, una descripción, etc.
Tambien tenemos opciones extra que podemos elegir, como iniciar el README o añadir el ".gitignore"

#### 10. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub? 
Para poder vincularlos ocupamos el enlace de nuestro repositorio de GitHub y ejecutar lo siguiente
### git remote add origin (y aquí añadimos el enlace)

#### 11. ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos.
```bash
git add archivo - Con esto agregamos los cambios de un archivo
git add . -Para agregar los cambios realizados a todos los archivos

git commit -m "Mensaje de descripción del cambio"  -Al hacer los cambios debemos escribir el mensaje del cambio que hicimos

git remote add origin https://github.com/usuario/repositorio.git -Aquí debemos agregar el origen remoto de nuestro repositorio

git push -u origin master -Se debe usar la primera vez que vinculemos el repositorio remoto con el local

git push -Esto será ára las actualizaciones que hagamos posteriormente

git pull -Para descargar los cambios de nuestro repositorio remoto al local
```
#### 12. ¿Para qué sirve el archivo .gitignore?
Nos sirve para poder indicar los archivos o carpetas que no queremos incluir/mostrar en nuestro repositorio

#### 13. ¿Cuál es el propósito de una rama? 
Una rama es como otra línea de nuestro proyecto que nops deja hacer cambios o trabajar sin necesidad de modificar nuestra rama principal (main)

#### 14. ¿Qué es una fusión? 
Es con lo que podemos unir una rama con otra

#### 15. Explica los diferentes tipos de fusión que existen.
Principalmente existen dos tipos de fusiones
- Fast-Forward: Aquí la fusión es de forma automática
- Manual Merge: La fusión aquí se debe hacer manual y resolver conflictos en caso de haber 

#### 16. ¿Cómo puedes ver el historial de tu repositorio?
Utilizando el comando: git log

#### 17. ¿Cuál es el propósito de una etiqueta?
El proposito es el poder clasificar u organizar el trabajo de nuestro repositorio