

<h1 align="center">Hi there, I'm Diana 👋</h1>

<div align="center">

<svg width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .bg { fill: #0d1117; }
      .computer-body { fill: #4a9eff; stroke: #2d5aa0; stroke-width: 3; }
      .screen { fill: #f0f6fc; stroke: #24292f; stroke-width: 2; }
      .keyboard { fill: #ffd700; stroke: #cc9900; stroke-width: 2; }
      .key { fill: #fff; stroke: #ddd; stroke-width: 1; }
      .text { font-family: 'Courier New', monospace; font-size: 24px; font-weight: bold; fill: #24292f; }
      .greeting { font-family: 'Arial', sans-serif; font-size: 28px; font-weight: bold; fill: #58a6ff; }
      .emoji { font-size: 24px; }
      .shape1 { fill: #ffd700; }
      .shape2 { fill: #ff6b9d; }
      .shape3 { fill: #4ecdc4; }
      .button { fill: #e6e6e6; stroke: #999; stroke-width: 2; cursor: pointer; }
      .button-text { font-family: 'Arial', sans-serif; font-size: 14px; fill: #333; text-anchor: middle; }
      .power-light { fill: #ff4444; }
      
      @keyframes typing {
        0% { opacity: 0; }
        50% { opacity: 1; }
        100% { opacity: 1; }
      }
      
      @keyframes blink {
        0%, 50% { opacity: 1; }
        51%, 100% { opacity: 0; }
      }
      
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-10px); }
      }
      
      @keyframes pulse {
        0%, 100% { opacity: 0.8; }
        50% { opacity: 1; }
      }
      
      .typing-animation { animation: typing 3s infinite; }
      .cursor { animation: blink 1s infinite; }
      .floating { animation: float 3s ease-in-out infinite; }
      .pulsing { animation: pulse 2s infinite; }
    </style>
  </defs>
  
  <!-- Background -->
  <rect width="800" height="400" class="bg"/>
  
  <!-- Decorative shapes -->
  <ellipse cx="100" cy="100" rx="40" ry="60" class="shape1 floating"/>
  <path d="M 700 80 L 750 120 L 720 160 L 680 140 Z" class="shape2 floating" style="animation-delay: -1s;"/>
  <circle cx="80" cy="320" r="35" class="shape3 floating" style="animation-delay: -2s;"/>
  <path d="M 720 320 Q 750 280 780 320 Q 750 360 720 320" class="shape2 floating" style="animation-delay: -0.5s;"/>
  
  <!-- Computer Monitor -->
  <rect x="280" y="120" width="240" height="180" rx="15" class="computer-body"/>
  
  <!-- Screen -->
  <rect x="300" y="135" width="200" height="130" rx="5" class="screen"/>
  
  <!-- Power button and lights -->
  <circle cx="490" cy="285" r="4" class="power-light pulsing"/>
  <circle cx="505" cy="285" r="3" fill="#44ff44" class="pulsing" style="animation-delay: -1s;"/>
  
  <!-- Screen content -->
  <text x="400" y="160" class="text typing-animation" text-anchor="middle">DIANA</text>
  <text x="400" y="185" class="text typing-animation" style="animation-delay: 0.5s;" text-anchor="middle">DATA ANALYST</text>
  <text x="400" y="210" class="text typing-animation" style="animation-delay: 1s;" text-anchor="middle">DATA SCIENTIST</text>
  <text x="400" y="235" class="text typing-animation" style="animation-delay: 1.5s;" text-anchor="middle">INDUSTRIAL ENG</text>
  <text x="420" y="250" class="cursor">|</text>
  
  <!-- Computer Base/Stand -->
  <rect x="330" y="300" width="140" height="20" rx="10" class="computer-body"/>
  <rect x="370" y="320" width="60" height="30" rx="5" class="computer-body"/>
  
  <!-- Keyboard -->
  <ellipse cx="400" cy="370" rx="120" ry="25" class="keyboard"/>
  
  <!-- Keyboard keys (simplified) -->
  <g class="floating" style="animation-delay: -1.5s;">
    <rect x="320" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="335" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="350" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="365" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="380" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="395" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="410" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="425" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="440" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="455" y="360" width="12" height="8" rx="2" class="key"/>
    <rect x="470" y="360" width="12" height="8" rx="2" class="key"/>
    
    <rect x="330" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="345" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="360" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="375" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="390" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="405" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="420" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="435" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="450" y="375" width="12" height="8" rx="2" class="key"/>
    <rect x="465" y="375" width="12" height="8" rx="2" class="key"/>
  </g>
  
  <!-- Start button -->
  <rect x="580" y="280" width="80" height="35" rx="5" class="button floating"/>
  <text x="620" y="302" class="button-text">Start</text>
  
  <!-- Greeting text -->
  <text x="400" y="50" class="greeting typing-animation" text-anchor="middle" style="animation-delay: 2s;">Hello there! ¡Hola! 👋🤓</text>
</svg>

</div> 


<p align="center">
  💻 Data Analyst transitioning into Data Science & Engineering<br/>
  📍 Based in Germany | 🇨🇴 Originally from Bogotá, Colombia
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/dianaterrazalopez/"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin" /></a>
  <a href="https://github.com/Dianaaleja"><img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github" /></a>
  <a href="mailto:dianalterlop@gmail.com"><img src="https://img.shields.io/badge/-Email-white?style=flat-square&logo=gmail" /></a>
</p>

---

### 👩‍💻 About Me

- 🎓 Industrial Engineer with 6+ years of experience in finance and customer analytics  
- 🌱 Currently learning Data Engineering, NLP, and deploying AI pipelines  
- 🧠 Passionate about Data, BI, forecasting, customer behavior, and scalable data products  
- 🚀 Career transition powered by Masterschool & Cisco certifications  
- 🌐 Languages: Spanish 🇪🇸 | English 🇬🇧 | German 🇩🇪 | French 🇫🇷

---

### 🚀 Tech & Tools

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=000)
![dbt](https://img.shields.io/badge/dbt-%23FF694B.svg?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-56B9DA?style=for-the-badge&logo=snowflake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)

---

### 🌱 Currently Learning

- ⚙️ Airflow for orchestration  
- 📊 dbt & Snowflake for cloud data engineering  
- 🧪 LangChain and OpenAI for AI agents and chatbots  
- ☁️ AWS fundamentals  

---

### 📌 Featured Projects

- [**NLP**](https://github.com/Dianaaleja/NLP): Conversational agents, vectorization, prompts, and NLP tools  
- [**XGBoost Forecast**](https://github.com/Dianaaleja/corporacion_favorita): Forecasting e-commerce products with deep learning ARIMA, SARIMA, LSTM models.  
- [**Client Segmentation**](https://github.com/Dianaaleja/travel_tide_customer_segment): K-means clustering and PCA for customer behavior  
- [**AWS Grocery**](https://github.com/Dianaaleja/AWS_grocery):Fully automated AWS infrastructure deployment using Terraform and GitHub Actions  

---

### 🏆 Certifications


- ☁️ **Certified Cloud Practitioner** (AWS - Foundational)  
- 📊 **Cisco Data Analytics Essentials**  
- 🧠 **Networking Academy Learn‑A‑Thon 2023**  
- 🏫 **Masterschool: Data Analyst - Data Scientist Path**  
- 🎓 Continuous learning: webinars, hands-on projects, GitHub collaboration   

---

### ✨ Let's Collaborate!

I'm open to collaborate on data science, analytics, or data engineering projects — especially where we can turn messy data into actionable insights. I enjoy learning and am always eager to explore new technologies and grow professionally. 

💬 Reach me on [LinkedIn](https://www.linkedin.com/in/dianaterrazalopez/) or drop me an email at: **dianalterlop@gmail.com**

---

<p align="center">
  Made with ❤️ by Diana Alejandra Terraza López
</p>
