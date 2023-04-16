<template>
    <!--banner image-->
    
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
        <div class="content text-start">
            <h1 class="text-white">Welcome To My Website!!</h1>
        </div>
        <div class = "col-lg-5">
          <img src="../assets/cansss.jpg" class="img-fluid">

        </div>
    </div>



    <!--kontent-->
    <section id = "sec-4" class = "py-5">
        <div class = "container my-4">
            <div class = "row gx-lg-5">
                <div class = "col-lg-6 mb-5">
                     <h3>Sedikit Tentang Saya</h3>
                    <p class = "text-muted fw-light lh-lg my-4">Nama saya Lusi Diah Wiranti, biasa dipanggil Lusi. Saat ini saya menjadi mahasiswa di salah satu universitas yang ada di Pekanbaru,yaitu Universitas Islam Negeri Sultan Syarif Kasim Riau. </p>

                    <button type = "button" class = "btn btn-green mt-2"><router-link to="/about">More About Me</router-link></button>
                </div>
                <div class = "col-lg-6">
                    <img src = "../assets/hailus.png" class = "img-fluid">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
.banner-image {
    background-color: rgba(171, 102, 102, 0.62);
}

.col-lg-5{
  margin-top: 300px;
  height: 600px;
  margin-bottom: 300px;
  margin-right: -300px;
}
</style>
