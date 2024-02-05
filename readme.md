# Requisitos del sistema

Trabajas en un proyecto de git utilozando comando de git log para obtener un resumen de los utlimos 5 comits en todas las ramas

Vision grafica y detallada del historial de comits.

- Muestra una reprecentacion grafica del historial de commits
- muestra el hash cort del commit en color rojo
- Muestra las refencias(Rams o tags) e las que esta involucrado el commit en color amarillo
-Muestra el mensaje del commit
- muestra la fecha relativa del commit en color verde
- muestra el hash del commit en color verde
- Muestra el hash del commmit como un identificador abreviado
- Muestra las fechas de los commits de forma relativa

Estas trabajan frecuentemente con el comando git log -1 HEAD para obtener detalles sobre el ultimo commit en la rama acutal

Imagina que deseas simplificar el proceso de editar la configuracion global de fit tu tarea es utilizar el comando git config para crear un alias que te permita abrir facilmente la configuracion glibal en tu editor de texto

1) se debe inicializarun repositorio: con "git config --Global init.defaiultBranch main"
2) "git add nombre_del_archivo
3) "git rm"
"GIT log"
"git log --oneline"
"git log --oneline --decorate -- all -- graph"
"git config --global core.editor 'core --wait'
"git commit --amend"
"git chechkout--"
"Git Reset"
"GitKeep"
"Git statis --short"
"git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold
blue)%h%C(reset) - %C(bold green) (%ar)%C(reset)%C(white)%s%C(reset)%C(dim
white)-%an%C(reset)%C(bold yellow)%d%C(reset)' --all""
