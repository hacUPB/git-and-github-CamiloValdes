# Cómo crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local

1. **Crea el repositorio remoto en GitHub:**
   - Ingresa a [github.com](https://github.com) y accede a tu cuenta.
   - Haz clic en "New" o "Nuevo repositorio".
   - Escribe el nombre del repositorio y configura las opciones deseadas.
   - Haz clic en "Create repository".

2. **Obtén la URL del repositorio remoto:**
   - Copia la URL que aparece, por ejemplo:  
     `https://github.com/usuario/nombre-repositorio.git`

3. **Vincula el repositorio local con el remoto:**
   - En la terminal, dentro de la carpeta de tu repositorio local, ejecuta:
     ```
     git remote add origin https://github.com/usuario/nombre-repositorio.git
     ```

4. **Sube los cambios locales al repositorio remoto:**
   - Sube el primer commit con:
     ```
     git push -u origin master
     ```
     *(o `main` si tu rama principal se llama así)*

5. **Verifica la sincronización:**
   - Refresca la página del repositorio en GitHub para ver tus archivos.

Ahora tu repositorio local está sincronizado con el remoto en