---
layout: page
title: Contact
permalink: /contact/
---

# Contact

Please fill out the form below to get in touch with me!

<form action="https://formspree.io/f/mayrkaak" method="POST">
  <label for="name">Name: *</label><br>
  <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

  <label for="email">Email: *</label><br>
  <input type="email" id="email" name="email" placeholder="Enter your email address" required><br><br>

  <label for="phone">Phone:</label><br>
  <input type="tel" id="phone" name="phone" placeholder="Enter your phone number"><br><br>

  <label for="message">Message:</label><br>
  <textarea id="message" name="message" placeholder="Type your message here" rows="4" cols="50"></textarea><br>

  <input type="submit" value="Send">
</form>
<br>

<!-- Embed Google Maps -->
<div id="map" style="height: 400px; width: 100%;"></div>

<script>
  function initMap() {
    const map = new google.maps.Map(document.getElementById("map"), {
      center: { lat: 55.80785, lng: 12.510003 },
      zoom: 15,
    });
    const marker = new google.maps.Marker({
      position: { lat: 55.80785, lng: 12.510003 },
      map: map,
    });
  }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCCaJI21DqAtxCNnLrorlyGV7MSS7fM6Z0&callback=initMap" async defer></script>



