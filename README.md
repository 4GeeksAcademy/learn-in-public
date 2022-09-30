 # Learn In Public (for introverts and extroverts)

> 🚨 Important information for the teachers, [please read this if you are a teacher](./TEACHERS_INSTRUCTIONS.md).

Contributions are Github's bread-and-butter, the main purpose. It's time to start your first GitHub contribution. 

<p align="center"><img src="https://github.com/4GeeksAcademy/learn-in-public/blob/master/resume.png?raw=true" height="400" /></p>
 
## The Pull Request

Git offers a way to push code to a repository without owning it, or even being invited to it, it's called a `Pull request` and the main goal of this exercise is to create your first `Pull request`. [Here is a 12min video explaining pull requests](https://www.youtube.com/watch?v=_NrSWLQsDL4).

## Your Public Profile
  
During this project you will start building your professional profile, one of the most significant accomplishments you can have at the academy:

- It will be the first version of your developer portfolio.

- This will be the first version of your Resume (as a coder).
  
- It will give more context to your learning experience: you can see a table of everything you will learn throughout the course.
  
This [Student Showcase](https://sep.4geeksacademy.com/) it's still in beta. You can find the list of students that have their profile already built, you can also click around each student to find their public information (github profile, twitter usernames, linkedin profiles, etc.).
  
Don't worry about the content of your profile, today its just about the YML structure and making sure you show up on the [student list](https://sep.4geeksacademy.com/), later you can do more updates to your profile.

## How to build your own profile inside the Student Showcase?

1. Fork [the repository](https://github.com/4GeeksAcademy/About-4Geeks-Academy).

  ![alt-text](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
  
  A new repository will be created in your account.
  
2. Clone the new repository into your *workspace* or open it on Gitpod (ask your teacher on how to open your fork on Gitpod if your don't know).
  
3. In your *workspace*, create a file `<your_github_username>.yml` file inside `/site/resumes/` with your profile information. 

  The `YML` file must contain all your personal and professional information. Check the details in [Completing the YML file](#completing-the-yml-file)
  
  For example: [example.yml](https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/resumes/example.yml).
  
  ```
  Important: You should test your `YML` syntax here: http://www.yamllint.com/
  ```

4. Commit and push your changes.

  `$ git add .`
  
  `$ git commit -m "my profile"`
  
  `$ git push origin master`
  

5. Go back to [Github](https://github.com) and look for the recently created repository. In it you will find a button to "Pull Request" your changes back into the main repository.

  ![alt-text](https://github-images.s3.amazonaws.com/help/pull_requests/recently_pushed_branch.png)


After completing the PR (Pull Request) the application will automatically generate your own student portfolio, to see it, see if your name appears here: 

**[https://sep.4geeksacademy.co](https://sep.4geeksacademy.com/)**

Your profile should look like the following:

<p align="center">
  <img height="350" src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/preview.png?raw=true">
</p>

<p align="center">
  <a href="https://sep.4geeksacademy.com/84mulville/profile?lang=en&theme=white" target="_blank">Wach Live Demo Here</a>
</p>

## Completing the YML file

The YML file it's comprised of 4 major sections: 

```yml
theme: You can choose a theme and skin colors.
basic_info: Personal info.
education: Previous studies.
experiences: Previous jobs.
projects: Describe the projects you've built as a developer.
publications: Any articles you have published.
skills: List your skills with a percentage of expertise.
```


<p align="center">
  <img height="350" src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/yml.png?raw=true">
</p>

You can pick a different template and skin, for example:

```yml
template: "online-cv"
skin: "orange"
```
