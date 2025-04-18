---
layout: page
title: LCOGT
show_sidebar: false
menubar: observatories_menu
---

# Las Cumbres Observatory Global Telescope Network (LCOGT)
For more information, please visit: <a href="https://lco.global">https://lco.global</a>.

LCOGT operates a network of robotic optical telescopes at 7 sites world-wide with apertures of 0.4, 1.0 and 2.0m, 
illustrated by the interactive map below. 

<figure class="image is-16by9">
  <iframe class="has-ratio" src="https://terminator.lco.global/index.html?noident=true&weather=true"
          width="100%" height="600" frameborder="0"
          allowfullscreen>
  </iframe>
    <caption>Interactive map of LCOGT telescope facilities</caption>
</figure>

The geographic distribution of telescopes means that at least one site is in darkness at any given time, 
with visibility of targets in both hemispheres.  This is optimally suited to the immediate follow-up of 
any visible target at any time.  

The entire telescope network is operated as a single instrument through unique dynamic scheduling software. 
Users can request observations at any time interactively through an online portal or via software 
through LCO's Application Programmable Interface.  The dynamic scheduler automatically computes an optimized 
observing sequence for all operational telescopes in the network, running every 5min to ensure a rapid 
response to new and urgent requests.  This takes into account the live weather and conditions at each 
observing site, enabling the software to move observation requests to alternative sites in real-time if 
one telescope becomes unavailable for any reason.  This ensures a reponsive and robust mode of operation. 

The instrument complement for the telescope networks are as follows. 

<table class="table">
<tbody>
<tr align="center">
<th rowspan="2">Name</th>
<th rowspan="2">Telescope Class</th>
<th>Pixel scale "/pix</th>
<th rowspan="2">Field of view</th>
<th rowspan="2">Overhead per frame</th>
<th rowspan="2">Filter options</th>
</tr>
<tr align="center">
<td>(std. binning)</td>
</tr>
<tr>
<td><a href="https://lco.global/observatory/instruments/muscat3">MuSCAT</a></td>
<td><a href="https://lco.global/observatory/telescopes/2m">2-meter</a></td>
<td>0.27 (bin 1x1)</td>
<td>9.1'x9.1'</td>
<td>6s or 46s</td>
<td>SDSS g'r'i'zs fixed</td>
</tr>
<tr>
<td><a href="https://lco.global/observatory/instruments/sinistro">Sinistro</a></td>
<td><a href="https://lco.global/observatory/telescopes/1m/">1-meter</a></td>
<td>0.389 (bin 1x1)</td>
<td>26'x26'</td>
<td>28 s</td>
<td>21</td>
</tr>
<tr></tr>

<tr>
<td><a href="https://lco.global/observatory/instruments/qhy600-delta-rho-350">QHY600</a></td>
<td><a href="https://lco.global/observatory/instruments/qhy600-delta-rho-350">0.4-meter (Delta Rho 350)</a></td>
<td>~0.74 (bin 1x1)</td>
<td>1.9&deg; x 1.2 &deg;</td>
<td>4 s</td>
<td>13</td>
</tr>
</tbody>
</table>
  

<script>

    $(".navbar-item.has-dropdown").click(function(e) {
          if ($(".navbar-burger").is(':visible')) {
            $(this).toggleClass("is-active");
          }
      });
      $(".navbar-item > .navbar-link").click(function(e) {
          if ($(".navbar-burger").is(':visible')) {
            e.preventDefault();
          }
      });
      $(window).resize(function(e) {
        if (!$(".navbar-burger").is(':visible') && $(".navbar-item.has-dropdown.is-active").length) {
          $(".navbar-item.has-dropdown.is-active").removeClass('is-active');
        }
      });

    function togglehideshow(elid) {
          var div = document.getElementById(elid);
          if (div.style.display !== 'none') {
              div.style.display = 'none';
          }
          else {
              div.style.display = 'block';
          }
      };
</script>
