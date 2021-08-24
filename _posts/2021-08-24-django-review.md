---
layout: post
title: Django Review 🔄
tags: phase-2 django
---

## 🗓️ Today's Topics

- Progress report on Code Snippets and Flashcards
- Django review & questions

## 🎯 Project: Django Duplex

Continue working together on this project. You should be working on the core functionality and addressing bugs as you work.

## 🔖 Resources

### Models & Queries

- [Retrieving Objects](https://docs.djangoproject.com/en/3.2/topics/db/queries/#retrieving-objects)
- [Video: How Model Queries Work in Django](https://www.youtube.com/watch?v=WimXjp0ryOo)
- [Django Q objects for complex queries](https://docs.djangoproject.com/en/3.2/ref/models/querysets/#q-objects)
- [Complex lookups with Q objects](https://docs.djangoproject.com/en/3.2/topics/db/queries/#complex-lookups-with-q)

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


## 🦉 Code

- [Django Music Example App: Search](https://github.com/Momentum-Team-9/example-django-music/tree/search)
- [Django Music Example App: Adding JS](https://github.com/Momentum-Team-9/example-django-music/tree/adding-js-to-django)
