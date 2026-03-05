## comandos para clonar proyectos ###

debes abrirl el entono cmd de git y opiar open git bash
´´´´
git clone https://github.com/LillianaU/tallerAlertasJs.git

´´´´

### abrir mi  usuario en este pc ###

´´´´
git config --global user.name "lillianau"
git config --global user.email "lillianauribe@gmail.com"


´´´´
### comprobar ###
git config --list
### iniciarlizar git  para poder subir cambios del proyecto ##

´´´´
git init
´´´
### comando para verificar rama ###
git branch
## paso a paso para subir mi respositorio ##
# paso 1
git remote add origin https://github.com/LillianaU/expresiones_regulares.git
# paso 2 establecer  rama
git branch -M main
# crear commin son obligatorios
git commit -m " estamos subiendo en index al repositorio donde esta la documentacion de js para las expresiones regulares, esta parte es la plantilla sin funciones"

git push -u origin main