<script type="text/javascript">
  import Hero from './Hero.svelte'
  import Footer from './Footer.svelte'

  let title = "Genus is a model with realistic clinical potential for automated diabetic retinopathy screening using image recognition, pattern recognition and machine learning using colour fundus photographs as input."
</script>

<Hero title = {title} />

      <div class="site-section" id="about-section">

        <div class="container">
          <div class="row mb-5 justify-content-center">
            <div class="col-md-7 text-center">
              <div class="block-heading-1" data-aos="fade-up" data-aos-delay="">
                <h2>About</h2>
                <p>Genus is a model with realistic clinical potential for automated diabetic retinopathy screening using image recognition, pattern recognition and machine learning using colour fundus photographs as input.</p>
              </div>
            </div>
          </div>
        </div>

              <div class="block__73694 site-section border-top" id="why-us-section">
        <div class="container">
          <div class="row d-flex no-gutters align-items-stretch">

            <div class="col-lg-5 mr-auto p-lg-5 mt-4 mt-lg-0 order-lg-1" data-aos="fade-right" data-aos-delay="">
              <form action="" method="POST" enctype="multipart/formdata">
                <div class="form-group row">
                  <div class="col-md-12 mb-4 mb-lg-0">
                    <input type="file" class="form-control" placeholder="Name" name="file">
                  </div>
                </div>

                <div class="form-group row">
                  <div class="col-md-6 mr-auto">
                    <input type="submit" class="btn btn-block btn-primary text-white py-3 px-5" value="Classify">
                  </div>
                </div>
            </form>

            </div>
            
            <div class="col-12 col-lg-6 block__73422 order-lg-2" data-aos="fade-left" data-aos-delay="">
              <p class="lead-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
            </div>

          </div>
        </div>
      </div>

      </div>


            <div class="site-section bg-light" id="services-section">
        <div class="container">
          <div class="row mb-5 justify-content-center">
            <div class="col-md-7 text-center">
              <div class="block-heading-1">
                <h2>Why Genus</h2>
              </div>
            </div>
          </div>
          <div class="owl-carousel owl-all">
            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-ferry"></span>
              </div>
              <h3 class="mb-3">Accessibility</h3>
              <p>Genus is easily accessible over the internet on the web. </p>
            </div>

            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-airplane"></span>
              </div>
              <h3 class="mb-3">Ease of use</h3>
              <p>Genus is very easy to use. Just upload your fondus image and click classify </p>
            </div>

            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-box"></span>
              </div>
              <h3 class="mb-3">Accuracy</h3>
              <p>Genus effectively achieve a high accuracy of 72.6%. </p>
            </div>

            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-lorry"></span>
              </div>
              <h3 class="mb-3">Light weight</h3>
              <p>The Genus network is a light one compared to other approaches. </p>
            </div>

            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-warehouse"></span>
              </div>
              <h3 class="mb-3">Performance</h3>
              <p>Genus is very fast in detecting retinopathy in retinal images. </p>
            </div>

            <div class="block__35630">
              <div class="icon mb-0">
                <span class="flaticon-add"></span>
              </div>
              <h3 class="mb-3">low latency</h3>
              <p>Genus is able to make inference using minimal computing power. </p>
            </div>

          </div>
        </div>
      </div>

<Footer />
