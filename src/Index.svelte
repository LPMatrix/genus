<script type="text/javascript">
  import Hero from './Hero.svelte'

  let title = "Applying AI to some of the world’s biggest challenges through research, engineering, and initiatives to build the AI ecosystem,using AI to address societal challenges."
</script>

<Hero title = {title} />


        <div class="site-section bg-light" id="services-section">
        <div class="container">
          <div class="row mb-5 justify-content-center">
            <div class="col-md-7 text-center">
              <div class="block-heading-1">
                <h2>APPLICATIONS</h2>
              </div>
            </div>
          </div>
          <div class="owl-carousel owl-all">
            <a href="/retinopathy" target="_blank">
              <div class="block__35630">
                <div class="icon mb-0">
                  <span class="flaticon-ferry"></span>
                </div>
                <h3 class="mb-3">Diabetic Retinopathy Detection</h3>
                <p>Genus is easily accessible over the internet on the web. </p>
              </div>
            </a>
            <a href="/malaria">
              <div class="block__35630">
                <div class="icon mb-0">
                  <span class="flaticon-airplane"></span>
                </div>
                <h3 class="mb-3">Malaria Classiication</h3>
                <p>Genus is very easy to use. Just upload your fondus image and click classify </p>
              </div>
            </a>

           <!--  <div class="block__35630">
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
            </div> -->

          </div>
        </div>
      </div>


    <div class="site-section bg-light" id="contact-section">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center mb-5" data-aos="fade-up" data-aos-delay="">
            <div class="block-heading-1">
              <span>Get In Touch</span>
              <h2>Contact Us</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6 mb-5" data-aos="fade-up" data-aos-delay="100">
            <form action="https://formspree.io/mbjdzjoz" method="POST">
              <div class="form-group row">
                <div class="col-md-12 mb-4 mb-lg-0">
                  <input type="text" class="form-control" placeholder="Name" name="name">
                </div>
              </div>

              <div class="form-group row">
                <div class="col-md-12">
                  <input type="email" class="form-control" placeholder="Email address" name="_replyto">
                </div>
              </div>

              <div class="form-group row">
                <div class="col-md-12">
                  <textarea name="message" id="" class="form-control" placeholder="Write your message." cols="30" rows="10"></textarea>
                </div>
              </div>
              <div class="form-group row">
                <div class="col-md-6 mr-auto">
                  <input type="submit" class="btn btn-block btn-primary text-white py-3 px-5" value="Send Message">
                </div>
              </div>
            </form>
          </div>
          <div class="col-lg-4 ml-auto" data-aos="fade-up" data-aos-delay="200">
            <div class="bg-white p-3 p-md-5">
              <h3 class="text-black mb-4">Contact Info</h3>
              <ul class="list-unstyled footer-link">
                <li class="d-block mb-3">
                  <span class="d-block text-black">Address:</span>
                  <span>4 Barnawa Close,Off Challawa Crescent,Barnawa,Kaduna</span></li>
                <li class="d-block mb-3"><span class="d-block text-black">Phone:</span><span>08132554349</span></li>
                <li class="d-block mb-3"><span class="d-block text-black">Email:</span><span><a href="mailto:mubaraqsanusi908@gmail.com">mubaraqsanusi908@gmail.com</a></span></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>


    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="row">
              <div class="col-md-7">
                <h2 class="footer-heading mb-4">About Us</h2>
                <p>A model with realistic clinical potential for automated diabetic retinopathy screening using image recognition, pattern recognition and machine learning using colour fundus photographs as input. </p>
              </div>

            </div>
          </div>
          <div class="col-md-4 ml-auto">


            <h2 class="footer-heading mb-4">Follow Us</h2>
            <a href="https://github.com/LPMatrix" class="smoothscroll pl-0 pr-3"><span class="icon-github"></span></a>
            <a href="https://twitter.com/WeirdMatrix" class="pl-3 pr-3"><span class="icon-twitter"></span></a>
            <a href="https://www.linkedin.com/in/matrix2552/" class="pl-3 pr-3"><span class="icon-linkedin"></span></a>
          </div>
        </div>

      </div>
    </footer>