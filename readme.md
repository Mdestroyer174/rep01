# pasos para crear repositorio en local

**paso 1:** crear el repositorio  
| 🦖 **git init repo01**                      | 
|-----------------------------------------|


![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/1.png "paso 1")

**paso 2 :** comprobar que el repositorio esta creado y inicializado  
| 🦖 **git status**                           |
|-----------------------------------------|

![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/2.png "paso 2")  

**paso 3 :** subir el archivo readme.md y dejarlo listo en el repositorio 
| 🦖 **git add readme.md**          |
|:-------------------------------|
| 🦖 **git commit -m "primer commit"**|

![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/3.png "paso 3")  

**paso 4 :** comprobar en que estado esta el archivo *al modificar el readme sale como modificado.*     
| 🦖 **git add readme.md**         |
|:-------------------------------|
| 🦖 **git commit -m "segundo commit"**|
|:-------------------------------|
| 🦖 **git log**                     |

![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/4.png "paso 4")  

**paso 5 :** comprobar si estamos conectados al repositorio remoto  
| 🦖 **git remote -v**                    |
|-----------------------------------------|

![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/5.png "paso 5") 

**paso 6 :** ahora toca asociar el repositorio local con el remoto en github y subir lo que tenemos en espera al repositorio remoto ***en mi caso es con mi direccion***  
| 🦖 **git remote add origin https://github.com/Mdestroyer174/rep01.git**         |
|:-------------------------------|
| 🦖 **git branch -m main**     |
|:-------------------------------|
| 🦖 **git push -u origin main**    | 

![Este contenido se mostrará cuando la imagen no se pueda cargar, como texto alternativo](/imagenes/6.png "paso 6") 