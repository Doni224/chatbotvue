<template>
  <div class="koleksi">
    <NavbarBaru/>
    <div class="container">
      <div class="row">
        <div class="col-sm" style="margin-top: 130px;">
          <h2 class="text-center loki" data-aos="fade-down" data-aos-duration="1000">Mau cari koleksi apa?</h2>
          <div class="searchWisata">
            <div class="aki col" data-aos="fade-down" data-aos-duration="1000" data-aos-delay="50">
              <div class="input-group mb-3 ">
                <input
                  type="text"
                  v-model="search"
                  class="form-control"
                  placeholder="Cari koleksi anda"
                  aria-label="Cari"
                  aria-describedby="button-addon2 "
                />
                <span
                  class="btn btn-outline-secondary"
                  type="button"
                  id="button-addon2"
                  @click="searchWisata"
                >
                  <b-icon-search></b-icon-search>
                  Cari
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div data-aos="fade-up" data-aos-duration="1000" class="container-fluid-dk jarak-klk ">
      <article data-aos="fade-down" data-aos-duration="1000" class="cta">
	<img class="gbr-koleksi"  src='../assets/img/gigi.jpg' alt='Bluetit'>
	<div class="cta__text-column">
		<h2 class="nama-koleksiku">Gigi-Gigi Hiu</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
		<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio"> <button type="button" class="btn btn-danger btn-sm">Lihat Selengkapnya</button>
      </a>
	</div>
</article>

<article data-aos="fade-down" data-aos-duration="1000" class="cta ">
	<img class="gbr-koleksi" src='../assets/img/kapak.jpg' alt='Small blue-grey yellow-breasted bird'>
	<div class="cta__text-column">
		<h2 class="nama-koleksiku">Kapak Batu</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
		<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio"> <button type="button" class="btn btn-danger btn-sm">Lihat Selengkapnya</button>
      </a>
	</div>
</article>
<article data-aos="fade-down" data-aos-duration="1000" class="cta ">
	<img class="gbr-koleksi" src='../assets/img/tengkorak.jpg' alt='Small blue-grey yellow-breasted bird'>
	<div class="cta__text-column">
		<h2 class="nama-koleksiku">Kepala Kerbau</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
		<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/aspect-ratio"> <button type="button" class="btn btn-danger btn-sm">Lihat Selengkapnya</button>
      </a>
	</div>
</article>
      </div>


  </div>
  
</template>
<script>
import NavbarBaru from '@/components/NavbarBaru.vue'
export default{
  name: "KoleksiView",
  components:{
    NavbarBaru
  },
  data() {
    return {
      wisataSemua:[],
      
      search: '',

    };
  },
 
  props: ["wisata"],
}
</script>
<style>
.koleksi {
	font-family: "Open Sans", sans-serif;
	min-height: 100vh;
	display: flex;
	flex-direction: column;
	gap: 0rem;
	justify-content: center;
	align-items: center;
	background: #f1f1f1;
}



.cta .gbr-koleksi {
	display: block;
	width: 100%;
  gap: 4rem;
}

.cta__text-column .nama-koleksiku {
	margin: 0;
	font-size: 1.4rem;
}

@media (min-width: 50em) {
	.cta__text-column .nama-koleksiku {
		font-size: 1.8rem;
	}
}

.cta {
	--shadowColor: 187 60% 40%;
	display: flex;
	flex-wrap: wrap;
	background: hsl(0, 0%, 100%);
	max-width: 50rem;
	width: 100%;
	/* box-shadow: 0.65rem 0.65rem 0 hsl(var(--shadowColor) / 1); */
	border-radius: 0.8rem;
  box-shadow: 3px 3px 10px 2px rgba(0,0,0,0.75);
	overflow: hidden;
	border: 0.5rem solid;
}

.cta .gbr-koleksi {
	aspect-ratio: 3 / 2;
	object-fit: cover;
	flex: 1 1 300px;
	outline: 0.5rem solid;
}

.cta__text-column {
	padding: min(2rem, 5vw) min(2rem, 5vw) min(2.5rem, 5vw);
	flex: 1 0 50%;
}

.cta__text-column > * + * {
	margin: min(1.5rem, 2.5vw) 0 0 0;
}

.cta .btn-kolek {
	display: inline-block;
	color: black;
	padding: 0.5rem 1rem;
	text-decoration: none;
	background: hsl(187 75% 64%);
	border-radius: 0.6rem;
	font-weight: 700;
	border: 0.35rem solid;
}
</style>