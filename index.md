***

layout: default
title: Home
-----------

# *Kaleleakoa*

:: faith (*kalele*) to believe and the courage (*koa*) to achieve ::

***

| About Me |                                                                                                                                                                                                                                                                                             |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|          | I’m a talent development pro who’s diving headfirst into project management and financial planning—because why not mix spreadsheets with people skills? When I’m not geeking out over growth strategies, you’ll find me turning life’s chaos into bite-sized stories and insights. the end. |

***


# My musings

{% for post in site.posts limit:5 %}

*   \[{{ post.title }}]\({{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
    {% endfor %}

