 # Perfil externo del estudiante (para introvertidos y extrovertidos)

Las colaboraciones sustentan a Github, son su propósito principal. Es hora se que realices tu primera colaboraación en Github.

<p align="center"><img src="https://github.com/4GeeksAcademy/learn-in-public/blob/master/resume.png?raw=true" height="400" /></p>
 
## Pull Request

Git ofrece una forma de compartir (pushing) código con un repositorio sin ser el dueño, o incluso sin ser invitado a él, se llama **"Pull request"** y estás a punto de hacer tu primera PR (Pull Request). [Aquí hay un video que explica las Pull Requests](https://www.youtube.com/watch?v=xl3nxfbGkzY).
## Tu perfil público
  
Durante este proyecto comenzarás a construir tu perfil profesional y es uno de los logros más significativos que podrás tener en la academia:

> Esta será la primera versión de su CV (como programador).
  
Este [Student Showcase ( Lista de perfiles de los estudiantes)](https://sep.4geeksacademy.co/) aún está en versión beta. Ahí puedes encontrar una lista de estudiantes que ya han creado su perfil. También puedes darle clic a los diversos perfiles de estudaiantes y ver su información (perfil en Github, nombre de usuario de Twitter, perdil de LinkedIN, etc.).

No te preocupes por el contenido de tu perfil, hoy nos centraremos en la estructura YML y en que aparezcas en la [lista de estudiantes](https://sep.4geeksacademy.co/), luego podrás seguir actualizando tu perfil.
  
## ¿Cómo crear tu propio perfil dentro Student Showcase?

1. Haz un fork del [repositorio](https://github.com/4GeeksAcademy/About-4Geeks-Academy).

  ![alt-text](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
  
Esto creará un nuevo repositorio en tu cuenta de Github.
  
2. Clona el nuevo repositorio en tu  *workspace* (espacio de trabajo).
  
  ```$ git clone <url_of_repository>```
  
3.  En tu *workspace*, crea un archivo `<your_github_username>.yml` dentro `/site/resumes/` con información sobre tu perfil. 

  El archivo `YML` debe contener toda tu información personal y profesional. Puedes ver los detalles [completando el archivo YML](#completing-the-yml-file)
  
  Por ejemplo: [example.yml](https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/resumes/example.yml).
  
  ```yml
  Importante: Deberías verificar tu sintaxis `YML` aquí: http://www.yamllint.com/
  ```

4. Dale 'commit' y 'push' a tus cambios.

  `$ git add .`
  
  `$ git commit -m "my profile"`
  
  `$ git push origin master`
  
5. Regresa a [Github](https://github.com) y busca el repositorio creado recientemente. Una vez dentro de tu repositorio, busca el botón **"Contribute & Pull Request"** que enviará/compratirá los cambios que realizaste desde tu repositorio al repositorio principal.

  ![alt-text](https://github-images.s3.amazonaws.com/help/pull_requests/recently_pushed_branch.png)

Luego de completar la PR, la aplicación automáticamente generará tu propio portafolio de estudiante, para verlo, verifica que tu nombre aparezca en esta lista:

**[https://sep.4geeksacademy.co](https://sep.4geeksacademy.co/)**

Tu perfil debería parecerse al siguiente:

<p align="center">
  <img height="350" src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/preview.png?raw=true">
</p>

<p align="center">
  <a href="https://sep.4geeksacademy.co/sharu725" target="_blank">Wach Live Demo Here</a>
</p>

## Completando el archivo YML

El archivo YML tiene 4 secciones principales:

```yml
theme: Puedes escoger el `theme` y el skin color (color de fondo).
basic_info: Información personal.
education: Estudios.
experiences: Experiencia llaboral
projects: Decribe los proyectos que hayas hecho como desarrollador.
publications: Cualquier artículo que hayas pubicado.
skills: Haz una lista de tus habilidades/capacidades y asígnales un porcentaje de expertiz.
```

<p align="center">
  <img height="350" src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/yml.png?raw=true">
</p>

Tu puedes escoger otro formato con otros colores, por ejemplo:

```yml
template: "online-cv"
skin: "orange"
```
