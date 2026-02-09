# Welcome to Srujana's Blog

This is my personal site about AI and code.

## Latest Posts

{% for post in site.posts %}
  ## [{{ post.title }}]({{ post.url }})
  **Published on {{ post.date | date: "%B %d, %Y" }}**
  
  {{ post.excerpt }}
  
  [Read more]({{ post.url }})
  
---

{% endfor %}

*Check back soon for more posts on AI, algorithms, and code adventures!*