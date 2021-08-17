# Intermediate Bootstrap

### Bootstrap Carousel
> `A slideshow component for cycling through elements—images or slides of text—like a carousel.`
```
  <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="..." class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="..." class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="..." class="d-block w-100" alt="...">
      </div>
    </div>
  </div>
```

> `The amount of time to delay between automatically cycling an item. If false, carousel will not automatically cycle.`
```
  <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel" data-bs-interval="1000">
```

> `If set to 'hover', pauses the cycling of the carousel on mouseenter and resumes the cycling of the carousel on mouseleave. If set to false, hovering over the carousel won't pause it.`
```
  <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel" data-bs-interval="1000" data-bs-pause="hover">
```

> `	Autoplays the carousel after the user manually cycles the first item. If set to 'carousel', autoplays the carousel on load.`
```
  <div id="testimonial-carousel" class="carousel slide" data-bs-ride="false">
```



