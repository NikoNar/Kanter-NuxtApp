<template>
<div>
  <nav class="navbar navbar-light bg-white">
    <div class="container">
      
      
      <button class="menu-button" data-bs-toggle="modal" data-bs-target="#staticBackdrop" onclick="this.classList.toggle('opened');this.setAttribute('aria-expanded', this.classList.contains('opened'))" aria-label="Main Menu">
        <svg width="50" height="50" viewBox="0 0 100 100">
          <path class="line line1" d="M 20,29.000046 H 80.000231 C 80.000231,29.000046 94.498839,28.817352 94.532987,66.711331 94.543142,77.980673 90.966081,81.670246 85.259173,81.668997 79.552261,81.667751 75.000211,74.999942 75.000211,74.999942 L 25.000021,25.000058" />
          <path class="line line2" d="M 20,50 H 80" />
          <path class="line line3" d="M 20,70.999954 H 80.000231 C 80.000231,70.999954 94.498839,71.182648 94.532987,33.288669 94.543142,22.019327 90.966081,18.329754 85.259173,18.331003 79.552261,18.332249 75.000211,25.000058 75.000211,25.000058 L 25.000021,74.999942" />
        </svg>
      </button>

      

      <a class="navbar-brand mx-auto" href="#"><img src="~assets/images/logo.svg" /></a>


      <button type="button ms-auto" class="btn btn-black">BOOKING</button>



    </div>
  </nav>

  <!-- Modal -->
  <div class="modal" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
    <div class="modal-dialog modal-fullscreen">
      <div class="modal-content bg-dark">
        <div class="container">

          <div class="modal-header p-0 py-2 border-0">

            <a class="navbar-brand mx-auto" href="#"><img src="~assets/images/logo-w.svg" /></a>
            
            <button type="button" class="btn btn-white">LOG IN / SIGN UP</button>
            
          </div>
          <div class="modal-body">

            <ul class="nav flex-column">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Active</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
              </li>
            </ul>

          </div>
        </div>
      </div>
    </div>
  </div>


</div>
</template>

<script>
    export default {
        
    }
</script>


<style lang="scss" scoped>

@import '~/assets/scss/style.scss';

</style>