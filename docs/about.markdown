---
layout: page
order: 2
title: About Me
permalink: /about me/
---

In 2023 I graduated from Columbia University with master's degrees in data science and social policy (an MA from  <a href="https://qmss.columbia.edu"> QMSS </a> and an MIA from <a href="https://www.sipa.columbia.edu/sipa-education/masters-programs/master-international-affairsSIPA"> SIPA</a>). I studied probability and statistics, as the foundation of emerging data science techniques, and how to apply those data science techniques, like data mining, machine learning, and AI, in a wide variety of fields.

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photo Gallery</title>

  <style>
    /* General body styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4; /* Light background for contrast */
    }

    /* Photo gallery container using CSS Grid */
    .photo-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* Creates responsive columns */
      gap: 16px; /* Space between the images */
      padding: 20px; /* Padding around the gallery */
      justify-items: center; /* Center images in each grid cell */
    }

    /* Gallery item styling */
    .gallery-item {
      position: relative; /* Needed for hover effects */
      overflow: hidden; /* Ensures the image doesn't overflow out of the container */
      border-radius: 8px; /* Rounded corners for images */
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Light shadow for depth */
      transition: transform 0.3s ease; /* Smooth transition for enlarging the container */
      display: flex; /* Use flexbox to center images */
      align-items: center; /* Vertically center the image */
      justify-content: center; /* Horizontally center the image */
    }

    /* Styling the images to make sure they fit inside the gallery item */
    .gallery-item img {
      width: 100%; /* Ensure the images take up full container width */
      height: 100%; /* Ensure the images take up full container height */
      object-fit: cover; /* This ensures images cover the container area without stretching */
      border-radius: 8px; /* Rounded corners for images */
    }

    /* Hover effect: enlarge the entire container */
    .gallery-item:hover {
      transform: scale(1.5); /* Enlarge the entire container (image + border) */
      z-index: 10; /* Bring the container to the front */
    }
  </style>
</head>
<body>

  <div class="photo-gallery">
    <div class="gallery-item">
      <img src="../IMG-20230511-WA0010.jpg" alt="grad photo 1" />
    </div>
    <div class="gallery-item">
      <img src="../grad photo.png" alt="grad photo 2" />
    </div>
    <div class="gallery-item">
      <img src="../grad1.png" alt="grad photo 3" />
    </div>
    <div class="gallery-item">
      <img src="../IMG-20230512-WA0009.jpg" alt="grad photo 4" />
    </div>
  </div>

</body>
</html>

 <br>
 <br>
Since graduation I've been working at <a href="https://www.publicpolicylab.org"> Public Policy Lab</a>, a civic innovation and design research firm that works primarily with government agencies to rethink how they deliver social services.

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photo Gallery</title>

  <style>
    /* General body styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4; /* Light background for contrast */
    }

    /* Group of photos container */
    .photo-group {
      display: flex; /* Use flexbox to arrange images side by side */
      gap: 16px; /* Space between the images */
      justify-content: center; /* Center the photos horizontally */
      flex-wrap: wrap; /* Allow wrapping if the screen is small */
      padding: 20px; /* Padding around the group */
    }

    /* Individual photo container */
    .photo-item {
      position: relative;
      width: 300px; /* Set a fixed width for the container */
      height: 300px; /* Set a fixed height for the container */
      overflow: hidden; /* Hide the overflow */
      border-radius: 8px; /* Rounded corners for the container */
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Light shadow for depth */
      transition: transform 0.3s ease; /* Smooth transition for enlarging */
      display: flex; /* Use flexbox to center images */
      align-items: center; /* Vertically center the image */
      justify-content: center; /* Horizontally center the image */
    }

    /* Styling the images to fit their container */
    .photo-item img {
      width: 100%; /* Ensure the images take up full container width */
      height: 100%; /* Ensure the images take up full container height */
      object-fit: cover; /* Ensure the images cover the container without stretching */
      border-radius: 8px; /* Rounded corners for the images */
    }

    /* Hover effect: enlarge the entire container */
    .photo-item:hover {
      transform: scale(1.5); /* Enlarge the entire container (image + border) */
      z-index: 10; /* Bring the container to the front */
    }
  </style>
</head>
<body>

  <!-- Group of Photos -->
  <div class="photo-group">
    <div class="photo-item">
      <img src="../IMG_4897.jpg" alt="PPL photo" />
    </div>
    <div class="photo-item">
      <img src="../IMG_7858.JPG" alt="PPL photo 2" />
    </div>
    <div class="photo-item">
      <img src="../IMG_9508.JPG" alt="PPL photo 3" />
    </div>
    <div class="photo-item">
      <img src="../IMG_7610%20(1).jpeg" alt="PPL photo 4" />
    </div>
  </div>

</body>
</html>


