<p style="margin: 10px 0px 0px;"><a href="/"><strong>← Back to homepage</strong></a></p>

<h1 id="news"></h1>

<h2 style="margin: 20px 0px 10px;">News</h2>

<ul>
{% for item in site.data.news.items %}
<li><strong>[{{ item.date }}]</strong> {{ item.text }}</li>
{% endfor %}
</ul>

<p style="margin-top: 10px;"><a href="/"><strong>← Back to homepage</strong></a></p>
