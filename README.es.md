 # Aprende en Público (para personas introvertidas y extrovertidas)
 
> 🚨 Information importante para los profesores, [por favor lee esto si eres profesor](./TEACHERS_INSTRUCTIONS.md).
 
Las contribuciones son el pan y la mantequilla de Github, el objetivo principal. Es hora de comenzar tu primera contribución en Github. 

<p align="center"><img src="https://github.com/4GeeksAcademy/learn-in-public/blob/master/resume.png?raw=true" height="400" /></p>

## The Pull Request

Git ofrece una forma de insertar código en un repositorio sin poseerlo, o incluso ser invitado a él, se llama `Pull request` y el objetivo principal de este ejercicio es crear tu primer `Pull request`. [Aquí un video de 12min explicando pull requests](https://www.youtube.com/watch?v=_NrSWLQsDL4).

## Tu Perfil Público

Al mismo tiempo, comenzarás a construir tu perfil de estudiante, uno de los logros más importantes que puedes tener en la academia porque:
- Será la primera versión de tu portafolio de desarrolladores.
- Será la primera versión de tu currículum (como un desarrollador).
- Le dará más contexto a tu experiencia de aprendizaje: puedes ver una tabla de todo lo que aprenderás a lo largo del curso.

Este `Student Showcase` todavía está en fase beta y tu eres uno de los primeros estudiantes en convertirse en colaborador. Puedes encontrar la lista de estudiantes que ya tienen su perfil construido en la [SIGUIENTE URL](http://sep.4geeksacademy.co/), También puedes hacer click en el nombre de los estudiantes para encontrar una versión beta de cómo se ve el perfil de los estudiantes en este momento.

## ¿Cómo construir tu propio perfil dentro de Student Showcase?

1. Haz Fork en [el repositorio](https://github.com/4GeeksAcademy/student-external-profile/).

  ![alt-text](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
  
  Se creará un nuevo repositorio en su cuenta.
  
2. Clona el nuevo repositorio en tu *espacio de trabajo*.
  
  ```$ git clone <url_of_repository> ```
  
3. En tu *espacio de trabajo*, crea un archivo `<your_github_username> .yml` dentro de `/ src / students /` con tu información de perfil.

  El archivo `YML` debe contener toda tu información personal y profesional. Verifica los detalles en [Completando el archivo YML](#completing-the-yml-file)
  
  Por ejemplo: [example.yml](https://github.com/4GeeksAcademy/student-external-profile/blob/master/site/resumes/example.yml).
  
  ```
  Importante: deberías probar tu sintáxis de `YML`aqui: http://www.yamllint.com/
  ```

4. Commit y push tus cambios.

  `$ git add .`
  
  `$ git commit -m "my profile"`
  
  `$ git push origin master`
  

5. Volver a [Github](https://github.com) y busca el repositorio creado recientemente. En él, encontrarás un botón para "pull request" de tus cambios nuevamente al repositorio principal.

  ![alt-text](https://github-images.s3.amazonaws.com/help/pull_requests/recently_pushed_branch.png)


Después de completar el PR (Pull Request), la aplicación generará automáticamente tu propio portafolio de estudiantes, para verlo, ve si tu nombre aparece aquí:

**[https://sep.4geeksacademy.co](https://sep.4geeksacademy.co)**

Tu perfil debe verse como el siguiente:

<p align="center">
  <img height="350" src="https://raw.githubusercontent.com/4GeeksAcademy/student-external-profile/master/site/static/preview.png">
</p>

<p align="center">
  <a href="https://sep.4geeksacademy.com/84mulville/profile?lang=en&theme=white" target="_blank">Wach Live Demo Here</a>
</p>

## Completando el archivo YML

El archivo YML consta de 4 secciones principales:
```yml
theme: You can choose a theme and skin colors.
basic_info: Personal info
education: Previous studies.
experiences: Previous jobs.
projects: Describe the projects you've built as a developer.
publications: Any articles you have published.
skills: List your skills with a percentage of expertise.
```

<p align="center">
  <img height="350" src="https://raw.githubusercontent.com/4GeeksAcademy/student-external-profile/master/site/static/yml.png">
</p>

Puede elegir una plantilla y un aspecto diferentes, por ejemplo:

```yml
template: "online-cv"
skin: "orange"
```
