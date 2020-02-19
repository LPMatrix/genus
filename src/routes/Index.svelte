<script type="text/javascript">
  import { Router, Route } from "svelte-routing";
  export let url = "";

  import Hero from './Hero.svelte'
  import Footer from './Footer.svelte'

  let title = "Applying AI to some of the world’s biggest challenges through research, engineering, and initiatives to build the AI ecosystem,using AI to address societal challenges."

  let projects = [
    {
      "name":"Diabetic Retinopathy Detection",
      "description": "a model with realistic clinical potential for automated diabetic retinopathy screening using machine learning with colour fundus photographs as input.",
      "url": "retinopathy"
    },
    {
      "name":"Malaria Detection",
      "description": "A deep neural network model introduced for identifying infected falciparum malaria parasite using transfer learning approach.",
      "url": "malaria"
    }
  ]
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
            <Router url="{url}">
            {#each projects as project}
              <Link to="/{project.url}" target="_blank">
                <div class="block__35630">
                  <div class="icon mb-0">
                    <span class="flaticon-ferry"></span>
                  </div>
                  <h3 class="mb-3">{project.name}</h3>
                  <p>{project.description}</p>
                </div>
              </Link>
              <div>
                <Route path="/{project.url}" component="{project.url}" />
              </div>
            {/each}
          </Router>
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

<Footer />