<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yongqian Li - CV</title>
  <style>
    body {
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
      max-width: 860px;
      margin: auto;
      padding: 50px 30px;
      background-color: #f5f7fa;
      color: #2c3e50;
      line-height: 1.7;
      font-size: 20px;
    }
    h1 {
      text-align: center;
      font-size: 42px;
      margin-bottom: 5px;
      color: #2c3e50;
    }
    .subtitle {
      text-align: center;
      font-size: 18px;
      color: #7f8c8d;
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
      margin-bottom: 30px;
    }
    .photo {
      text-align: center;
      margin: 20px 0;
    }
    .photo img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
      border: 3px solid #ffffff;
    }
    .contact {
      text-align: center;
      margin-bottom: 30px;
      color: #555;
    }
    .contact p {
      margin: 5px;
    }
    .section {
      margin-top: 40px;
      padding: 20px;
      background: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
      margin-bottom: 40px;
    }
    h2 {
      color: #34495e;
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
      margin-bottom: 20px;
      font-size: 28px;
      text-align: center;
    }
    h3 {
      font-size: 24px;
      margin-top: 20px;
      color: #34495e;
    }
    p {
      text-align: justify;
      margin-bottom: 15px;
    }
    ul {
      padding-left: 30px;
      margin-bottom: 15px;
    }
    ul li {
      margin-bottom: 10px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 20px;
    }
    .gallery img {
      width: calc(33% - 20px);
      max-width: 300px;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <h1>Yongqian Li</h1>
  <p class="subtitle">PhD Candidate | Infertility Research | Experimental Biology & Data Analysis</p>

  <div class="photo">
    <img src="photo.jpg" alt="Yongqian Li">
  </div>

  <div class="contact">
    <p><strong>Address:</strong> Rue Martin V 9, 1200 Woluwe-Saint-Lambert, Belgium</p>
    <p><strong>Phone:</strong> +32 0495 354 233</p>
    <p><strong>Email:</strong> <a href="mailto:yongqianleee@gmail.com">yongqianleee@gmail.com</a></p>
  </div>

  <div class="section">
    <h2>Profile</h2>
    <p>
      I pursued a PhD (second-year) at the Faculty of Medicine, UCLouvain (Belgium) from January 2023 to March 2025, focusing on the fundamental mechanisms of infertility and the development of experimental models. During this period, I have cultivated strong independent research capabilities and developed substantial expertise in experimental techniques, data analysis, and animal model operations. My core strengths include:
    </p>
    
    <h3>✅ Core Competencies</h3>
    <ul>
      <li><strong>Advanced Experimental Skills</strong><br>
      Proficient in a wide range of molecular and histological techniques, including PCR, hematoxylin–eosin (HE) staining, immunohistochemistry (IHC), immunofluorescence (IF), and TUNEL assays. I am capable of independently designing and executing complex experimental workflows with high reproducibility and data consistency.</li>
      <li><strong>Data Analysis & Visualization</strong><br>
      Experienced in using R and Python for statistical analysis and bioinformatics. Skilled in integrating tools such as GraphPad Prism, QuPath, and ImageJ to complete the full pipeline—from data cleaning and modeling to visualization—enabling the extraction of actionable scientific insights from complex data.</li>
      <li><strong>Certified & Competent in Animal Studies</strong><br>
      Certified by the Belgian official online course in Laboratory Animal Science. I am well-versed in murine reproductive procedures such as hCG-induced ovulation, oocyte retrieval, and parthenogenetic activation, and have hands-on experience in anesthesia and aseptic surgical techniques for rat models.</li>
      <li><strong>Interdisciplinary Background & Project Leadership</strong><br>
      Between 2020 and 2021, I undertook systematic training in bioinformatics and single-cell omics at Qianshuo Bio (Shanghai), extending my skills into data-driven biology. From 2016 to 2019, I worked as a clinical assistant in reproductive medicine at Shanghai University of Traditional Chinese Medicine and Tongji University. I independently led a rodent research project funded by a university innovation grant, overseeing experimental design, surgical execution, and data interpretation—demonstrating strong project execution and cross-disciplinary communication skills.</li>
    </ul>

    <h3>🎯 Current Goal</h3>
    <p>
      Due to fundamental discrepancies between my current research objectives and clinical datasets from over 150 medical centers, combined with a lack of dedicated funding, I am actively seeking a new PhD opportunity. I aspire to join a research team with strong resources and long-term vision, where I can further expand my technical expertise, broaden my global perspective, and contribute meaningfully to translational medical research.
    </p>
  </div>

  <div class="section">
    <h2>Visualization Gallery</h2>
    <p>Below are some data charts generated by R language programs:</p>
    <div class="gallery">
      <img src="PCA.png" alt="PCA Plot">
      <img src="Volcano_optimized.png" alt="Volcano Plot">
      <img src="ggalluvial.png" alt="Alluvial Plot">
    </div>
  </div>

</body>
</html>
