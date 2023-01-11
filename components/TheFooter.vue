<template>
  <footer id="footer">
    <div class="footer-top">
      <div class="container">
        <div class="row center">
          <div class="col-md-6">
            <h1>Join Our <strong>Newsletter</strong> & Get updated.</h1>
          </div>
          <div class="col-md-6 ">
            <form class="form-inline">
              <div class="form-group w-100">
                <input
                  type="text"
                  class="form-control w-100 mb-0"
                  placeholder="Enter Your Email"
                />
                <p>We only send interesting and relevant emails</p>
              </div>
              <button type="submit" class="btn btn-main">Subscribe</button>
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-content">
      <div class="container">
        <div class="row">
          <div class="col-md-5">
            <div class="widget-item">
              <div class="footer-about">
                <img
                  class="logo-footer"
                  src="~/assets/images/footer-logo.png"
                  alt=""
                />
                <p>
                  Corpita is all about you, your business, and your victory. We
                  deliver a wide range of services to help you reach your goals.
                </p>
                <SocialMedia />
              </div>
            </div>
          </div>
          <div class="col-md-7 ">
            <div class="row end">
              <div class="col-md-3">
                <div class="widget-item">
                  <h4>Links</h4>
                  <ul class="footer-links">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Company</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Work</a></li>
                    <li><a href="#">Blog </a></li>
                    <li><a href="#">Contact Us</a></li>
                  </ul>
                </div>
              </div>

              <div class="col-md-3">
                <div class="widget-item">
                  <h4>Services</h4>
                  <ul class="footer-links">
                    <li><a href="#">Branding</a></li>
                    <li><a href="#"> Mobile Apps</a></li>
                    <li><a href="#">Marketing </a></li>
                    <li><a href="#"> Web Development</a></li>
                    <li><a href="#">UI/UX Design</a></li>
                    <li><a href="#">Support</a></li>
                  </ul>
                </div>
              </div>

              <div class="col-md-3">
                <div class="widget-item">
                  <h4>Legal</h4>
                  <ul class="footer-links">
                    <li><a href="#">Terms of use</a></li>
                    <li><a href="#">Terms & conditions</a></li>
                    <li><a href="#">Privacy policy</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#"> Cookie policy</a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-divider">
      <div class="container">
        <div class="divider-line"></div>
      </div>
    </div>

    <div class="copyright">
      <p>Copyright © 2017 Corptia - All Right Reserved</p>
    </div>
  </footer>
</template>

<script>
import SocialMedia from "./SocialMedia.vue";
export default {
  name: "TheFooter",
  layout: "component",

  components: {
    SocialMedia,
  },
};
</script>

<style></style>
