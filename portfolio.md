---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<!-- Page Content -->
{% include spacer.html %}
<div class="container">
<h2 class="mb-3">Illustration</h2><a id="illustration"></a>
  <div class="card-columns">
    {% for work in site.data.illustration %}<div class="card">
        <a href="../assets/portfolio/{{ work.file }}" data-toggle="lightbox" data-max-width="800" data-max-height="800" data-gallery="illustration" data-footer="{{ work.info }}">
        <img class="card-img" src="../assets/portfolio/{{ work.file }}" alt="Card image">
        <div class="card-img-overlay d-flex">
        </div>
      </a>
    </div>{% endfor %}
  </div>
</div>
<div class="container mb-5">
<hr>
</div>
<div class="container">
<h2 class="mb-3">Graphic Design</h2><a id="graphicdesign"></a>
  <div class="card-columns">
    {% for work in site.data.graphicdesign %}<div class="card">
        <a href="../assets/portfolio/{{ work.file }}" data-toggle="lightbox" data-max-width="800" data-max-height="800" data-gallery="graphicdesign" data-footer="{{ work.info }}">
        <img class="card-img" src="../assets/portfolio/{{ work.file }}" alt="Card image">
        <div class="card-img-overlay d-flex">
        </div>
      </a>
    </div>{% endfor %}
  </div>
</div>
<div class="container my-5">
<hr>
</div>