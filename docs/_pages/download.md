---
permalink: /download/
lang: en
layout: splash
classes: wide
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home_header.png
title: Download
mysubtitle: HurricaneLog
feature_row:
  - image_path: /assets/images/linux-logo-small.png
    url: "https://github.com/thiagocorreiap/HurricaneLog/releases/latest/download/HurricaneLog_v1.1.0_Linux.zip"
    btn_alignment: "center"
    btn_class: "btn btn--primary btn--small"
    btn_label: "<i class='fas fa-download'></i> Linux"
  - image_path: /assets/images/apple-logo-small.png
    url: "https://github.com/thiagocorreiap/HurricaneLog/releases/latest/download/HurricaneLog_v1.1.0_macOS.dmg"
    btn_alignment: "center"
    btn_class: "btn btn--primary btn--small"
    btn_label: "<i class='fas fa-download'></i> macOS"
  - image_path: /assets/images/windows-logo-small.png
    url: "https://github.com/thiagocorreiap/HurricaneLog/releases/latest/download/HurricaneLog_v1.1.0_Windows.exe"
    btn_alignment: "center"
    btn_class: "btn btn--primary btn--small"
    btn_label: "<i class='fas fa-download'></i> Windows"
---
<h2>Play for free now!</h2>
<h3>Please, select your operational system:</h3>

{% include feature_row row_align="center" %}

You can also access the <a href="{{ 'consent_form.pdf' | prepend:'/assets/files/' | absolute_url }}" download="consent_form.pdf">*Information and Consent*</a> form to have more information on the experiment.

For help with the installation, visit our <a href="{{ '/installation/' | relative_url }}">installation guide</a>.

<h3>Please, watch this tutorial walkthrough or play the tutorial before playing the game.</h3>

<iframe 
src="https://www.youtube.com/embed/HSAt9XY2yqk">
</iframe>