---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. student in the Department of Geography at the University of Wisconsin–Madison, Spatial Computing and Data Mining Lab. My research interests lie in remote sensing, precision agriculture, natural hazards, and deep learning. I focus on integrating advanced machine learning (ML) and deep learning (DL) techniques with traditional remote sensing applications.

My current work involves:
- **Wildfire burnt area mapping** using bi-temporal Sentinel-2 imagery and attention-based U-Net models  
- **Hydrological streamflow prediction** with graph neural networks  
- **Precision agriculture monitoring** using deep spectral reconstruction methods from multispectral inputs

In the future, I aim to continue exploring cutting-edge methods for spatiotemporal change detection and disaster monitoring.  
<br><br>

📫 Feel free to reach out via email at **tsui5@wisc.edu** or connect on [Google Scholar](https://scholar.google.com/citations?user=XXXXXX) and [ResearchGate](https://www.researchgate.net/profile/Tang-Sui-2).

> Google Scholar citations:  
<a href='https://scholar.google.com/citations?user=TaezBZ0AAAAJ&hl=zh-CN&oi=ao'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

---

# 🔥 News
- *2025.07*: 🏆 Fourth Place, Remote Sensing Competition, 2025 AAG Annual Meeting.
- *2024.08*: 🎉 Started Ph.D. program at UW–Madison!
- *2024.06*: 📝 Our wildfire burnt area mapping paper accepted in *IJAEOG*.

---

# 📝 Selected Publications

- **Tang Sui**, Mingda Wu, Meiliu Wu, Zhou Zhang, Qunying Huang.  
  *BiAU-Net: Wildfire burnt area mapping using bi-temporal Sentinel-2 imagery and U-Net with attention mechanism*.  
  *International Journal of Applied Earth Observation and Geoinformation*, 2024.  
  <span class='show_paper_citations' data='TaezBZ0AAAAJ:9yKSN-GCB0IC'></span>

- **Mingda Wu**, Tang Sui, Bo Peng, Manzhu Yu, Qunying Huang.  
  *A Remote Sensing Spectral Index Guided Bitemporal Residual Attention Network for Wildfire Burn Severity Mapping*.  
  *IEEE JSTARS*, 2024.

- **Songxi Yang**, Bo Peng, Tang Sui, Qunying Huang.  
  *Self-supervised Pretraining with Edge Guidance for Building Damage Assessment*.  
  *7th ACM SIGSPATIAL AI4Geo Workshop*, 2024.

> _(For full list, see CV or Google Scholar)_

---

# 🎖 Honors and Awards
- 🥈 1st Prize, UAV Photogrammetry National Competition, 2022  
- 🥇 Tongji University Merit Scholarship (Top GPA), 2023  
- 🥉 National Surveying Tech Competition (Essay), 2021  

---

# 📖 Education
- **University of Wisconsin–Madison**, USA  
  Ph.D. Student in Geography, 2024 – Present  
- **Tongji University**, China  
  B.Eng. in Surveying and Mapping, 2019 – 2024

---

# 💬 Selected Talks
- *Quasi-Hyperspectral Image Generation with CNNs*, AAG 2025 Annual Meeting, Detroit  
- *Deep Learning for Urban Wildfire Detection*, GSCS & ICUI 2023, Hong Kong  
- *Burnt Area Mapping with Sentinel-2 and U-Net*, SDS Symposium 2023

---

# 💻 Internships & Projects
- Smart Agriculture Intern, CAAS, Beijing, 2021  
- GNSS Surveying, GIS & Engineering Practice, Tongji University  
- Pedestrian Detection Lighting System, MIT–Tongji Joint Project

