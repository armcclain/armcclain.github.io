---
title: "about me"
permalink: /about me/
layout: page
--- 

<style>
  /* General Styling for Desktop */
  .content-container {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 20px;
  }

  .content-container img {
    max-width: 250px;
    height: auto;
  }

  .content-container div {
    flex: 1;
    max-width: 600px;
  }

  /* Mobile-specific Styles */
  @media (max-width: 768px) {
    .content-container {
      flex-direction: column; /* Stack vertically */
      align-items: center; /* Center horizontally */
    }

    .content-container img {
      margin-top: 20px; /* Add space above the image */
      order: 2; /* Move the image to the bottom (end) */
    }

    .content-container div {
      max-width: 100%; /* Allow text to fill the available space */
      order: 1; /* Ensure text stays on top */
    }
  }
</style>


<div class="content-container">
  
  <!-- Text Content -->
  <div style="flex: 1; max-width: 600px;">
    
    <p>i am a behavioral ecologist interested in how death and loss in social groups can inform what we know about social bonds in nonhuman species.</p>
    
    <p>right now you can find me working on my phd at george washington university's <a href="https://cashp.columbian.gwu.edu/primate-behavioral-ecology" style="color: #840032;"><strong>primate behavioral ecology lab</strong></a> in washington, dc and in the field at <a href="https://janegoodall.ca/what-we-do/africa-programs/gombe-stream-research-centre/" style="color: #840032;"><strong>gombe national park</strong></a>, tanzania. my work is funded by the national science foundation, the leakey foundation, the american society of mammalogists, and the gw anthropology department.</p>

    <p>my recent projects explore the influence of friendship on space use in wild primates — analyzing geospatial and behavioral data from the world's longest running great ape dataset.</p>

    <p>before my phd, i worked with the indiana department of natural resources herpetology and nongame mammals teams surveying indiana's endangered reptile and mammal species.</p>

    <p>want to chat? you can find me on <a href="https://www.linkedin.com/in/abigail-mcclain" style="color: #840032;"><strong>linkedin</strong></a>! in the meantime, you can catch up with my latest <a href="https://armcclain.github.io/publications/" style="color: #840032;"><strong>publications</strong></a> and <a href="https://armcclain.github.io/creative%20works/" style="color: #840032;"><strong>creative works</strong></a> and find my <a href="https://github.com/user-attachments/files/18383961/McClain_Abigail_2pg_CV_JAN_2025.pdf" style="color: #840032;"><strong>cv</strong></a> here.</p>

  </div>

  <!-- Headshot Image -->
  <img src="https://github.com/user-attachments/assets/d733de93-f5a5-4a5b-8028-a6e5e4335336" 
       alt="Abigail McClain Headshot" 
       style="max-width: 250px; height: auto;">
</div>
