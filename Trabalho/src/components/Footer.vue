<template>
    <footer class="footer">
      <div class="footer-container">
        <div class="footer-description">
          <p>&copy; 2024 Notícias de Futebol. Todos os direitos reservados.</p>
          <p>Fique por dentro das últimas notícias, análises e resultados do futebol mundial.</p>
        </div>
        <div class="footer-social">
          <a href="https://www.facebook.com" target="_blank" class="social-link">Facebook</a>
          <a href="https://twitter.com" target="_blank" class="social-link">Twitter</a>
          <a href="https://www.instagram.com" target="_blank" class="social-link">Instagram</a>
          <a href="https://www.youtube.com" target="_blank" class="social-link">YouTube</a>
        </div>
      </div>
      
      <div class="media">
           
           <li>
               <a herf="#"><i class="fab fa-facebook-f"></i> </a>
           </li>
              
           <li>
               <a herf="#"><i class="fa-brands fa-x-twitter"></i> </a>
           </li>

           <li>
               <a herf="#"><i class="fab fa-instagram"></i> </a>
           </li>          
     
           <li>
               <a herf="#"><i class="fab fa-youtube"></i> </a>
           </li>
      
     </div>


    </footer>
  </template>

  <script>
  export default {
    name: 'FooterComponent'
  }
  </script>

  <style scoped>
  .footer {
    background-color: #ffffff;
    color: #000000;
    padding: 20px 0;
    text-align: center;
  }

  .footer-container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .footer-description p {
    margin: 5px 0;
  }

  .media{
  height: 100%;
  display: flex;
  /* margin-right: 290px; */
   align-items: center;
  justify-content: center;
  
  
}

.media li{
    list-style:none;
    margin: 32px;
}

/* .header-social-media-twitter ul{
  height: 100%;
  display: flex;
  margin-right: 105px;
  align-items: center;
  justify-content: center; 
}

.header-social-media-instagram ul{
  height: 100%;
  display: flex;
  margin-left: 30px;
  align-items: center;
  justify-content: center; 
}

.header-social-media-youtube ul{
  height: 100%;
  display: flex;
  margin-left: 200px;
  align-items: center;
  justify-content: center; 
} */

  .footer-social {
    margin-top: 15px;
  }

  .social-link {
    margin: 0 10px;
    color: #000000;
    text-decoration: none;
    font-weight: bold;
  }

  .social-link:hover {
    color: #ffffff;
  }

  .fa-facebook-f:hover{
    color: #ffffff;
  }
  .fa-x-twitter:hover{
    color: #ffffff;
  }
  .fa-instagram:hover{
    color: #ffffff;
  }
  .fa-youtube:hover{
    color: #ffffff;
  }
  </style>
