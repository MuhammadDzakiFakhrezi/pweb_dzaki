<template>
  <header>

    <div id="kedua" class="page-banner home-banner">
      <div class="container h-100 background">
        <div class="row align-items-center h-100">
          <div class="col-lg-6 py-3 wow fadeInUp">
            <p id="text"
              class="text-yellow-600 hover:text-yellow-500 text-2xl lg:text-4xl font-medium lg:font-semibold mb-5 lg:leading-normal leading-snug">
              <div id="test">
               Hi, guys    ,,,,,,
               <br/>
               Kenalin
              <br />
              Nama Aku,
              <br />
              Dzaki
              </div>
            </p>
            <p
              class="hidden lg:block text-2xl mb-5">
               Aku mahasiswa Universitas Islam Negeri Sultan Syarif Kasim Riau dengan Prodi Teknik Informatika
            </p>

            <router-link
              to="/about"
              name="fade"
              id="initentang" class="btn btn-outline border text-secondary">
              About
            </router-link>
            <a
              href="https://drive.google.com/file/d/1FaiPHNEKFIXfyp2hhYzmyw0wcfFZuAFY/view?usp=share_link"
              id="ini" class="btn btn-primary btn-split ml-2">
              CV Saya
              <div class="fab"><span class="mai-play"></span></div>
            </a>
          </div>
          <div class="col-lg-6 wow zoomIn">
            <div id="gambarku"
              class="m-3 lg:m-1 p-4 lg:p-5">
            
                <img src="../images/dua.jpg"
                background="transparent"
                style="max-width: 500px; max-height: 500px"
                >
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import { directive as motion } from "@vueuse/motion";

export default {};
</script>

<style>

#gambarku{
  margin-left: auto;
}

#kedua{
  background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);
}

#initentang{
background-color: white;
}

#ini{
  background-color: black;
}


#text{ display: inline-block;

}
#test{
  color: black;
  font-size: 2rem;
  letter-spacing: 10px;
  font-family: monospace;
  border-right: 5px solid;
  width: 60%;
  white-space: nowrap;
  overflow: hidden;
  animation: 
           typing 2s steps(8),
           cursor .4s step-end infinite alternate;

}


  @keyframes cursor {
         50% { border-color: transparent}
    
  }

  @keyframes typing {
          from { width:0}
  }
    
 

</style>
