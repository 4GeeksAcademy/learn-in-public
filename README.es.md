 # Aprende en Público (para introvertidos y extrovertidos)
 
> 🚨 Información importante para los profesores, [por favor lee esto si eres profesor](https://github.com/4GeeksAcademy/learn-in-public/blob/master/TEACHERS_INSTRUCTIONS.md).
 
Las contribuciones son el pan y la mantequilla de GitHub, el objetivo principal. Es hora de comenzar tu primera contribución en GitHub. 

<p align="center"><img src="https://github.com/4GeeksAcademy/learn-in-public/blob/master/resume.png?raw=true" height="400" /></p>

## El Pull Request

Git ofrece una forma de insertar código en un repositorio sin poseerlo, o incluso ser invitado a él, se llama `Pull Request` y el objetivo principal de este ejercicio es crear tu primer `Pull Request`. [Aquí un video de 12min explicando pull requests](https://www.youtube.com/watch?v=_NrSWLQsDL4).

## Tu Perfil Público

Al mismo tiempo, comenzarás a construir tu perfil de estudiante, uno de los logros más importantes que puedes tener en la academia porque:

- Será la primera versión de tu portafolio de desarrollador.

- Será la primera versión de tu currículum (como un desarrollador).

- Le brindará más contexto a tu experiencia de aprendizaje: puedes ver una tabla de todo lo que aprenderás a lo largo del curso.

Este [Student Showcase](https://sep.4geeksacademy.com/) todavía está en versión beta. Puedes encontrar la lista de estudiantes que ya tienen su perfil creado, también puedes hacer clic alrededor de cada estudiante para encontrar su información pública (perfil de GitHub, nombres de usuario de Twitter, perfiles de Linkedin, etc.).

No te preocupes por el contenido de tu perfil, hoy se trata solo de la estructura YML y de asegurarse de aparecer en la [lista de estudiantes](https://sep.4geeksacademy.com/), luego puedes hacer más actualizaciones para tu perfil.

## ¿Cómo construir tu propio perfil dentro del Student Showcase?

1. Haz Fork de [este repositorio](https://github.com/4GeeksAcademy/4GeeksAcademy).

  ![botón de fork](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/fork_button.png?raw=true)
  
  Se creará un nuevo repositorio en tu cuenta.
  
2. Abre tu nuevo repositorio (fork) con un entorno de desarrollo como Codespaces o Gitpod (pregúntale a tu maestro cómo abrir tu fork si no lo sabes).
  
3. En tu Codespace, crea un archivo `<your_github_username>.yml` dentro de `/site/resumes/` con tu información de perfil.

  El archivo `YML` debe contener toda tu información personal y profesional.
  
  Abre esta plantilla y copia su contenido para empezar a construir tu perfil: [example.yml](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/resumes/example.yml)
  
  > 💡 Importante: debes probar tu sintaxis de `YML` aquí: https://www.yamllint.com/

4. Commit y push a tus cambios.

  `$ git add .`
  
  `$ git commit -m "mi perfil"`
  
  `$ git push origin master`
  
5. Volver a [GitHub](https://github.com) y buscar el repositorio creado recientemente. En él encontrarás un botón para hacer "Pull Request" a tus cambios nuevamente al repositorio principal.


  ![botón de pull request](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/pull_request_button.png?raw=true)
  

Después de completar el PR (Pull Request), la aplicación generará automáticamente tu propio portafolio de estudiante, para verlo, verifica si tu nombre aparece aquí:

**[https://sep.4geeksacademy.co](https://sep.4geeksacademy.co)**

Tu perfil debe verse como el siguiente:

<p align="center">
  <img height="350" src="https://breathecode.herokuapp.com/v1/media/file/preview-resume-png">
</p>

<p align="center">
  <a href="https://sep.4geeksacademy.com/84mulville/profile?lang=en&theme=white" target="_blank">Clic para ver Demo</a>
</p>

## Completando el archivo YML

El archivo YML consta de 5 secciones principales:

```yml
basic_info: Información personal.
education: Estudios previos.
experiences: Trabajos anteriores.
projects: Describe los proyectos que has creado como desarrollador.
skills: Enumera tus habilidades con un porcentaje de experiencia.
```

<p align="center">
  <img height="350" src="https://breathecode.herokuapp.com/v1/media/file/preview-png">
</p>

Puedes elegir una plantilla y un aspecto diferentes, por ejemplo:

```yml
template: "online-cv"
skin: "blue"
```

Este y otros proyectos son usados para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/coding-bootcamps/desarrollador-full-stack/?lang=es), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning).
