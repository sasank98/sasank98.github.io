---
layout: archive
title: "Projects"
permalink: /projects/ 
author_profile: true
---
<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
<html>
<head>
  <style>
    .row {
      display: flex;
      flex-wrap: wrap;
      column-gap: 30px;
      justify-content: center; /* Center the columns horizontally */
    }
    .column {
      flex: 50%;
      padding: 20px;
      border: 1px solid grey; /* Add a border around each column */
      border-radius: 10px; /* Round the corners of the boxes */
      box-sizing: border-box; /* Include border and padding in element's total width and height */
      display: flex; /* Make the column a flex container */
      flex-direction: column; /* Stack the items vertically */
      align-items: center; /* Center the items horizontally */
    }
    .column img {
      width: 100%;
      height: auto;
      max-width: 300px;
      object-fit: cover;
      border-radius: 10px;
    }
    .column h2 {
      font-weight: bold;
      padding: 10px; /* Add padding around the title */
    }
    .column p {
      font-size: 14px; 
      text-align: justify;
      padding: 10px; /* Add padding around the description */
    }
  </style>
</head>
<body>
  <div class="row">
    {% for feature in site.data.features %}
      <div class="column">
        <img src="{{ feature.image_path }}" alt="{{ feature.alt }}">
        <h2> {{ feature.title }}  <a href="{{ feature.url }}"><code>Github</code></a></h2> <!-- Add feature.url in href -->
        <p>{{ feature.excerpt }}</p>
      </div>
    {% endfor %}
  </div>
</body>
</html>
