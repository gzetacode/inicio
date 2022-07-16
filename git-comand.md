<!-- texto en italica-->

*txt*

<!-- texto en negrita-->

**txt**

<!-- texto en tachado-->

~~txt~~

<!-- listas desordenadas-->
## listas desordenadas

* manzana
* naranja
* pera

<!-- listas desordenadas ccon subitems-->
## listas desordenadas con subitems
* manzana
    * m2
* naranja
    * n2
* pera
    * p2

<!-- listas ordenadas-->
## listas ordenadas
1. *manzana*
2. *naranja*
3. *pera*




### --vamos a la carpeta del ***proyecto***
git init

git status -s
--muestra los archivos y directorios que esta controlando
--si tiene ?? en rojo significa que git no esta haciendo seguimiento

git add git-comand.txt
--ahora aparece una A por que se agrego 

git commit -m "primer paso"
--si es la primera vez me va pedir primero:
git config --global user.name "gzeta"
git config --global user.email "gazetaimpresiones@gmail.com"
--y luego si:
git commit -m "primer paso"

--despues de modificar el archivo y cuando querramos hacer instantanea:
git add git-comand.txt
git commit -m "segundo paso"

--listado de las copias y descripcion
git log --oneline

--para restaura archivo a otra instantanea
git reset --hard d93d741

--para agregar todos los archivos de la carpeta:
git add .

--si quiero agregar y hacer commit a la vez:
git commit -am "tercer paso"

--si queremos modificar un comentario (habrimos editor VIM)
git commit --amend

--para subir a github
git push -u origin master
