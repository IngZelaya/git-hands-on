# Mi Primer Proyecto Git
What does this do?

1. `git init` inicializa git en su proyecto. Para ser claros, esto sucederá sólo en la creación del proyecto, ¡no en la clonación! Entonces, cuando trabaje en un proyecto existente, no necesitará realizar este paso.
2. `git add .` agrega todos los archivos a la confirmación (hablaremos más sobre ello).
3. `git commit -m “first commit"`guarda los cambios **localmente** , con el mensaje "primera confirmación". ¿Qué significa *localmente* ? ¡Esa es una buena pregunta y la responderé durante la sección práctica!
4. `git branch -M main` creará una rama remota llamada `main`. (¿Qué es una sucursal? ¡Ya verás!)
5. `git remote add origin` conecta el directorio local al repositorio git remoto.
6. `git push -u origin main` empuja el compromiso a la rama principal remota.
