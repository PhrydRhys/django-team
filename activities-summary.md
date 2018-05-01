The summary should contain the following items:

- list of issues that you attempted/considered with a brief comment stating if you decided to work on it or not and how successful the work was

|                  **Ticket Number**                  |        **Comment**                |
|-----------------------------------------------------|-----------------------------------|
|[#29233](https://code.djangoproject.com/ticket/29233)|We planned to take it, but the maintainer decided that it didn't need to be fixed and closed the ticket.|
|[#28290](https://code.djangoproject.com/ticket/28290)|Decided not to work on it          |
|[#29122](https://code.djangoproject.com/ticket/29122)|We took it, but the maintainer recommended us not to because it had a "maybe" status|
|[#29258](https://code.djangoproject.com/ticket/29258)|We considered taking it, but the life cycle was very quick (was taken and completed within days)|
|[#29148](https://code.djangoproject.com/ticket/29148)|We were considering it but realized that the PR was closed on GitHub just 2 hours ago and it hasn't been updated on Django's Ticket Tracker yet.|
|[#28667](https://code.djangoproject.com/ticket/28667)|Decided not to take it|
|[#28581](https://code.djangoproject.com/ticket/28581)|Has a patch that needed to be updated, we decided not to do it|
|[#29261](https://code.djangoproject.com/ticket/29261)|Assigned already and has a patch that needs improvement, but user claimed that they were going to do it|
|[#29131](https://code.djangoproject.com/ticket/29131)|Considered taking it but after looking into it, issue looks harder than it seemed in the beginning|
|[#28273](https://code.djangoproject.com/ticket/28273)|The issue was too complicated|
|[#28539](https://code.djangoproject.com/ticket/28539)|Decided not to take it|
|[#29329](https://code.djangoproject.com/ticket/29329)|Decided not to work on it|
|[#29332](https://code.djangoproject.com/ticket/29332)|Bug was closed as duplicate|
|[#29281](https://code.djangoproject.com/ticket/29281)|We didn't know how to solve it|
|[#27946](https://code.djangoproject.com/ticket/27946)|Considered it but decided not to take it|
|[#29249](https://code.djangoproject.com/ticket/29249)|Wasn't sure how to improve the patch|
|[#29120](https://code.djangoproject.com/ticket/29120)|Decided not to work on it|
|[#29157](https://code.djangoproject.com/ticket/29157)|Decided that we're not qualified to do it|
|[#29056](https://code.djangoproject.com/ticket/29056)|Decided not to work on it|
|[#27925](https://code.djangoproject.com/ticket/27925)|It was for an outdated version of Django, so we decided not to do it|
|[#29274](https://code.djangoproject.com/ticket/29274)|Claimed the issue, PR merged|
|[#29351](https://code.djangoproject.com/ticket/29351)|Claimed the issue, PR pending approval|
|[#29359](https://code.djangoproject.com/ticket/29359)|Claimed the issue, PR rejected|
|[#29369](https://code.djangoproject.com/ticket/29369)|Created the issue, PR merged ([mailing list discussion](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!topic/django-developers/-rrIRia5IuU))|


- list of pull requests with a mention of its current status (accepted, rejected, still waiting, making changes, ...) and a list of group members who worked on that pull request

|#|Pull Request #|Status|Group Members|
|-|--------------|------|-------------|
|1|Ticket [#29274](https://code.djangoproject.com/ticket/29274), PR [#9875](https://github.com/django/django/pull/9875)|Accepted|Everyone (But only Rohit and Jessica made commits)|
|2|Ticket [#29351](https://code.djangoproject.com/ticket/29351), PR [#9907](https://github.com/django/django/pull/9907)|Pending|Kelly|
|3|Ticket [#29369](https://code.djangoproject.com/ticket/29369), PR [#9908](https://github.com/django/django/pull/9908)|Accepted|Kenneth|
|4|Ticket [#29359](https://code.djangoproject.com/ticket/29359), PR [#9912](https://github.com/django/django/pull/9912)|Rejected|Shiyang|

- for each group member individually: a list of commits to the fork repository in the class organization (some of you have lots of them in different branches and finding them turned out to be challenging)

1. Rohit
- [Added new password list](https://github.com/django/django/commit/53efaa80a46a412d11b341b38643360686acf9d3)
- [Added in old passwords that are missing from the new list](https://github.com/django/django/commit/6a609490477cabfaf5f83485099ca7a3bc276b8c)
2. Jessica
- [Deleted hex errors in password list](https://github.com/django/django/commit/3dfd731662325b803a910a25d5587e82191c2bd9)
- [Updated Documentation for password list](https://github.com/django/django/commit/7c3e0cee0f9045d1e87bef7ced5b6b8b5af6555d)
- [Updated Documentation for password list (part 2)](https://github.com/django/django/commit/afbe18cd23efe20ca63afd4f0dafeb34fb079c7d)
3. Shiyang	
- [Updated middleware documentation with deprecated ExceptionMiddleware](https://github.com/nyu-ossd-s18/django/commit/c03c398181c4183843c1cda00603d698fd1562d5)
4. Kelly
- [Documented that ModelAdmin.prepopulated_fields removes stop words](https://github.com/nyu-ossd-s18/django/commit/b1d990c195de04620683b5fc0e524bc3d9b5813a)
- [reworded how ModelAdmin.prepopulated_fields removes stop words](https://github.com/django/django/pull/9907/commits/e14b9a0e6dc93d74d3957709ec29102febabfe59)
5. Kenneth
- [Added information of #django-dev IRC channel](https://github.com/nyu-ossd-s18/django/commit/8754e763c3cdeffa26cd081b93fdb86dc288058a)
- [Added information of #django-dev IRC channel (part2)](https://github.com/nyu-ossd-s18/django/commit/4eb44ea943b7c2c239997f6ad1c229926ef1b267)
