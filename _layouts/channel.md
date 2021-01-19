---
layout: "wrapper"
---
<article id="Channel">
        <section class="calendar">
        {% for class in site.classes %}
        <div class="mission">
                <a class="mission-class_link" href="{{ class.url }}"></a>
                <div class="mission-image">
                        <img src="/img/light_sculpture/syllabus/icon-intro.png">
                </div>
                <div class="mission-text">
                        <header>
                                <span>mission {{ forloop.index }}</span>
                                <!-- <date>06/23</date> -->
                        </header>
                        <h2>{{ class.title }}</h2>
                </div>
        </div>
        {% endfor %}
</article>