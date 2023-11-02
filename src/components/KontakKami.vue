<template>
<div class="id  bg-kontak " data-aos="fade-up" data-aos-duration="1000">
    <div class="container-fluid"></div>
    
    <div class="kontakL row py-5">
      <div class="col-sm-6 col-12 kont " style="color: white;">
      
        <h3 class="title-hubungi" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50">Kontak Kami</h3>
       
       <div class=" kontak d-flex align-items-center ">
        <img src="../assets/Icons/phone.png" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
        <p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">0857-1320-7547</p>
        
    </div>
    <div class="kontak d-flex align-items-center">
      <img src="../assets/Icons/email.png" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
        <p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100"> museumsemedo@kemdikbud.go.id</p>
    </div>
      </div>
      <div data-aos="fade-up" data-aos-duration="1000" class="col-sm-6 col-12 kontak2" style="color: white; ">
        <h3 class="title-hubungi" style="text-align: center;" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50">Media Sosial</h3>
        <div class="row">
          <div class="col-md-5 " >
            <div class="align-items-center d-flex kontak">
              <img class="medsos" src="../assets/Icons/instagram.png" alt="" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
              <p  style="width:auto;" class="" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">@museumsemedo</p>
            </div>
            <div class="align-items-center d-flex kontak">
              <img class="medsos" src="../assets/Icons/facebook.png" alt="" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
              <p  style="width:auto;" class="" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">MuseumSemedo</p>
            </div>
          </div> 
          </div>
      </div>
    </div>
</div>
</template>

<script>
// import KontakUs from "./Kontak/KontakUs.vue";
// import MediaSosial from "./Kontak/MediaSosial.vue";
export default {
    // components: {  MediaSosial },
name: "KontakKami"

};
</script>

<style>
.bg-kontak{
    background-color: #232222;
    height: 50vh;
}
.kontak{
  padding: 10px 90px;
}
.heading-kontak{
  font-family: 'Lato', sans-serif;
  font-weight: bold;
  line-height: 43px;
  font-style: normal;
}
.title-kontak{
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
}
.title-hubungi{
    font-family: 'Lato', sans-serif;
    font-weight: bold;
    font-size: 24px;
  }
  .kontak img{
  width: 42px;
  height: 42px;

}
.kontak p{
  margin-left: 10px;
  padding: 10px 0px 0px 0px;
}
@media only screen and (max-width: 430px) {
  .kontak{
  padding: 10px 50px;
}
}
</style>