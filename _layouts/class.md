---
layout: "wrapper"
---

<article id="Class">
        <header>
                {% if page.previous.url %}
                        <a class="prev" href="{{page.previous.url}}"><span class="icon">navigateleft</span>{{page.previous.title}}</a>
                {% endif %}
                <h1>{{ page.title }}</h1>
                {% if page.next.url %}
                        <a class="next" href="{{page.next.url}}">{{page.next.title}} <span class="icon">navigateright</span></a>
                {% endif %}
        </header>

        {{ content }}

</article>
<footer>
</footer>