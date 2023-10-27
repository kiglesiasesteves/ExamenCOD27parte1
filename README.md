# ExamenContornosSegundoParte

Para utilizarlo en el examen.

## Ejercicio 1:

Abrimos la terminal y utilizando los comandos **ls** y **cd** entramos hasta la carpeta donde queremos realizar el clonado. 
Cuando entremos a esa carpeta realizamos el comando de clonado :

**git clone -o clonado https://github.com/damiancastelao/examenDAM.git**

Ahora que ya tenemos el clonado abrimos el Intellij y abrimos un nuevo proyecto con estas caracteristicas:

*New Project>Project from existing sources>Seleccionamos nuestra carpeta>Create Project from exisitng sources>Next>(Abrimos el proyecto)*

Tras este procedimiento ya tendremos el archivo abierto en nuestro IDE. 

## Ejercicio 2:

Vamos a nuestra cuenta de github y creamos un nuevo repositorio donde subiremos este readme.
Abrimos la terminal del intellij y realizamos los pasos para subir este md. Si realizamos un git remote -v podemos ver que nos aparece con el nombre clonado el repositorio del cual hicimos el clonado.

- **git init**

- **git add README.md**

- **git commit -m "ejercicio2"**

- **git branch -M main**

- **git remote add origin https://github.com/kiglesiasesteves/ExamenCOD27parte1.git**

- **git push -u origin main**

Ahora si hacemos el **git remote -v** tras añadir el repositorio remoto de origen tenemos 4 https, dos de las cuales hicimos el clonado y nuestro propio repositorio que añadimos como remoto.

## Ejercicio 3:

Copiamos y pegamos un programa ya realizado en este programa. 
Para subirlo haremos un 
- **git add libro.java boletin04.java**
- **git commit -m "Ejercicio3"**
- **git push -u origin main**

