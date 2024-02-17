---
layout: splash
permalink: /
lang: en
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home_header.png
  actions:
    - label: "<i class='fas fa-download'></i> Download"
      url: "/download/"
excerpt: >
  Learn about humanitarian logistic operations while having fun.<br />
feature_row:
  - image_path: /assets/images/hurricane_home.png
    alt: "hurricanes"
    title: "Hurricanes based on real-life data"
    excerpt: "Displacement of hurricanes based on data from past Atlantic hurricane seasons."
    url: "/features/#Feature1"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/hurricane_damage.jpg
    alt: "damages"
    title: "Realistic populational damages"
    excerpt: "Damage to regions based on data collected from online databases."
    url: "/features/#Feature2"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/data_collection.jpg
    alt: "dataCollection"
    title: "Data collection tool"
    excerpt: "Collects information from players' disaster preparedness and response decisions."
    url: "/features/#Feature3"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

<style>
    .container {
      display: flex;
      align-items: center;
    }

    .feature_image {
        padding-right: 20px;
        padding-bottom: 5px;
        padding-top: 5px;
        height: auto;
        margin-left: auto;
    }

    .center {
        clear: both;
    }
</style>

<!-- <h3>Awarded top prize in serious game competition</h3> -->
<!-- <p>The seriour game competition organized by the Serious Game Society awarded HurricanLog the special prize on best serious game addressing crisis and emergency preparedness, response, recovery and resilience.</p> -->
<div class="container">
  <div class="center" style="margin-left: 20px;">
      <h3>HurricaneLog Wins Top Prize in Serious Game Competition</h3>
      <p>Honored with the special prize in the category of games addressing crisis and emergency preparedness, response, recovery, and resilience at the Serious Game Society's competition.</p>
  </div>
  <img src="{{ '/assets/images/news/prize.png' | relative_url }}" alt="prize" width="400" class="feature_image">
</div>

 <hr>

{% include feature_row %}
