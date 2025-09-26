---
layout: default
title: Leaderboard
---

## Photo Reel
<style>
  .slideshow-container {
    width: 100%;
    max-width: 700px;
    position: relative;
    margin: auto;
    overflow: hidden;
    border-radius: 8px;
    aspect-ratio: 16 / 9; /* Sets a widescreen aspect ratio */
  }
  .slide-image {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensures image covers the container */
    display: none; /* Hide all images by default */
    position: absolute;
  }
</style>

<div class="slideshow-container">
  <img class="slide-image" src="https://res.cloudinary.com/davtpvjyg/image/upload/v1758850153/86110909_-_Alexus_Warchock_kfnzoa.jpg">
  <img class="slide-image" src="https://res.cloudinary.com/davtpvjyg/image/upload/v1758850154/a9c3e497aeffd89d805e99f8ed8c8e56_-_Alexus_Warchock_t6a8jz.jpg">
  <img class="slide-image" 
src="https://res.cloudinary.com/davtpvjyg/image/upload/v1758850153/cry1_-_Alexus_Warchock_bjg5z1.jpg">
  <img class="slide-image"     src="https://res.cloudinary.com/davtpvjyg/image/upload/v1758850152/someone-are-you-seriously-going-to-cry-because-you-re-stressed-me-331370_-_Alexus_Warchock_g22hr1.jpg">
</div>

<script>
  let slideIndex = 0;
  showSlides();

  function showSlides() {
    let slides = document.getElementsByClassName("slide-image");
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}
    slides[slideIndex-1].style.display = "block";
    setTimeout(showSlides, 4000); // Change image every 4 seconds
  }
</script>

## Competition Leaderboard

The results update automatically as new entries are submitted.

<iframe src="https://docs.google.com/spreadsheets/d/1IqbruTQqIsP7_g8dXXSFmJTxSl_3kKARwapnPzySzsE/edit?usp=sharing" width="100%" height="600"></iframe>

