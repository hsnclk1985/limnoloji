---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#aae3e2"
  overlay_image: /assets/images/hero_anasayfa.jpeg
  #overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  #overlay_filter: rgba(13, 180, 185, 0.5)
  #overlay_filter: rgba(27, 163, 156, 0.9)
  overlay_filter: rgba(134, 163, 184, 0.8)
  actions:
    - label: "Derneğimize Üye Olmak İçin"
      url: "/uyelik/"
excerpt: >
  Türkiye Limnoloji Derneği Resmî Web Sitesidir.<br />

feature_row:
  - image_path: /assets/images/blog.jpeg
    alt: "Abant İzzet Baysal Üniversitesi Mezunları Derneği İBUMED"
    title: "Duyurular"
    excerpt: "Duyurularımız ve paylaştığımız önemli yazılarımız için blog sayfamısı ziyaret edebilisiniz."
    url: "/posts/"
    btn_class: "btn--inverse"
    btn_label: "Blog Sayfamız"
  - image_path: /assets/images/scholarship1.jpeg
    alt: "Limnoloji derneği burs imkanı"
    title: "Burs Çalışmaları"
    excerpt: "Limnoloji Derneği olarak sunduğumuz destekler ve burslar hakkında detaylı bilgiye buradan ulaşabilirsiniz."
    url: "/iletisim/"
    btn_class: "btn--inverse"
    btn_label: "İletişim İçin"
  - image_path: /assets/images/form.jpeg
    alt: "Limnoloji Derneği Üyeliği"
    title: "Limnoloji Derneği Üyeliği"
    excerpt: "Derneğimize üye olmak isteyenler, öncelikli olarak başvuru formunu doldurmaları ve tarafımıza iletmeleri gerekmektedir."
    url: "/assets/docs/limnoloji-uyelik-dilekcesi.doc"
    btn_class: "btn--inverse"
    btn_label: "Üyelik Dilekçesini İndir"    
feature_row2:
  - image_path: /assets/images/izzet-baysal.webp
    alt: "izzet baysal"
    title: "Saygı ve Özlemle..."
    excerpt: "1907 yılında Bolu'da dünyaya geldi. İlk ve orta öğrenimini Bolu'da, yüksek öğrenimini İstanbul Güzel Sanatlar Akademisi'nde Mimar olarak tamamladı. Yıllarca İstanbul'da en fazla gelir vergisi veren ilk on kişi arasında yer aldı. 'En büyük eserimdir' dediği İzzet Baysal Vakfı'nı, vergisi ödenmiş kazançlarından tahsis ederek 1987 yılında kurdu."
    url: "https://izzetbaysalvakfi.org.tr/izzet-baysal/hayati"
    btn_label: "Hakkında"
    btn_class: "btn--inverse"  
feature_row3:
  - image_path: /assets/images/ibu2.webp
    alt: ""
    title: ""
    excerpt: ""
    url: "/album/"
    btn_label: ""
    btn_class: "btn--inverse"  
feature_row4:
  - image_path: /assets/images/ibu.webp
    alt: "a"
    title: ""
    excerpt: ""
    url: "http://www.ibu.edu.tr/tr"
    btn_label: ""
    btn_class: "btn--inverse"
    image_filter: rgba(134, 163, 184, 0.8)
feature_row5:
  - image_path: /assets/images/media.jpeg
    alt: ""
    title: ""
    excerpt: ""
    url: "/media"
    btn_label: ""
    btn_class: "btn--inverse"
    image_filter: rgba(134, 163, 184, 0.8)
---

{% include feature_row %}

<!-- {% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row4" type="right" %}
{% include feature_row id="feature_row3" type="left" %} -->
<!--{% include feature_row id="feature_row2" type="right" %} -->

## Güncel Haberler

<div class="grid__wrapper">
{% for post in site.posts limit: 8 %}
  {% include archive-single.html type="grid"  %}
{% endfor %}
</div>


<!-- {% include feature_row id="feature_row5" type="center" %} -->
