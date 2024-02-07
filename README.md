 # Learn In Public (for introverts and extroverts)

> 🚨 Important information for the teachers, [please read this if you are a teacher](https://github.com/4GeeksAcademy/learn-in-public/blob/master/TEACHERS_INSTRUCTIONS.md).

Contributions are GitHub's bread-and-butter, the main purpose. It's time to start your first GitHub contribution. 

<p align="center"><img src="https://github.com/4GeeksAcademy/learn-in-public/blob/master/resume.png?raw=true" height="400" /></p>
 
## The Pull Request

Git offers a way to push code to a repository without owning it, or even being invited to it, it's called a `Pull Request` and the main goal of this exercise is to create your first `Pull Request`. [Here is a 12min video explaining pull requests](https://www.youtube.com/watch?v=_NrSWLQsDL4).

## Your Public Profile
  
During this project, you will start building your professional profile, one of the most significant accomplishments you can have at the academy:

- It will be the first version of your developer portfolio.

- This will be the first version of your Resume (as a coder).
  
- It will give more context to your learning experience: you can see a table of everything you will learn throughout the course.
  
Open this [Student Showcase](https://sep.4geeksacademy.com/) (still in beta): Here you can find the list of some students that have their profile already built, you can also click around each student to find their public information (GitHub profile, Twitter usernames, Linkedin profiles, etc.).
  
Don't worry about the content of your profile, today its just about the YML structure and making sure you show up on the [students list](https://sep.4geeksacademy.com/), later you can do more updates to your profile.

## How to build your own profile inside the Student Showcase?

1. Open this URL and fork the repository https://github.com/4GeeksAcademy/4GeeksAcademy

  ![fork button](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/fork_button.png?raw=true)
  
  A new repository will be created in your account.
  
2. Open the new forked repository using a provisioning tool like Codespaces (recommended) or Gitpod (ask your teacher on how to open your fork).
  
3. In your Codespace, create a file `<your_github_username>.yml` file inside `/site/resumes/` with your profile information. 

  The `YML` file must contain all your personal and professional information. 
  
  Open this template and copy its contents to start making your profile: [example.yml](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/resumes/example.yml)
  
  > 💡 Important: You should test your `YML` syntax here: https://www.yamllint.com/

4. Commit and push your changes.

  `$ git add .`
  
  `$ git commit -m "my profile"`
  
  `$ git push origin master`
  
5. Go back to [GitHub](https://github.com) and look for the recently created repository. In it you will find a button to "Pull Request" your changes back into the main repository.

  ![pull request button](https://github.com/4GeeksAcademy/4GeeksAcademy/blob/master/site/src/static/pull_request_button.png?raw=true)


After completing the PR (Pull Request) the application will automatically generate your own student portfolio, to see it, see if your name appears here: 

**[https://sep.4geeksacademy.com](https://sep.4geeksacademy.com/)**

Your profile should look like the following:

<p align="center">
  <img height="350" src="https://breathecode.herokuapp.com/v1/media/file/preview-resume-png">
</p>

<p align="center">
  <a href="https://sep.4geeksacademy.com/84mulville/profile?lang=en&theme=white" target="_blank">Watch Live Demo Here</a>
</p>

## Completing the YML file

The YML file it's comprised of 5 major sections: 

```yml
basic_info: Personal info.
education: Previous studies.
experiences: Previous jobs.
projects: Describe the projects you've built as a developer.
skills: List your skills with a percentage of expertise.
```


<p align="center">
  <img height="350" src="https://breathecode.herokuapp.com/v1/media/file/preview-png">
</p>

You can pick a different template and skin, for example:

```yml
template: "online-cv"
skin: "blue"
```

This and many other projects are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).
