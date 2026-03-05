## 🎈comandos para clonar proyectos 🎈 ###

debes abrirl el entono cmd de git y opiar open git bash
´´´´
git clone https://github.com/LillianaU/tallerAlertasJs.git

´´´´

### ✨ abrir mi  usuario en este pc 🎞 ###

´´´´
git config --global user.name "miusuario"
git config --global user.email "micorreo@gmail.com"


´´´´
### 🦺comprobar ###
git config --list
### 🥽iniciarlizar git  para poder subir cambios del proyecto ##

´´´´
git init
´´´
### 🔍comando para verificar rama ###
git branch
## paso a paso para subir mi respositorio ##
# paso 1
git remote add origin https://github.com/LillianaU/expresiones_regulares.git
# paso 2 establecer  rama
git branch -M main
# subir archivos
´´´´
git add .

´´´´
el . significa todo lo que esta en la carpeta

### ejemplo si solo desea subir algo en espesifico##
´´´´
git add Nombrearchivo.extencion
´´´´
ejem´
´´´´
git add menu.html
´´´´
# crear commin son obligatorios
git commit -m " estamos subiendo en index al repositorio donde esta la documentacion de js para las expresiones regulares, esta parte es la plantilla sin funciones"

# ultimo paso  dar la accion de que lo suba
´´´´
git push -u origin main

´´´´
# 👔como hago las actualizaciones # 
 verificar del estado  
 ´´´´
 git status

 ´´´´
 luego  adicionar cambios
 ´´´´
 pasopasogit.md
 ´´´´
## por utimo crear el commit
 ´´´´
 git commit -m " complemente el  tutorial de git"
 ´´´´
## ahora suba
´´´´
git push -u origin main
´´´´
