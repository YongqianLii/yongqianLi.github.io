<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yongqian Li - CV</title>
  <style>
    body {
      font-family: "Helvetica Neue", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f9fb;
      color: #2c3e50;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      max-width: 1100px;
      margin: 0 auto;
      padding: 40px 20px;
    }
    .sidebar {
      flex: 1;
      min-width: 250px;
      max-width: 300px;
      padding: 20px;
      background-color: #ffffff;
      box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.05);
    }
    .main {
      flex: 2;
      padding: 20px 30px;
      background-color: #ffffff;
      margin-left: 20px;
      box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.05);
    }
    img.photo {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      margin: 0 auto 20px;
      border: 3px solid #fff;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .contact p {
      text-align: center;
      font-size: 14px;
      margin: 5px 0;
      color: #555;
    }
    h1 {
      font-size: 32px;
      margin-bottom: 5px;
    }
    h2 {
      font-size: 20px;
      color: #005288;
      border-bottom: 1px solid #ccc;
      padding-bottom: 5px;
      margin-top: 40px;
    }
    .timeline {
      position: relative;
      margin: 30px 0;
      padding-left: 20px;
      border-left: 2px solid #ccc;
    }
    .timeline-item {
      margin-bottom: 25px;
      position: relative;
    }
    .timeline-item::before {
      content: '';
      position: absolute;
      left: -9px;
      top: 5px;
      width: 12px;
      height: 12px;
      background-color: #005288;
      border-radius: 50%;
    }
    .gallery img {
      width: 100%;
      max-width: 720px;
      margin: 25px 0;
      border-radius: 4px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      .main {
        margin-left: 0;
        margin-top: 20px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="sidebar">
      <img src="photo.jpg" alt="Yongqian Li" class="photo" />
      <div class="contact">
        <p><strong>Yongqian Li</strong></p>
        <p>Rue Martin V 9</p>
        <p>1200 Woluwe-Saint-Lambert</p>
        <p>+32 0495 354 233</p>
        <p><a href="mailto:yongqianleee@gmail.com">yongqianleee@gmail.com</a></p>
      </div>
    </div>

    <div class="main">
      <h1>Yongqian Li</h1>
      <p>
        I am a PhD candidate in infertility research at UCLouvain (2023–2025), with solid experimental skills and data analysis expertise. I specialize in translational medicine, and am currently seeking new PhD opportunities aligned with human clinical data and long-term funding support.
      </p>

      <h2>Timeline</h2>
      <div class="timeline">
        <div class="timeline-item">
          <strong>2023–2025:</strong> PhD in Infertility, UCLouvain — Developed expertise in PCR, HE staining, immunohistochemistry, immunofluorescence, TUNEL assays, and data analysis using R/Python.
        </div>
        <div class="timeline-item">
          <strong>2020–2022:</strong> Shanghai Qianshuo Bio — Specialized in single-cell omics analysis; gained proficiency in hCG-induced ovulation, egg collection, and parthenogenetic activation.
        </div>
        <div class="timeline-item">
          <strong>2016–2019:</strong> Clinical Assistant at Shanghai University & Tongji University — Gained IVF clinical experience, led two rat research projects involving anesthesia, sterile surgeries, and ovum collection.
        </div>
      </div>

      <h2>Visualization Gallery</h2>
      <p>Figures created using R and Python:</p>
      <div class="gallery">
        <img src="PCA.png" alt="PCA Plot">
        <img src="Volcano_optimized.png" alt="Volcano Plot">
        <img src="ggalluvial.png" alt="Alluvial Plot">
      </div>
    </div>
  </div>
</body>
</html>
