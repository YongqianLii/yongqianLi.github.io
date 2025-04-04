<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yongqian Li - Professional CV</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Playfair+Display:wght@600&display=swap" rel="stylesheet" />
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #fdfcf9;
      color: #2d4a53;
    }
    header {
      background: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 26px;
      margin: 0;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #2d4a53;
      font-weight: 600;
    }
    nav a:hover {
      color: #ff7755;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }
    .card {
      background: #fff;
      border-radius: 12px;
      padding: 30px;
      margin-bottom: 40px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.06);
    }
    .photo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #fff;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
      display: block;
      margin: 0 auto 20px;
    }
    .center {
      text-align: center;
    }
    h2 {
      font-size: 24px;
      margin-top: 0;
      position: relative;
      padding-bottom: 8px;
    }
    h2::after {
      content: '';
      width: 50px;
      height: 3px;
      background: #ff7755;
      position: absolute;
      bottom: 0;
      left: 0;
    }
    ul {
      padding-left: 20px;
    }
    .timeline {
      border-left: 3px solid #77c1b2;
      padding-left: 20px;
    }
    .timeline-item {
      margin-bottom: 20px;
    }
    .timeline-item h4 {
      margin: 0 0 5px;
      color: #2e6c80;
    }
    .gallery img {
      width: 100%;
      max-width: 720px;
      border-radius: 8px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.02);
    }
    .download-btn {
      background: #ff7755;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 6px;
      display: inline-block;
      margin-top: 20px;
      font-weight: 600;
    }
    footer {
      text-align: center;
      color: #888;
      font-size: 14px;
      padding: 20px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Yongqian Li</h1>
    <nav>
      <a href="#profile">Profile</a>
      <a href="#timeline">Timeline</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <div class="card center" id="profile" data-aos="fade-up">
      <img class="photo" src="photo.jpg" alt="Yongqian Li">
      <h2>Profile</h2>
      <p>PhD Candidate | Infertility Research | Experimental Biology & Data Analysis</p>
      <p>I pursued a PhD (second-year) in the field of infertility at the UCLouvain University School of Medicine from January 2023 to March 2025...</p>
      <a class="download-btn" href="cv_yongqianli.pdf" download>Download PDF CV</a>
    </div>

    <div class="card" id="timeline" data-aos="fade-up">
      <h2>Experience Timeline</h2>
      <div class="timeline">
        <div class="timeline-item">
          <h4>2023–2025: PhD Candidate</h4>
          <p>UCLouvain – Infertility Research and Experimental Biology</p>
        </div>
        <div class="timeline-item">
          <h4>2020–2022: Bioinformatics Training</h4>
          <p>Shanghai Qianshuo Bio – R, Python & Single-cell analysis</p>
        </div>
        <div class="timeline-item">
          <h4>2016–2019: IVF Clinical Assistant</h4>
          <p>Shanghai & Tongji Universities – Clinical + animal study projects</p>
        </div>
      </div>
    </div>

    <div class="card" id="gallery" data-aos="fade-up">
      <h2>Visualization Gallery</h2>
      <p>Figures generated using R and Python:</p>
      <div class="gallery">
        <img src="PCA.png" alt="PCA Plot">
        <img src="Volcano_optimized.png" alt="Volcano Plot">
        <img src="ggalluvial.png" alt="Alluvial Plot">
      </div>
    </div>

    <div class="card center" id="contact" data-aos="fade-up">
      <h2>Contact</h2>
      <p><strong>Address:</strong> Rue Martin V 9, 1200 Woluwe-Saint-Lambert</p>
      <p><strong>Phone:</strong> +32 0495 354 233</p>
      <p><strong>Email:</strong> <a href="mailto:yongqianleee@gmail.com">yongqianleee@gmail.com</a></p>
    </div>
  </div>

  <footer>
    &copy; 2025 Yongqian Li – All rights reserved.
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
