<template>
  <div>
    
    <div class=" kontak d-flex align-items-center">
        <img src="@/assets/Icons/email.png" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
        <p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">0857-1320-7547</p>
        
    </div>
    <div class="div d-flex align-items-center">
      <img src="@/assets/Icons/email.png" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="50"/>
        <p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="100">PartnerJalan@gmail.com</p>
    </div>
  </div>
</template>

<script>
export default {
   
  name: "KontakUs",
  props: ["kontakus"],
  
}
</script>

<style>
.kontak img{
  width: 42px;
  height: 42px;

}
.kontak p{
  margin-left: 10px;
  padding: 10px 0px 0px 0px;
}
</style>