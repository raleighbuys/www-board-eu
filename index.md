---

title: OWASP Global Board EU Entity
layout: col-sidebar
tags: eu board

---

<!-- rebuild 001 -->

<h2>Board of Directors</h2>

<section id="board" class="corporate">
<div>	
 {% for member in site.data.board %}
    <div class="member-container">
        <div class="member-img-container">	
            <div class="member-img" style="background-image: url({{ member.image }});">
            </div>
        </div>
        <div class="member-caption"><h2>{{ member.name }}</h2><hr><strong>{{ member.title }}</strong><br/>
        <div class="member-location">{{member.location}}</div></div><br/>
        <div class="member-info">{{ member.description }}</div>	
    </div>
    <div style="height:18px;"></div>
{% endfor %}	
</div>
</section>

## EU Entity Board Meetings

- [May 2021](/www-board-eu/202105)
- [May 2022](/www-board-eu/202205)
- [May 2023](/www-board-eu/202305)
