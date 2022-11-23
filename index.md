<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reconnect to Chaos</title>
</head>
<body>
  {% if site.lang == "de" %}
    {% capture link1 %}{{ site.baseurl_root }}/en{{ page.url}}{% endcapture %}
    <a href="{{ link1 }}" >{% t global.english %}</a>
  {% elsif site.lang == "en" %}
    {% capture link2 %}{{ site.baseurl_root }}{{ page.url  }}{% endcapture %}
    <a href="{{ link2 }}" >{% t global.german %}</a>
  {% endif %}
    <h1>Reconnect to Chaos</h1>
    <h2>27.12.2022 - 30.12.20222</h2>
    <div>
        {% translate_file rtc/abstract.md %}
    </div>
    <ul>
      <a class="button button-75 center" role="button" href="https://tickets.ccc-p.org/rtc22/"><span class="text">Tickets</span></a>
      <a class="button button-75 center" role="button" href="https://cfp.ccc-p.org/rtc22/"><span class="text">CfP</span></a>
    </ul>
</body>
</html>
