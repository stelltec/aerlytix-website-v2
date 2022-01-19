---
title: "Contact Us"
header: "Contact Us"
# summary: ""
---

<article>
<div class="container col-md-12">
    <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
      <div class="col mb-4">
        <div class="card pt-5 pb-5 rounded-6 shadow">
            <h3>Email us:</h3>
            <p>Email us for general queries.</p>
            <p><a class="h4" href="mailto:info@aerlytix.com">info@aerlytix.com</a></p>
        </div>
      </div>
      <div class="col mb-4">
        <div class="card pt-5 pb-5 ps-3 pe-3 rounded-6 shadow">
            <h3>Call us:</h3>
            <p>Call to speak to a member of our team.</p>
            <p><a class="h4" href="tel:0035316077070">+353 (0)1 607 7070</a></p>
        </div>
      </div>
      <div class="col mb-4">
        <div class="card pt-5 pb-5 rounded-6 shadow">
            <h3>Follow us:</h3>
            <p>We are present in this networks.</p>
            <p>
            <a class="link-dark" href="https://www.twitter.com/aerlytix">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/></svg>
            </a>
            <a class="link-dark ms-2" href="https://www.linkedin.com/company/aerlytix">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/></svg>
            </a>
            </p>
        </div>
      </div>
      <div class="col-md-12 mb-4">
        <!-- <div class="card mb-4 pt-5 pb-5 rounded-6 shadow">
            <h3>Visit us:</h3>
            <p>Embassy House<br/> Herbert Park Lane<br />Ballsbridge<br />D04 H6Y0, Ireland</p>
        </div> -->
        <div class="card mb-4 rounded-6 shadow contact-us__map-card">
          <div class="row g-0">
            <div class="col-md-4">
              <div class="card-body pt-5 pb-5">
                <h3>Visit us:</h3>
                <p>Embassy House<br/> Herbert Park Lane<br />Ballsbridge<br />D04 H6Y0, Ireland</p>
              </div>
            </div>
             <div class="col-md-8 bg-green">
              <div id="map-dublin" class="map-canvas rounded-left" data-lat="25.7617" data-lng="-80.1918" data-color="#0c66ff" style="height: 500px"></div>
            <script>
              var map = L.map("map-dublin").setView([53.328268, -6.231743], 17);
              L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
                  attribution:
                    '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors',
                }
              ).addTo(map);
              var LeafIcon = L.Icon.extend({
                options: {
                  iconSize: [45, 120],
                },
              });
              var greenIcon = new LeafIcon({
                iconUrl: "/images/map-marker.svg",
              });
              L.marker([53.328268, -6.231743], { icon: greenIcon })
                .bindPopup(
                  "Embassy House, Herbert Park Lane, Ballsbridge, D04 H6Y0, Ireland"
                )
                .addTo(map);
            </script>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>
</article>
