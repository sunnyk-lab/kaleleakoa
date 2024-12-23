---
layout: default
title: Home
---
# Welcome to My Site

***

# Welcome to Kaleleakoa

> ### I’m a talent development pro who’s diving headfirst into project management and financial planning—because why not mix spreadsheets with people skills? When I’m not geeking out over growth strategies, you’ll find me turning life’s chaos into bite-sized stories and insights.  the end.

```markdown
/hello world
```

# Below are my latest posts:
# Latest 5 Posts:

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}
