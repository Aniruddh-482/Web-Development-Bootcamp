# Intermediate Bootstrap

### Bootstrap Carousel
` A slideshow component for cycling through elements—images or slides of text—like a carousel. `
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
`Change interval speed of sliding animation and add hover effect (pause sliding)`
```
  <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel" data-bs-interval="1000" data-bs-pause="hover">
```
