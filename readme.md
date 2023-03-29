# BIENVENIDOS AL TECH LAB DE GIT FLOW    

## Primera Parte
1. Hacer grupos de 4 personas
2. Asignar roles, así:
   * 3 Developers  
   * 1 Release manager
3. Fork del repositorio
   * <https://github.com/isanchezf/TechLabGitFlow.git>
4. Clonar repositorio copia.
5. Validar que existan ramas Main y Dev
6. Validar que esten bloqueadas o que no permitan subir cambios directamente.
7. Developer 1 crea rama feature_1
8. En caso de no existir, crear archivo alumnos.txt e ingresar su nombre y mesa a la que pertenece.
9.  Realizar comandos necesarios para subir la rama temporal a repositorio remoto.
10. Developer 2 y 3 clonan rama feature_1 y agregan sus nombres y mesa en la que estan en el archivo alumnos.txt
11. Developer 2 y 3 confirman cambios al repositorio remoto (Solucionar conflictos).
12. Developer 1 realizar Merge Request a la rama Dev.
13. Release Manager valida que esten los nombres de los developers y acepta el MR.
14. Release Manager genera rama Release.
15. Falta el nombre de un integrante del equipo, generar un bug en la rama release.
16. Clonar rama release
17. Generar rama bug y agregar el nombre del release manager con mesa a la que pertenece en el archivo alumnos.txt
18. Confirmar la rama bug en repositorio remoto y hacer Merge Request a la rama release.
19. Release Manager acepta *Merge Request* si sus datos son correctos.
20. Release manager realiza *Merge Request* a rama Main.
21. Release manager genera Release y genera tag con la estretegía de versionamiento semantico, aumentando el digito de Cambio Mayor.

## Segunda parte

### 1. Realizar una mejora

Como equipo nos auto-organizamos y generamos algun dato adicional en los datos suministrados en el archivo alumnos.txt

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 2. Realizar un Feature nuevo

Auto-organizarse e incluir un nuevo archivo con algun texto a elección para subir.

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 3. Solucionar un Hotfix

Validar algun cambio pequeño que se deba hacer en rama *Main*, simulando una incidencia productiva.

Tener en cuenta:

* Realizar cambios en ramas temporales, prohibido subir cambios directamente a ramas de larga duración (*Dev/Main*)
* Contemplar flujo *Git Flow*.
* Identificar de que rama padre se generara la rama Hotfix.
* Al momento de subir el cambio a *Main*, validar cual digito de versionamiento semántico (*X.Y.Z*) se debe aumentar.

### 4. Socialización

Nos reuniremos todos los equipos, explicaremos nuestros ejercicios y comentaremos:

* ¿Qué se nos complicó más?
* ¿Qué dudas surgieron?
* ¿Que problemas se presentaron y comó los solucionaron?

Nota: Escoger un representante por grupo.