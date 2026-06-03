<h1 id="news"></h1>

<h2 style="margin: 60px 0px 10px;">News</h2>

<ul>
{% for item in site.data.news.items limit:5 %}
<li><strong>[{{ item.date }}]</strong> {{ item.text }}</li>
{% endfor %}
</ul>

<p style="margin-top: 10px;"><a href="/news.html"><strong>Full list of news →</strong></a></p>
