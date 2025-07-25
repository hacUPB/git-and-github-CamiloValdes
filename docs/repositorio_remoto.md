# Cómo crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local

1. **Crear el repositorio remoto en GitHub:**
   - Ingresar a [github.com](https://github.com) y acceder a la cuenta.
   - Hacer clic en "New" o "Nuevo repositorio".
   - Escribir el nombre del repositorio y configurar las opciones deseadas.
   - Hacer clic en "Create repository".

2. **Obtener la URL del repositorio remoto:**
   - Copiar la URL que aparece, por ejemplo:  
     `https://github.com/usuario/nombre-repositorio.git`

3. **Vincular el repositorio local con el remoto:**
   - En la terminal, dentro de la carpeta del repositorio local, ejecutar:
     ```
     git remote add origin https://github.com/usuario/nombre-repositorio.git
     ```

4. **Subir los cambios locales al repositorio remoto:**
   - Subir el primer commit con:
     ```
     git push -u origin master
     ```
     *(o `main` si tu rama principal se llama así)*

5. **Verificar la sincronización:**
   - Refrescar la página del repositorio en GitHub para ver tus archivos.

Ahora el repositorio local está sincronizado con el remoto 