<template>
    <div>
         <!-- Google Tag Manager (noscript)-->
    <noscript>
      <iframe src="http://www.googletagmanager.com/ns.html?id=GTM-WKV3GT5" height="0" width="0" style="display: none; visibility: hidden;"></iframe>
    </noscript>
    <!-- Demo switcher (offcanvas)-->
    <button class="btn btn-icon btn-light rounded-circle shadow position-fixed top-50 end-0 translate-middle-y me-3" type="button" data-bs-toggle="tooltip" data-bs-placement="left" title="Choose Demo" style="z-index: 1035;"><span class="d-flex align-items-center justify-content-center position-absolute top-0 start-0 w-100 h-100 rounded-circle" data-bs-toggle="offcanvas" data-bs-target="#demo-switcher"><i class="fi-layers"></i></span></button>
      <div class="offcanvas offcanvas-end" id="demo-switcher">
        <div class="offcanvas-header d-block border-bottom">
          <div class="d-flex align-items-center justify-content-between mb-4">
            <h2 class="h5 mb-0">Choose Demo</h2>
            <button class="btn-close" type="button" data-bs-dismiss="offcanvas"></button>
          </div>
          <div class="d-flex"><a class="btn btn-outline-secondary btn-sm w-100 me-2" href="index.html"><i class="fi-home me-2"></i>Main Page</a><a class="btn btn-outline-secondary btn-sm w-100" href="components/typography.html"><i class="fi-file me-2"></i>Docs / UI Kit</a></div>
        </div>
        <div class="offcanvas-body">
          <div class="card card-hover shadow-sm mb-4"><img class="card-img-top" src="../../img/intro/demos/offcanvas/car-finder.jpg" alt="Car Finder Demo">
            <div class="card-body p-3">
              <h3 class="fs-base card-title text-center"><a class="nav-link stretched-link" href="car-finder-home.html">Car Finder Demo</a></h3>
            </div>
          </div>
          <div class="card card-hover shadow-sm mb-4"><img class="card-img-top" src="../../img/intro/demos/offcanvas/real-estate.jpg" alt="Real Estate Demo">
            <div class="card-body p-3">
              <h3 class="fs-base card-title text-center"><a class="nav-link stretched-link" href="real-estate-home-v1.html">Real Estate Demo</a></h3>
            </div>
          </div>
          <div class="card card-hover shadow-sm mb-4"><img class="card-img-top" src="../../img/intro/demos/offcanvas/job-board.jpg" alt="Job Board Demo">
            <div class="card-body p-3">
              <h3 class="fs-base card-title text-center"><a class="nav-link stretched-link" href="job-board-home-v1.html">Job Board Demo</a></h3>
            </div>
          </div>
          <div class="card card-hover shadow-sm mb-4"><img class="card-img-top" src="../../img/intro/demos/offcanvas/city-guide.jpg" alt="City Guide Demo">
            <div class="card-body p-3">
              <h3 class="fs-base card-title text-center"><a class="nav-link stretched-link" href="city-guide-home-v1.html">City Guide Demo</a></h3>
            </div>
          </div>
        </div>
        <div class="offcanvas-header border-top"><a class="btn btn-primary btn-lg w-100" href="https://themes.getbootstrap.com/product/finder-directory-listings-template-ui-kit/" target="_blank" rel="noopener"><i class="fi-cart fs-lg me-2"></i>Buy Finder</a></div>
      </div>
    <!-- Page loading spinner-->
    <div class="page-loading active">
      <div class="page-loading-inner">
        <div class="page-spinner"></div><span>Loading...</span>
      </div>
    </div>
        <main class="page-wrapper">
      <!-- Sign In Modal-->
      <div class="modal fade" id="signin-modal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-lg modal-dialog-centered p-2 my-0 mx-auto" style="max-width: 950px;">
          <div class="modal-content bg-dark border-light">
            <div class="modal-body px-0 py-2 py-sm-0">
              <button class="btn-close btn-close-white position-absolute top-0 end-0 mt-3 me-3" type="button" data-bs-dismiss="modal"></button>
              <div class="row mx-0 align-items-center">
                <div class="col-md-6 border-end-md border-light p-4 p-sm-5">
                  <h2 class="h3 text-light mb-4 mb-sm-5">Hey there!<br>Welcome back.</h2><img class="d-block mx-auto" src="../../img/signin-modal/signin-dark.svg" width="344" alt="Illustartion">
                  <div class="text-light mt-4 mt-sm-5"><span class="opacity-60">Don't have an account? </span><a class="text-light" href="#signup-modal" data-bs-toggle="modal" data-bs-dismiss="modal">Sign up here</a></div>
                </div>
                <div class="col-md-6 px-4 pt-2 pb-4 px-sm-5 pb-sm-5 pt-md-5"><a class="btn btn-outline-info w-100 mb-3" href="#"><i class="fi-google fs-lg me-1"></i>Sign in with Google</a><a class="btn btn-outline-info w-100 mb-3" href="#"><i class="fi-facebook fs-lg me-1"></i>Sign in with Facebook</a>
                  <div class="d-flex align-items-center py-3 mb-3">
                    <hr class="hr-light w-100">
                    <div class="text-light opacity-70 px-3">Or</div>
                    <hr class="hr-light w-100">
                  </div>
                  <form class="needs-validation" novalidate>
                    <div class="mb-4">
                      <label class="form-label text-light mb-2" for="signin-email">Email address</label>
                      <input class="form-control form-control-light" type="email" id="signin-email" placeholder="Enter your email" required>
                    </div>
                    <div class="mb-4">
                      <div class="d-flex align-items-center justify-content-between mb-2">
                        <label class="form-label text-light mb-0" for="signin-password">Password</label><a class="fs-sm text-light" href="#">Forgot password?</a>
                      </div>
                      <div class="password-toggle">
                        <input class="form-control form-control-light" type="password" id="signin-password" placeholder="Enter password" required>
                        <label class="password-toggle-btn" aria-label="Show/hide password">
                          <input class="password-toggle-check" type="checkbox"><span class="password-toggle-indicator"></span>
                        </label>
                      </div>
                    </div>
                    <button class="btn btn-primary btn-lg w-100" type="submit">Sign in         </button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Sign Up Modal-->
      <div class="modal fade" id="signup-modal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-lg modal-dialog-centered p-2 my-0 mx-auto" style="max-width: 950px;">
          <div class="modal-content bg-dark border-light">
            <div class="modal-body px-0 py-2 py-sm-0">
              <button class="btn-close btn-close-white position-absolute top-0 end-0 mt-3 me-3" type="button" data-bs-dismiss="modal"></button>
              <div class="row mx-0 align-items-center">
                <div class="col-md-6 border-end-md border-light p-4 p-sm-5">
                  <h2 class="h3 text-light mb-4 mb-sm-5">Join Finder.<br>Get premium benefits:</h2>
                  <ul class="list-unstyled mb-4 mb-sm-5">
                    <li class="d-flex mb-2"><i class="fi-check-circle text-primary mt-1 me-2"></i><span class="text-light">Add and promote your listings</span></li>
                    <li class="d-flex mb-2"><i class="fi-check-circle text-primary mt-1 me-2"></i><span class="text-light">Easily manage your wishlist</span></li>
                    <li class="d-flex mb-0"><i class="fi-check-circle text-primary mt-1 me-2"></i><span class="text-light">Leave reviews</span></li>
                  </ul><img class="d-block mx-auto" src="../../img/signin-modal/signup-dark.svg" width="344" alt="Illustartion">
                  <div class="text-light mt-sm-4 pt-md-3"><span class="opacity-60">Already have an account? </span><a class="text-light" href="#signin-modal" data-bs-toggle="modal" data-bs-dismiss="modal">Sign in</a></div>
                </div>
                <div class="col-md-6 px-4 pt-2 pb-4 px-sm-5 pb-sm-5 pt-md-5"><a class="btn btn-outline-info w-100 mb-3" href="#"><i class="fi-google fs-lg me-1"></i>Sign in with Google</a><a class="btn btn-outline-info w-100 mb-3" href="#"><i class="fi-facebook fs-lg me-1"></i>Sign in with Facebook</a>
                  <div class="d-flex align-items-center py-3 mb-3">
                    <hr class="hr-light w-100">
                    <div class="text-light opacity-70 px-3">Or</div>
                    <hr class="hr-light w-100">
                  </div>
                  <form class="needs-validation" novalidate>
                    <div class="mb-4">
                      <label class="form-label text-light" for="signup-name">Full name</label>
                      <input class="form-control form-control-light" type="text" id="signup-name" placeholder="Enter your full name" required>
                    </div>
                    <div class="mb-4">
                      <label class="form-label text-light" for="signup-email">Email address</label>
                      <input class="form-control form-control-light" type="email" id="signup-email" placeholder="Enter your email" required>
                    </div>
                    <div class="mb-4">
                      <label class="form-label text-light" for="signup-password">Password <span class='fs-sm opacity-50'>min. 8 char</span></label>
                      <div class="password-toggle">
                        <input class="form-control form-control-light" type="password" id="signup-password" minlength="8" required>
                        <label class="password-toggle-btn" aria-label="Show/hide password">
                          <input class="password-toggle-check" type="checkbox"><span class="password-toggle-indicator"></span>
                        </label>
                      </div>
                    </div>
                    <div class="mb-4">
                      <label class="form-label text-light" for="signup-password-confirm">Confirm password</label>
                      <div class="password-toggle">
                        <input class="form-control form-control-light" type="password" id="signup-password-confirm" minlength="8" required>
                        <label class="password-toggle-btn" aria-label="Show/hide password">
                          <input class="password-toggle-check" type="checkbox"><span class="password-toggle-indicator"></span>
                        </label>
                      </div>
                    </div>
                    <div class="form-check form-check-light mb-4">
                      <input class="form-check-input" type="checkbox" id="agree-to-terms" required>
                      <label class="form-check-label" for="agree-to-terms"><span class='opacity-70'>By joining, I agree to the</span> <a href='#' class='text-light'>Terms of use</a> <span class='opacity-70'>and</span> <a href='#' class='text-light'>Privacy policy</a></label>
                    </div>
                    <button class="btn btn-primary btn-lg w-100" type="submit">Sign up         </button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Navbar-->
        <TheNavBar/>
      <!-- Page content-->
        <TheSection/>
     

    </main>
    </div>
</template>
<script lang="ts" setup>
    import TheNavBar from "./TheNavBar.vue"
    import TheSection from "./TheSection.vue"
</script>