La subida remota de archivos con Git permite mantener un 
control de versiones seguro y colaborativo, facilitando que los cambios 
locales se guarden y compartan en un repositorio en línea.
## Resumen del procedimiento para conectar el repositorio local con GitLab
1. Clonar el repositorio desde GitHub.
2. Crear un nuevo repositorio vacío en GitLab.
3. Agregar GitLab como remoto adicional con `git remote add`.
4. Verificar remotos con `git remote -v`.
5. Subir el contenido al nuevo repositorio en GitLab con `git push`.