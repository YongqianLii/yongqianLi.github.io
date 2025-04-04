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
      margin-bottom: 10px;
      color: #2c3e50;
    }
    .subtitle {
      text-align: center;
      font-size: 18px;
      color: #7f8c8d;
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
      margin-bottom: 40px;
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
      margin-bottom: 40px;
      color: #555;
    }
    .contact p {
      margin: 5px;
    }
    .section {
      margin-top: 40px;
      padding: 30px;
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
    ol, ul {
      padding-left: 30px;
      margin-bottom: 15px;
    }
    li {
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
    .visual-desc {
      text-align: center;
      font-style: italic;
      color: #555;
      margin-bottom: 20px;
    }
    hr {
      border: none;
      border-top: 1px solid #ccc;
      margin: 30px 0;
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

  <div class="section" id="profile">
    <h2>Profile</h2>
    <p>
      I am currently a second-year PhD candidate at the Faculty of Medicine, UCLouvain (Belgium), conducting research from January 2023 to March 2025. My focus lies in the fundamental mechanisms of infertility and the development of experimental models. This work has enabled me to build a strong foundation in independent research and acquire substantial technical and analytical skills, especially in the following four domains:
    </p>
    
    <h3>Core Competencies</h3>
    <ol>
      <li>
        <strong>Experimental Design &amp; Molecular Techniques</strong>
        <p>
          I possess hands-on experience with a broad spectrum of molecular and histological methods, including PCR, hematoxylin–eosin (HE) staining, immunohistochemistry (IHC), immunofluorescence (IF), and TUNEL assays. I am capable of independently designing, optimizing, and executing full experimental workflows with high reproducibility. This allows me to generate reliable, interpretable biological data for mechanistic studies.
        </p>
      </li>
      <li>
        <strong>Data Processing &amp; Scientific Visualization</strong>
        <p>
          I am proficient in using R and Python for data analysis, particularly in statistical modeling and bioinformatics. Additionally, I utilize tools such as GraphPad Prism, QuPath, and ImageJ to ensure clean and comprehensive data visualization. This enables efficient transformation of raw biological data into structured, publication-quality insights.
        </p>
      </li>
      <li>
        <strong>Animal Models &amp; Research Compliance</strong>
        <p>
          I am certified in Laboratory Animal Science by the official Belgian online course. My expertise includes murine reproductive procedures (e.g., hCG-induced ovulation, oocyte retrieval, and parthenogenetic activation) and rat model operations (e.g., anesthesia and aseptic surgery). This combination of technical skill and ethical compliance ensures precise, reproducible animal experiments.
        </p>
      </li>
      <li>
        <strong>Interdisciplinary Training &amp; Independent Project Leadership</strong>
        <p>
          Between 2020 and 2021, I received systematic training in bioinformatics and single-cell omics at Qianshuo Bio (Shanghai), which extended my capabilities into data-driven biology. From 2016 to 2019, I worked as a clinical assistant in reproductive medicine (Shanghai University of Traditional Chinese Medicine and Tongji University), where I independently led a rodent-based research project funded by a university innovation grant. I managed all phases of the project—from experimental design to surgical execution and data analysis—demonstrating autonomy, scientific rigor, and leadership.
        </p>
      </li>
    </ol>
    
    <h3>Current Objective</h3>
    <p>
      My current research has encountered a significant challenge: key experimental outcomes diverge from clinical datasets derived from over 150 medical centers, and the project lacks sustainable funding. Therefore, I am actively seeking a new PhD opportunity within a team that offers strong scientific infrastructure, interdisciplinary collaboration, and long-term vision. My goal is to further expand my technical expertise and global perspective while contributing meaningfully to high-impact translational medical research.
    </p>
  </div>

  <div class="section" id="visualization">
    <h2>Visualization Gallery</h2>
    <p class="visual-desc">Below are some data charts generated by R language programs:</p>
    <div class="gallery">
      <img src="PCA.png" alt="PCA Plot">
      <img src="Volcano_optimized.png" alt="Volcano Plot">
      <img src="ggalluvial.png" alt="Alluvial Plot">
      <img src="heatmap.png" alt="Heatmap Plot">
    </div>
  </div>

</body>
</html>
