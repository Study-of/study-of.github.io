<div class="message">
  DRAFTS - These studies are **being researched**.
</div>

<div class="posts">
  {% for post in site.categories.drafts %}
    <article class="post">

      ##<a href="{{ site.baseurl }}{{ post.url }}">... {{ post.title }}</a>
      
      <div class="date">Published: {{ post.date | date: "%A, %B %-d, %Y" }}</div>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
