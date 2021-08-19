---
layout: post
title: Collaborating on a web application
tags: phase-2 django collaboration
---

Today we'll begin our first real team project, with a shared repo. This will require more planning, a lot of communication and coordination, and adding on some new git skills that will let us collaborate.

## 🎯 Project: Django Pair Project

You will work in a shared repo and turn in one application that your team will build together. How you share the work is up to you to determine.

You have two options to choose from for this assignment. Your team should meet to discuss and **decide today** which one you will do. Then, the very first thing you should do is decide what models you will need and what attributes and relationships they should have.

This assignment is due next Thursday at the end of the Phase.

[Link to assignment](https://classroom.github.com/g/dBgZdwJh)

### ✅ Project Checklist

- You will need to set up a new Django project from scratch. There is no starter code in the assignment repo.
- Make sure to create a .gitignore file. You can get one specific to a Django project at [gitignore.io](https://www.toptal.com/developers/gitignore). Just search for `Django` and copy and paste the text you find there into a `.gitignore` file. It should be placed at the root of your project directory.
- You may want to install `django-debug-toolbar`, `django-extenstions`, and `django-environ`, as we have done in previous projects.
- Make sure to create a custom user model, following best practices. Do this before you run any other migrations. [This guide may be helpful to you.](https://learndjango.com/tutorials/django-custom-user-model)

### Teams

For this project, the first team member listed should accept the assignment, then the other team member can accept the assignment and select the repo for their team.

```py
teams = {
    'team_black_bear': ('Joe', 'Connor'),
    'team_flying_squirrel': ('Andrea', 'Mike'),
    'team_red_wolf': ('Em', 'Sarah'),
}
```

## 🔖 Resources

- [GitHub Collaboration Docs](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests)
- [Git Collaboration slides](https://slides.com/amy_nc/git-collaboration/)
- [Git in VS Code](https://code.visualstudio.com/docs/introvideos/versioncontrol) -> I use git on the command line and that's how I teach people to use it. But you might like using the integration in VS Code. This is a good place to start, but there are many other extensions that you could use as well.
- [Pair Programming Guide](https://tuple.app/pair-programming-guide/template) -> This template for a pairing session is practical and actionable. There are other resources on this site worth a look as well.
- [Django cheat sheet](https://github.com/lucrae/django-cheat-sheet) -> This is the same one I posted earlier in the week. If you didn't see it then, you might be glad to see it now.
- [makeareadme.com](https://www.makeareadme.com/)
- [A great example of a README and a cool project](https://github.com/minter/tesla_puck)
- [CRC model](http://agilemodeling.com/artifacts/crcModel.htm) -> The Class-Responsibility-Collaborator model helps you to reason about how you should design your models.
