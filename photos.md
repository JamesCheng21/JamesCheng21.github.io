---
layout: page
---

<div class="photo-gallery-wrapper">
  <button class="gallery-nav left" onclick="scrollGallery(-1,'photoGallery_uk')">&#10094;</button>

  <div class="photo-gallery" id="photoGallery_uk">
    {% for item in site.data.photos_uk %}
      <img src="{{ item.src | relative_url }}">
    {% endfor %}
  </div>

  <button class="gallery-nav right" onclick="scrollGallery(1,'photoGallery_uk')">&#10095;</button>
</div>
<h6 style="text-align: center;">UK</h6>

<div class="photo-gallery-wrapper">
  <button class="gallery-nav left" onclick="scrollGallery(-1,'photoGallery_bos')">&#10094;</button>

  <div class="photo-gallery" id="photoGallery_bos">
    {% for item in site.data.photos_boston %}
      <img src="{{ item.src | relative_url }}">
    {% endfor %}
  </div>

  <button class="gallery-nav right" onclick="scrollGallery(1,'photoGallery_bos')">&#10095;</button>
</div>
<h6 style="text-align: center;">Boston</h6>

<div class="photo-gallery-wrapper">
  <button class="gallery-nav left" onclick="scrollGallery(-1,'photoGallery_WM')">&#10094;</button>

  <div class="photo-gallery" id="photoGallery_WM">
    {% for item in site.data.photos_white %}
      <img src="{{ item.src | relative_url }}">
    {% endfor %}
  </div>

  <button class="gallery-nav right" onclick="scrollGallery(1,'photoGallery_WM')">&#10095;</button>
</div>
<h6 style="text-align: center;">White mountain</h6>



<script>
function scrollGallery(direction, id='photoGallery') {
  const gallery = document.getElementById(id);
  const scrollAmount = gallery.clientWidth * 0.8;
  gallery.scrollBy({
    left: direction * scrollAmount,
    behavior: 'smooth'
  });
}
</script>