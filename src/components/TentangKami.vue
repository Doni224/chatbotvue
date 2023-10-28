<template>
  <div data-aos="fade-up" data-aos-duration="1000" class="id tentang"  >
    <div class=" container  ">
        <div class="row">
            <div class="col-6 py-5">
                <h3 class="mb-3" style="color:white;">Tentang Kami <hr> </h3>
            </div>
    </div>
    <div class="row">
        <div class="col-7 py">
            <h3 class="judulkami bg-">Museum Semedo</h3>
            <p class="tekskami">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus similique mollitia velit, voluptatum ad corrupti voluptate sequi dicta beatae? Maiores magni illum eius adipisci. Quia officiis earum qui consectetur rem.</p>
            <a href="#" class="btn btn-danger" style="float: left;">Lihat Selengkapnya</a>
        </div>
        <div class="col-md-5">
            <img class="gbr" src="../assets/img/semedo.jpg" alt="">
        </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
name: "TentangKami"
}
</script>

<style>
.tentang{
    background-color: #232222;
}
.judulkami{
    color: white;
    font-size: 40px;
    font-family: Lato'sans-serif';
    font-weight: 400;
}
.tekskami{
    color: white;
    text-align: start;
    padding-top: 30px;
}
@media only screen and (max-width: 420px) {
.gbr{
    width: 360px;
    padding-top: 30px;
}
.judulkami{
    margin-top: 0px;
    width: 360px;
    font-size: 30px;
}
.tekskami{
    width: 360px;
}
}
</style>