<!-- .slide: data-background-color="rgb(0, 100, 93)" -->
<div>
  <p class="section-title">
    <em>
      If You Want to Make Enemies, <br>Try to Change Something.
      <br><br>
      If You Want to Make Errors, <br>Try to Change Environments.
    </em>
  </p>
</div>

|||
## Venturing Among Environments

<img src="slides/img/envs.png">

|||
## The Seven Circles of R Reproducibility Hell

<div class="row" style="display: flex;  align-items: center;">

  <div class="column" style="float:left;">
    <ul style="list-style-type:decimal">
      <li class="fragment fade-in-then-semi-out" data-fragment-index="0" style="padding-bottom: 12px">Code Version</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="1" style="padding-bottom: 12px">Required Packages</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="2" style="padding-bottom: 12px">Package Dependencies</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="3" style="padding-bottom: 12px">Language Version</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="4" style="padding-bottom: 12px">Run Time Environment</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="5" style="padding-bottom: 12px">External Dependencies</li>
      <li class="fragment fade-in-then-semi-out" data-fragment-index="6" style="padding-bottom: 12px">Operating System</li>
    </ul>
  </div>

  <div class=" column" style="float: right;">
      <img src="slides/img/circles.jpg" style="display: flex; align-items: center; margin: 0px">
      <div style="font-size: 9px; text-align: left">
        The R logo is &#xa9; 2016 The R Foundation <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>
      </div>
  </div>

</div>

|||
## A Tale of Two Control Charts
<div class="row" style="display: flex;  align-items: center;">

  <div class="column" style="float:left;">
    <img src="slides/img/devCtrlChart.png">
  </div>

  <div class=" column" style="float: right;">
    <img src="slides/img/testCtrlChart.png">
  </div>

</div>
<div  class="fragment highlight-darkgreen" data-fragment-index="0">
  <span class="fragment fade-in" data-fragment-index="0">"dark green"</span>
</div>

|||
<h2>Only Two Things Are Certain in Life &mdash; <br>Backwards Compatibility is Not One of Them</h2>

<div class="r-stack">
  <span>
    <img src="slides/img/depends1.png" style="max-width: 100%">
  </span>
  <span class="fragment fade-out" data-fragment-index="2">
    <img src="slides/img/depends2.png" class="fragment fade-in" data-fragment-index="1" style="max-width: 100%">
  </span>
  <span>
    <img src="slides/img/depends3.png" class="fragment fade-in" data-fragment-index="2" style="max-width: 100%">
  </span>
</div>

