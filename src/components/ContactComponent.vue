<template>
  <div class="dizme_tm_section" id="contact">
    <div class="dizme_tm_contact">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <span>Contact Me</span>
          <h3>I Want To Hear From You</h3>
          <p>
            Please fill out the form on this section to contact with me. Or call
            between 9:00 a.m. and 8:00 p.m. ET, Monday through Friday
          </p>
        </div>
          <br>
          <br>     
            <div class="fields">
  <form
    action="https://formspree.io/f/xvggdyqv"
    method="POST"
    class="contact_form"
    id="contact_form"
    autocomplete="off"
  >
    <div class="input_list">
      <ul>
        <li>
          <input id="name" name="name" type="text" placeholder="Your Name" required />
        </li>
        <li>
          <input id="email" name="email" type="email" placeholder="Your Email" required />
        </li>
        <li>
          <input id="phone" name="phone" type="tel" placeholder="Your Phone" required/>
        </li>
        <li>
          <input id="subject" name="subject" type="text" placeholder="Subject" required/>
        </li>
      </ul>
    </div>
    <div class="message_area">
      <textarea
        id="message"
        name="message"
        placeholder="Write your message here"
        required
      ></textarea>
    </div>
                  <div class="dizme_tm_button">
                  <button class="button" id="send_message" style=" justify-content: center; align-items: center;" ><span>Submit Now</span></button>
                </div>
  </form>
</div>

          </div>
          <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
            <img src="img/brushes/contact/2.png" alt="" />
          </div>
        </div>
        <div class="dizme_tm_map wow fadeInUp" data-wow-duration="1s">
          <div class="mapouter">
            <div class="gmap_canvas">
              <iframe
                width="100%"
                height="375"
                id="gmap_canvas"
                src="https://maps.google.com/maps?q=2880%20Broadway,%20New%20York&t=&z=13&ie=UTF8&iwloc=&output=embed"
                frameborder="0"
                scrolling="no"
                marginheight="0"
                marginwidth="0"
              ></iframe
              ><a
                href="https://www.embedgooglemap.net/blog/divi-discount-code-elegant-themes-coupon"
              ></a>
            </div>
          </div>

          <!-- Get your API here https://www.embedgooglemap.net -->
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="img/brushes/contact/1.png" alt="" />
      </div>
</template>

<script>
export default {
  name: "ContactComponent",
  components: {},
};
</script>
