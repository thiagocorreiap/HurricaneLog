---
layout: splash
permalink: /fr/
lang: fr
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home_header.png
  actions:
    - label: "<i class='fas fa-download'></i> Télécharger maintenant"
      url: "/fr/download/"
excerpt: >
  Découvrez les opérations logistiques humanitaires tout en vous amusant.<br />
feature_row:
  - image_path: /assets/images/hurricane_home.png
    alt: "hurricanes"
    title: "Ouragans basés sur des données réelles"
    excerpt: "Déplacement des ouragans basé sur des données des saisons passées d'ouragans de l'Atlantique."
    url: "/fr/features/#Feature1"
    btn_class: "btn--primary"
    btn_label: "En savoir plus"
  - image_path: /assets/images/hurricane_damage.jpg
    alt: "damages"
    title: "Dommages réalistes"
    excerpt: "Dommages aux régions basés sur des données collectées à partir de bases de données en ligne."
    url: "/fr/features/#Feature2"
    btn_class: "btn--primary"
    btn_label: "En savoir plus"
  - image_path: /assets/images/data_collection.jpg
    alt: "dataCollection"
    title: "Outil de collecte de données"
    excerpt: "Collecte d'informations à partir des décisions des joueurs en matière de préparation et de réponse aux catastrophes."
    url: "/fr/features/#Feature3"
    btn_class: "btn--primary"
    btn_label: "En savoir plus"      
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

<div class="container">
  <div class="center" style="margin-left: 20px;">
      <h3>HurricaneLog remporte un prix au concours de jeux sérieux</h3>
      <p>Honoré du prix spécial dans la catégorie des jeux adressant la préparation aux crises et urgences, la réponse, la récupération et la résilience lors du concours de la Serious Game Society.</p>
  </div>
  <img src="{{ '/assets/images/news/prize.png' | relative_url }}" alt="prize" width="400" class="feature_image">
</div>

 <hr>

{% include feature_row %}
