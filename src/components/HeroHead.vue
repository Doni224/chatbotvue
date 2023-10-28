<template>
 <div class="id">
    <div data-aos="fade-up" data-aos-duration="1000" id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
        
      <img src="../assets/img/Group 1.png" class="d-block w-0 h-10" alt="..."  >
      <div class="carousel-caption ">
        <p>Temukan Informasi Dengan Mudah Melalui</p>
        <h3>Virtual Assistant</h3>
        <button type="button" class="btn btn-danger btn-lg">Mulai Chat</button>
      </div>
    </div>
    <div  class="carousel-item">
      <img src="../assets/img/slid2.png" class="d-block w-0 h-10" alt="...">
      <div class="carousel-caption " > 
        <p>Temukan Informasi Dengan Mudah Melalui</p>
        <h3>Virtual Assistant</h3>
        <button type="button" class="btn btn-danger btn-lg">Mulai Chat</button>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/img/slid3.png" class="d-block w-0 h-10" alt="...">
      <div class="carousel-caption ">
        <p>Temukan Informasi Dengan Mudah Melalui</p>
        <h3>Virtual Assistant</h3>
        <button type="button" class="btn btn-danger btn-lg">Mulai Chat</button>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
 </div>
</template>

<script>
export default {
name: "HeroHead",
}
</script>

<style>
.carousel-caption {
  position: absolute;
  top: 40%;
 
  padding: 10px; /* Padding di sekitar teks */
  border-radius: 5px; /* Ganti sesuai kebutuhan Anda */
}
.carousel-caption p{
  font-size: 38px;
  font-family: "Roboto", sans-serif;
}
.carousel-caption h3{
font-size: 42px;
font-family: "Lato",sans-serif;
font-weight: 600;
}
@media (max-width: 568px) {
  .carousel-caption {
    top: 20%; /* Sesuaikan dengan posisi vertikal yang sesuai untuk layar berukuran kecil */
    position: absolute;
  text-align: center;
  padding: 10px; /* Padding di sekitar teks */
  border-radius: 5px; /* Ganti sesuai kebutuhan Anda */
  }
}
@media (max-width: 400px) {
  .d-block{
    height: 50vh;
  }
  .carousel-caption p{
    font-size: 30px;
  }
  .carousel-caption h3{
    font-size:30px;
  }

}
</style>