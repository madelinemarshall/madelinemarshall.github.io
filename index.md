---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
tagline:
---


<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}
.left {
  width: 62%;
}

.right {
  width: 38%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="row">
  <div class="column left">
    <b>Dr Madeline Marshall</b> (Maddie, she/her)<br>
    <br>
    Tasmanian astrophysicist. <br><br>
    Currently an Oppenheimer Fellow at Los Alamos National Laboratory, in Los Alamos, New Mexico. <br><br>

    Studies galaxies and supermassive black holes in the early Universe using computer simulations and space telescopes. <br>
    Key research topics: high-z quasar host galaxies, creating mock observations for telescope predictions and comparisons, quasar-host decomposition, black hole and galaxy scaling relations, high-z quasars, HST & JWST imaging, JWST IFU spectroscopy, hydrodynamical simulations, and semi-analytic models.  <br><br>

    Leading a James Webb Space Telescope (JWST) program to study the host galaxies of the first quasars,
    and involved with several other exciting JWST projects studying the early Universe including <a href="https://sites.google.com/view/jwstpearls">PEARLS</a> and GA-NIFS. <br><br>

    Completed a PhD at the University of Melbourne and a BSc (Honours) at the University of Tasmania. <br><br>
    Previous Plaskett Fellow at the National Research Council Canada, Herzberg Astronomy and Astrophysics Research Centre, in Victoria, British Columbia. <br><br>

    Contact me: madeline_marshall (at) outlook (dot) com<br>
        <br>

      </div>
      <div class="column right">
        <p><img src='../../HeadShot.jpg' border="0" width="250" style="padding:0px; display: block; line-height: 0px; font-size: 0px; border:0px;" align="top">

        <br>

        For more information, see:<br>
        - <a href="{{ '/cv.html' | absolute_url }}">CV</a><br>
        - <a href="{{ '/publications.html' | absolute_url }}">List of publications</a><br>
        - <a href="{{ '/outreach.html' | absolute_url }}">Media links and science for the public</a><br>
        - <a href="{{ '/talks.html' | absolute_url }}">Recordings of conference talks</a><br>
    </p>
      </div>
    </div>

    </body>
