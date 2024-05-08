---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
    .area_pics img{
        width:380px;
        margin-left:50px
        float:left;
    }
  
        .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
        overflow: hidden;
      }
      
      .mySlides {
        display: none;
      }
      
      .prev, .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        margin-top: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 24px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
      }
      
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      
      .prev:hover, .next:hover {
        background-color: rgba(0,0,0,0.8);
      }
  
      .news {
      width:800px;
      height: 150px;
      overflow-y: auto;
    }
</style>
<body align="justify">
<div class="area_pics">
 <img src="/images/isa.png" />
 <img src="/images/EAI.png" />
</div>
<div class="area_pics">
 <img src="/images/TIM3.png" />
 <img src="/images/TCE.jpg" />
</div>
  <br>
<div>
   <h1> News about the laboratory</h1>
   <hr/> 
<div class="news">
<li> “SCG-GFFE: A Self-Constructed graph fault feature extractor based on graph Auto-encoder algorithm for unlabeled single-variable vibration signals of harmonic reducer” is accepted by AEI! Congratulations Hao Ding!--2024.04</li>
<li> “A Novel Cross-Domain Data Augmentation and Bearing Fault Diagnosis Method Based on an Enhanced Generative Model” is accepted by IEEE TIM! Congratulations Hao Ding!--2024.04</li>
<li> “Contrastive learning and dynamics embedding neural network for label-free interpretable machine fault diagnosis” is accepted by ISA Transactions! Congratulations Tengyi Peng!--2024.1</li>


  </div>
   </div>   
<br>
 <!-- 
<h1>What we do </h1>
   <hr/> 
  <p><b>Seeing is believing! </b>We firmly believe that resolution determines the depth of the research. We are interested to use super-resolution microscopy to show the wonders of the microscopic world. To achieve this, we collaborate heavily with biologists and develop a range of interdisciplinary technologies including new optics theories, advanced algorithms, smart hardware design and imaging strategies for better resolution, deeper depth, and faster speed. We embrace the open science and hope that our work will promote both the advancement of science and technology.</p>
  -->

<h1>Who we are </h1>
     <hr/> 
  <div class="slideshow-container">
      <div class="mySlides"> 
        <img src="/images/team1.jpg" style="width:100%">
      </div>
      <!--  
      <div class="mySlides">
        <img src="/images/team2.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team3.png" style="width:100%">
      </div>
          <div class="mySlides"> 
        <img src="/images/team4.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team5.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team6.png" style="width:100%">
      </div>
          <div class="mySlides"> 
        <img src="/images/team7.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team8.png" style="width:100%">
      </div>
      <div class="mySlides"> 
        <img src="/images/team9.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team10.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team11.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team11+.png" style="width:100%">
      </div>
      <div class="mySlides"> 
        <img src="/images/team12.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team13.png" style="width:100%">
      </div>
         <div class="mySlides">
        <img src="/images/team14.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team15.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team16.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team17.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team18.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team19.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team20.png" style="width:100%">
      </div>
    <div class="mySlides">
        <img src="/images/team21.png" style="width:100%">
      </div>
          <div class="mySlides">
        <img src="/images/team22.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team23.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team24.png" style="width:100%">
      </div>
    <div class="mySlides">
        <img src="/images/team25.png" style="width:100%">
      </div>
      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    -->
  <p>Our group is a mix of Mechanical, Control, and Computer.</p>
    <script>
      var slideIndex = 5;
      showSlides(slideIndex);
      
      function plusSlides(n) {
        showSlides(slideIndex += n);
      }
      
      function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        if (n > slides.length) {slideIndex = 1}
        if (n < 1) {slideIndex = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        slides[slideIndex-1].style.display = "block";
      }
       setInterval(function () {
    plusSlides(1);
  }, 3000);
    </script>
 






