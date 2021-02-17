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
  width: 60%;
}

.right {
  width: 40%;
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
    Hi! I'm Maddie, an astrophysicist from Tasmania, Australia. I study the host galaxies of supermassive black holes in the early Universe using computer simulations and space telescopes.
    I have just completed my PhD at the University of Melbourne, and am beginning a new position as the Plaskett Fellow at the National Research Council Canada, Herzberg Astronomy and Astrophysics.<br>
    <br>
    My work was recently featured by a NASA/STSci press release, which you can read <a href="https://www.nasa.gov/feature/goddard/2020/simulations-show-webb-telescope-can-reveal-distant-galaxies-hidden-in-quasars-glare/">here</a>!<br>
    <br>
    For more information, see:<br>
    - <a href="{{ '/cv.html' | absolute_url }}">CV</a><br>
    - <a href="{{ '/publications.html' | absolute_url }}">List of publications</a><br>
    - <a href="{{ '/outreach.html' | absolute_url }}">Media and outreach</a><br>
    - <a href="{{ '/talks.html' | absolute_url }}">Conference talks</a><br>
    <br>
    Contact me at madeline_marshall (at) outlook (dot) com!
  </div>
  <div class="column right">
    <p><img src='../../HeadShot.jpg' border="0" width="300" style="padding:0px; display: block; line-height: 0px; font-size: 0px; border:0px;" align="top">
</p>
  </div>
</div>

</body>
