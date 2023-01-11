<template>
  <div class="container">
    <div class="contact-page">
      <div class="contact-content">
        <div class="row">
          <div class="col-md-6">
            <div class="conact-info">
              <div class="contact-item">
                <h2 class="mb-60">Contact Us</h2>
                <h5>call us</h5>

                <p>
                  Our customer service is open from Sunday to Thursday, from
                  10:00 am to 6:00 pm
                </p>
                <a href=""> <i class="fas fa-phone-alt"></i>(123) 456 7890</a>
              </div>
              <div class="contact-item">
                <h5>Email</h5>
                <p>
                  A response is given within 48 hours in official working hours                </p>
                <a href="#">
                    <i class="far fa-envelope"></i>hello@corptia.com</a
                >
              </div>
              <div class="contact-item">
                <h5>Visit Us</h5>
                <p>
                  Our office is open from Sunday to Thursday, from 10:00 am to
                  6:00 pm
                </p>
                <a href="#">
                  <i class="fas fa-map-marker-alt"></i>18 Second District
                  Center, New Damietta, Egypt</a
                >
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <form id="contact-form" role="form">
              <div class="form-group">
                <label for="form_name">Name</label>
                <input
                  id="form_name"
                  type="text"
                  name="name"
                  class="form-control"
                  required="required"
                  data-error="Firstname is required."
                />
              </div>
              <div class="form-group">
                <label for="form_phone">Phone</label>
                <input
                  id="form_phone"
                  type="text"
                  name="name"
                  class="form-control"
                  required="required"
                  data-error="phone is required."
                />
              </div>
              <div class="form-group">
                <label for="form_email">Email</label>
                <input
                  id="form_email"
                  type="text"
                  name="name"
                  class="form-control"
                  required="required"
                  data-error="Email is required."
                />
              </div>
              <div class="form-group">
                <label for="form_massage">Message</label>
                <textarea
                  id="form_message"
                  name="message"
                  class="form-control"
                  rows="4"
                  required="required"
                  data-error="Please, leave us a message."
                ></textarea>
              </div>
              <input type="submit" class="btn-main  " value="Send Message" />
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TheForm",
  layout:'component',

};
</script>

<style></style>
