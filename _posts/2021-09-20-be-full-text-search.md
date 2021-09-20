---
layout: post
title: 🐍 Search & Automatic Deploys 🐍
tags: phase-3 phase-3-be full-text-search deploy file-upload
---

## Today's Topics

- Postgres full-text search
- Automatic deploys with Heroku's GitHub integration

## 🎯 Project: QuestionBox is due on Thursday morning

By today you should have working endpoints for:

- login and logout
- registration
- all questions
- all answers for a single question (this is probably the same as question detail)
- all questions for a single user
- all answers for a single user
- create a question
- create an answer for a question

Depending on how you've constructed your API, you might have separate endpoints for all of the above, or you might have fewer endpoints (for instance, if you nested answers in the question detail endpoint). What matters is that your have endpoints your front-end team can use to access this data.

This week you should work on endpoints for:

- search all questions
  - optionally search questions and answers
- delete a question (only the user who created the question)
  - optionally allow editing a question but _only_ for unanswered questions.
- mark an answer as accepted (only if you are the author of the associated question)
- favorite/"star" a question (authenticated users only)
- any of the "spicy" options you want to take on!

## 📖 Read | 📺 Watch | 🎧 Listen

- 📖 [Basic and Full-Text Search with Django and Postgres](https://testdriven.io/blog/django-search/)
- 📖 [If you want A LOT more detail about full-text search in Postgres and Django, this blog piece has you covered](https://pganalyze.com/blog/full-text-search-django-postgres)
- 📖 [Blog post with more on full-text search](https://www.netlandish.com/blog/2020/06/22/full-text-search-django-postgresql/)
- [Search from the Ground Up](https://www.youtube.com/watch?v=is3R8d420D4&list=PL2NFhrDSOxgXXUMIGOs8lNe2B-f4pXOX-&index=2) -> DjangoCon 2019 video explaining search in detail


## 🔖 Resources

### `@action` decorator in ViewSets

- [DRF Docs: Marking extra actions for routing with the `@action` decorator](https://www.django-rest-framework.org/api-guide/viewsets/#marking-extra-actions-for-routing)
- [DRF Docs: Routing for extra actions](https://www.django-rest-framework.org/api-guide/routers/#routing-for-extra-actions)

### Filtering and search

- [DRF - Filtering](https://www.django-rest-framework.org/api-guide/filtering/) -> Pretty useful reference. Includes how to filter your output based on GET parameters, which you will want to do for using search terms.
- [Django Docs: full-text search & the search lookup](https://docs.djangoproject.com/en/3.2/ref/contrib/postgres/search/#the-search-lookup)
- [Django Docs: SearchVector](https://docs.djangoproject.com/en/3.2/ref/contrib/postgres/search/#searchvector) -> You'll need this if you want to search against more than a single field
- [Blog post with a lot more on full-text search](https://www.netlandish.com/blog/2020/06/22/full-text-search-django-postgresql/)
- [If you want even more detail about full-text search in Postgres and Django, this blog piece has you covered](https://pganalyze.com/blog/full-text-search-django-postgres)

## 🦉 Code

- [DRF Library API](https://github.com/Momentum-Team-9/example-drf-library)
