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
    <b>Dr Madeline Marshall</b> (Maddie, she/her)<br>
    <font size="3">
    Tasmanian astrophysicist. <br>
    Currently a Plaskett Fellow at the National Research Council Canada, Herzberg Astronomy and Astrophysics Research Centre, in Victoria, British Columbia. <br>
    Studies galaxies and supermassive black holes in the early Universe using computer simulations and space telescopes.<br>
    Leading a James Webb Space Telescope (JWST) program to study the host galaxies of the first quasars,
    and involved with several other exciting JWST projects studying the early Universe. <br>
    Completed a PhD at the University of Melbourne and a BSc (Honours) at the University of Tasmania. <br>
    <br>

    For more information, see:<br>
    - <a href="{{ '/cv.html' | absolute_url }}">CV</a><br>
    - <a href="{{ '/publications.html' | absolute_url }}">List of publications</a><br>
    - <a href="{{ '/outreach.html' | absolute_url }}">Media and outreach</a><br>
    - <a href="{{ '/talks.html' | absolute_url }}">Recordings of conference talks</a><br>

    <br>
    I recently did an interview about the excitement of JWST and my involvement, which can be found <a href="https://www.theadvocate.com.au/story/7546611/former-coaster-involved-in-space-telescope-launch/?cs=2606">here</a>.
    For a great article about Canada's involvement with JWST including a few quotes from me and some fantastic images, take a look at <a href="https://www.theglobeandmail.com/canada/article-james-webb-space-telescope-set-to-reveal-universes-outer-limits-to-a/">'What the Webb hopes to catch' from The Globe and Mail</a>, and to see how we at the National Research Council are involved with JWST, check out <a href="https://nrc.canada.ca/en/stories/look-nrc-faces-behind-james-webb-space-telescope">'A look into the NRC faces behind the James Webb Space Telescope.'</a><br>
    <br>
    </font>

    Contact me: madeline_marshall (at) outlook (dot) com<br>
    <br>

  </div>
  <div class="column right">
    <p><img src='../../HeadShot.jpg' border="0" width="300" style="padding:0px; display: block; line-height: 0px; font-size: 0px; border:0px;" align="top">
</p>
  </div>
</div>

</body>
