# Estudio
todo tipo de codigos

Author: Aldo Geanbruno Risso Morales

git clone clonar todo el repositorio en mi pc para trabnajar de manera local
git fetch una vez clonado descarga la info
git pull origin main me movia a mi ultimo commit
git commit -am "mensaje>" guardar la info en manera local
git push origin main todos los xcommit los empuja al servidor

git branch NombreDelBranch
git checkout "NombreDelBranch"
git push origin NombreDelBranch

*********************
----------- 

Para devolverme al main y crear un nuevo branch

git checkout main
git checkout -B NombreBranch ---> este comando te crea el branch y te mueve al tiro a la posicion del branch

documentacion de segundoBranch 

------------

cuando se crean conflictos, se solucionan en vcode y se ingresa el comando
git commit -am "se resolvio el conflicto"
y despues de eso ya se puede empujar los cambios

Retroceder al ultimo commit ingresado, en el caso que no funcione o no quiera lo que estaba haciendo o el codigo dejo de funcionar
git reset --hard

si se quiere cambiar un solo arcvhivo
git checkout HEAD --nombre del archivo

git log --->historial de cosas que se han echo commits
git log --oneline
git log --oneline --graph

si me quiero mover a un commit en particular, ingreso git log --onleine copio el codigo del commit al que quuiero ir y escvribo
git checkout CodigoGitLog

en este caso se copia lo que se andaba buscando y se vuelve al main para agregar lo que se fue a buscar
git checkout main

para regresar un commit atras
git reset --hard HEAD~1 o git checkout --hard HEAD~1
git pull origin main

cuando ya tengo el codigo y lo quiero subir a produccion release (liberar el codigo)
hay que ir al github e ingresar al apartado release
create new release -> este release de que branch lo vas a sacar (main version final)
en nombre se pone la version del release

en github tb se pueden crear issue para notificar al equipo algun error o comentario que hay que revisar

issue -> new issue cuando se toma la decicion delq ue el issue es un issue se crea un new branch para trabajar en el 
git checkout -B NombredelIssue 

se arregla el issue y se guardan los cambios



