
<template>
  <hr>
  <section id="footer">
    <div class="footer container">
      <div class="nama">
      
      </div>
      <h2>Muhammad Dzaki Fakhrezi </h2>
      <p>Copyright © 2023 Dzaki. All rights reserved</p>
      <div id="medsos" class="social-icon">
        <div class="social-item">
          <a href="https://api.whatsapp.com/send/?phone=%2B628999234378&text&type=phone_number&app_absent=0"><img src="https://img.icons8.com/bubbles/100/000000/whatsapp.png" /></a>
        </div>
        <div class="social-item">
          <a href="https://www.instagram.com/rezi_trix/"><img src="https://img.icons8.com/bubbles/100/000000/instagram.png" /></a>
        </div>
        <div class="social-item">
          <a href="https://www.tiktok.com/@izerbetter"><img src="https://img.icons8.com/bubbles/100/000000/tiktok.png" /></a>
        </div>
        
      </div>
       
    </div>
  </section>
  
 
 
</template>

<script>

</script>


<style>

#footer {
	background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);

  
}



#footer .footer {
	min-height: 200px;
	flex-direction: column;
	padding-top: 50px;
	padding-bottom: 10px;
}
#footer h2 {
	color: white;
	font-weight: 500;
	font-size: 1.8rem;
	letter-spacing: 0.1rem;
	margin-top: 10px;
	margin-bottom: 10px;
}
#footer .social-icon {
	display: flex;
	margin-bottom: 30px;
}
#footer .social-item {
	height: 50px;
	width: 50px;
	margin: 0 5px;
  
}
#footer .social-item img {
	filter: grayscale(1);
	transition: 0.3s ease filter;
}
#footer .social-item:hover img {
	filter: grayscale(0);
}
#footer p {
	color: white;
	font-size: 1.3rem;
}
.hr{
  color: blue;
}
#footer {
  text-align: center;
}


</style>
