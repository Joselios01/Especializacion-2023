 documento de los comandos de UBUNTU y GIT

tree -a -c          -> abre listado de archivos y carpetas contenidas en forma de arbol.
ls                  -> Listado de archivos y carpetas, separados por espacios, ocultos "no" (instruccion de windows)
rm -r carpeta/*.*   -> borra todos los archivos dentro de carpeta



******************************************************
nano archivo.md    -> crea un archivo dentro de la carpeta actual de nombre archivo.md junto con un editor en consola
   Ctrl + X    -> salir
  
  
  
  
******************************************************
 git status      -> devuelve el estado del repositorio
- 
- En la rama master     -> me indica en que rama estoy
-
-No hay commits todavía   ->no hay ningun commit anterior o en uso
-
-Archivos sin seguimiento:    
-  (usa "git add <archivo>..." para incluirlo a lo que se será confirmado)-
-	archivo.md                      -> aparece en color rojo, indicando que el archivo o su modificacion no a sido incluida al repositorio 
-
-no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
-
 
 
 git add archivo    -> pasa un archivo de unTraking a Stage preparado para confirmar
