---
layout: post
title: 🍔 Django with a Side of JavaScript 🍟
tags: phase-2 django javascript ajax search
---

## 🗓️ Today's Topics

- Checking in on Code Snippets and Flashcards Progress
- Implementing search
- Why and how to incorporate JavaScript into your Django application

## 🎯 Project: Code Snippets | Flashcards

Keep on with your end-of-phase project. Today you should have models that you can use in the shell and in your application and at least a solid start on the CRUD functionality your application needs.

## 🔖 Resources

### Debugging

- [Python debugger commands](https://docs.python.org/3/library/pdb.html?highlight=debugger#debugger-commands)
- [Django Debug Toolbar docs](https://django-debug-toolbar.readthedocs.io/en/latest/)

### Foreign Keys

- [Django Model Field Reference: Foreign Key](https://docs.djangoproject.com/en/3.2/ref/models/fields/#foreignkey)
- [Django ORM Cookbook: How to include a Self-Referencing ForeignKey in a Model](https://books.agiliq.com/projects/django-orm-cookbook/en/latest/self_fk.html#how-to-include-a-self-referencing-foreignkey-in-a-model)

### Models & Queries

- [Retrieving Objects](https://docs.djangoproject.com/en/3.2/topics/db/queries/#retrieving-objects)
- [Video: How Model Queries Work in Django](https://www.youtube.com/watch?v=WimXjp0ryOo)

### Implementing Search

- [LearnDjango: SearchTutorial](https://learndjango.com/tutorials/django-search-tutorial) _Will uses class-based views in this post but you can still follow almost all of his steps and use function-based views._
- [MDN: Sending Form Data](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data) _Scroll down to the section on the `GET` method to see how to include form data as query parameters._

### JavaScript & Django

- [Django and AJAX](https://realpython.com/django-and-ajax-form-submissions/)
- [Fetching Data with Ajax and Django](https://www.brennantymrak.com/articles/fetching-data-with-ajax-and-django.html) -> This article is really helpful and has really good code examples. Important notes:
  > By including the 'X-Requested-With' header set to 'XMLHttpRequest' [in the AJAX request], the view will be able to check if the request is AJAX or not.

{% highlight python %}
    # In the view function that handles the AJAX request
    request.headers.get('x-requested-with') == 'XMLHttpRequest'
{% endhighlight %}

- [Django docs on the above](https://docs.djangoproject.com/en/3.2/ref/request-response/#django.http.HttpRequest.is_ajax)
- [Unintrusive JS with Django](https://lethain.com/intro-to-unintrusive-javascript-with-django/)

## ⭐ EXTRA/TMI

- [Django Views the Right Way](https://spookylukey.github.io/django-views-the-right-way/the-pattern.html) _This is a detailed, informative deep dive on function-based views in Django and the reasons why, in the author's opinion, they are better than class-based views._
- [jQuery](https://jquery.com/) _This is not something I recommend using right now, but I include it here because a lot of the resources you will encounter about using JavaScript in a web browser will refer to it (like the article on unintrusive js listed above). It is not as popular as it once was, and it is incompatible with a framework like React. But you will sometimes come across it, and you may end up working with it at your job, so you might as well recognize it when you see it and look it up if you ever need it._

## 🦉 Code

- [Django Music Example App: Search](https://github.com/Momentum-Team-9/example-django-music/tree/search)
-
