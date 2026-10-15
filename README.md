![Banner](f3606ae3-29b8-4c39-88eb-8be921db43ac.png)

# Hi, I'm Alya

I build software in Python and TypeScript: full stack apps, machine learning pipelines, and the data work underneath them. Based in Ireland.

I did my MSc in Data Analytics at TUS, where I built a drone assisted human detection system for search and rescue, using YOLOv8 to pick people out of aerial footage. Before that a Certificate in Software Engineering with Ericsson, where I was Scrum Master in Sprint 2, and a BSc in Applied Physics at UTP, which is where programming started for me with C and an Arduino.

Physics into data into engineering is a strange path, but it means I am comfortable anywhere from a database schema to a training run. Lately I have been leaning into software engineering while keeping the data science sharp.

**What I reach for most:** Python, TypeScript, SQL, React, FastAPI, PyTorch, PostgreSQL, Docker, Linux

Outside of code: film photography, painting, journaling, and Spotify.

## Featured Projects

### [ContagionLab](https://github.com/alymkarim/ContagionLab)

Financial contagion engine. It builds correlation networks from asset returns and pushes shocks through them to show where systemic risk spreads.

* Six network construction methods compared, with Random Matrix Theory filtering to cut noise
* Monte Carlo stress tests and replays of past crises such as 2008
* FastAPI backend with a React frontend and an interactive force graph

**Stack:** Python, FastAPI, NetworkX, pandas, React, TypeScript

**[Live Demo](https://contagionlab.vercel.app)**

### [driftwatch](https://github.com/alymkarim/driftwatch)

Population drift monitor. It compares the data a model was validated against with the data it is scoring now, and flags the features that moved.

* Written in Rust, using PSI and KS statistics with six behavioural tests
* Exits with a nonzero status so it can gate a model promotion in CI
* GitHub Actions pipeline and tagged releases with native binaries

**Stack:** Rust, csv, GitHub Actions

**[Releases](https://github.com/alymkarim/driftwatch/releases)**

### [ResearchIQ](https://github.com/alymkarim/researchiq)

Research paper analysis platform. Upload a PDF and get objectives, methodology, findings, strengths and limitations pulled out in seconds.

* Semantic search across a paper collection using RAG
* Side by side comparison of two papers
* Runs on OpenAI, Groq, Anthropic, Google and Ollama models

**Stack:** Python, FastAPI, FAISS, OpenAI SDK, React, TypeScript, PostgreSQL

**[Live Demo](https://researchiq-omega.vercel.app)** · **[API docs](https://researchiq.onrender.com/docs)**

### [InsightForge AI](https://github.com/alymkarim/InsightForge-AI)

Machine learning platform that trains, compares and explains models from a single dataset upload.

* Works out whether it is classification or regression, then compares several models
* Feature importance for every trained model
* Interactive dashboard for running predictions

**Stack:** Python, FastAPI, Pandas, React, TypeScript

**[Live Demo](https://insight-forge-ai-bb4f.vercel.app/)**

### [DevDesk](https://github.com/alymkarim/DevDesk)

Online store for developer workspace gear, from product catalog through checkout.

* JWT authentication with password reset, plus reviews, wishlist and discount codes
* Cart for guests and signed in users, with order tracking
* Docker Compose for local development and GitHub Actions for CI

**Stack:** FastAPI, React, TypeScript, Tailwind CSS, PostgreSQL, Stripe

**[Live Demo](https://dev-desk-nine.vercel.app)**

### [DataForge](https://github.com/alymkarim/dataforge)

Data engineering platform taking raw event data all the way to analytics ready tables.

* Bronze, Silver and Gold medallion architecture with validation at every stage
* Invalid records quarantined and lineage preserved
* Observability dashboard over the whole flow

**Stack:** Python, FastAPI, Pandas, PySpark, Delta Lake, Databricks, React, TypeScript, pytest

**[Live Demo](https://dataforge-ashen.vercel.app/)**

### [Rescue Vision](https://github.com/alymkarim/uav-human-detection)

My MSc research. Real time computer vision for finding people in aerial imagery during search and rescue operations.

* YOLOv8 with five body posture classes, around 0.81 mAP at 25 to 30 FPS on a laptop
* Dual scale and tiled inference
* Object tracking with ByteTrack

**Stack:** Python, PyTorch, YOLOv8, ByteTrack, Streamlit

**[Live Demo](https://rescuevision.streamlit.app)**

## Other projects

### Software

* **[Developer Portfolio](https://github.com/alymkarim/alya-portfolio)**: React, TypeScript, Vite. Interactive project explorer and technical blog. [Live](https://alya-portfolio-jade.vercel.app)
* **[TaskFlow](https://github.com/alymkarim/taskflow)**: task and notes app with a React frontend talking to a documented REST API. [Live](https://taskflow-six-sandy.vercel.app/) · [API docs](https://taskflow-i5u3.onrender.com/docs)
* **[DeepGuard](https://github.com/alymkarim/DeepGuard-Deepfake-Detector)**: deepfake video detector, EfficientNet trained on Vertex AI and served from ONNX. Test accuracy 0.513 and ROC AUC 0.548, and the demo page says so too. [Live](https://deep-guard-deepfake-detector.vercel.app/)
* **[UrbanTech](https://github.com/alymkarim/UTCS_Ericsson)**: Java management platform for shared workspaces, delivered by a six person Agile team. I was Scrum Master for Sprint 2.

### AI and machine learning

* **[Parkinson's Disease Prediction](https://github.com/alymkarim/Advanced-Machine-Learning-for-Health-Data-Handwriting-Classification-Parkinson-s-Disease-Regression)**: explainable ML on sensor handwriting data using Random Forest, KNN and SHAP
* **AI for MedTech**: RUN-EU collaborative research exploring AI for CT and MRI analysis

### Data and analytics

* **[Research Data Management System](https://github.com/alymkarim/Research_Project_Data_System_SQL)**: normalised schema with advanced SQL and PL/SQL queries. [Video](https://youtu.be/-6CFcrz3PiY)
* **[MongoDB Research Query Framework](https://github.com/alymkarim/Research-Project-Database-Design-using-MongoDB)**: 25 structured queries and aggregation pipelines. [Video](https://youtu.be/ImHuT0ZtSoQ)
* **[GP Practice Analytics](https://github.com/alymkarim/GP-Practice-Analytics-R-Markdown-Project)**: R, R Markdown, dplyr and ggplot2 for an Irish GP practice
* **Irish Agricultural Productivity Dashboard**: Tableau dashboard combining crop, weather and market trends for Irish regions

### Research

* **[Graphene Iron Oxide Biosensor](https://iopscience.iop.org/article/10.1088/1755-1315/842/1/012016/meta)**: award winning biosensor for detecting the mycotoxin zearalenone. SEDEX43 Gold FYP, Best Presenter, Best Poster
* **Thermally Conductive 3D Printing Resin**: nanocomposite research to improve thermal conductivity of printable resins
* **Graphene CNT Foam for Oil Spill Cleanup**: recyclable oleophilic nanomaterial foam for oil water separation
* **Dye Sensitized Solar Cells**: low cost photovoltaic research focused on improving light absorption

### Sustainability

* **[EcoZone Mapper](https://github.com/alymkarim/EcoZone-Mapper-GIS-for-Waste-Management-NASA-Space-Apps-2024-)**: GIS waste management analytics built for NASA Space Apps 2024
* **[Umbrella Green](https://github.com/alymkarim)**: modular rainwater harvesting concept for climate resilient cities. EU TalentOn second place
* **[UTP UIR Riau Community Service](https://www.facebook.com/profile.php?id=100068842090190)**: solar panel installation and science outreach for a rural island community in Indonesia. I was Vice President
* **Auto Vent**: automated vehicle ventilation to reduce hot car incidents. Made the Intel CREST semi finals
* **Aquatic Plant Wastewater Treatment**: team study of natural water treatment measured using flame AAS

## Right now

Working on: **DeepGuard**, retraining on a larger dataset and scoring videos across frames instead of one.

Learning: system design, cloud deployment, testing and CI/CD, data engineering, machine learning engineering.

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alya-karim/)

**Comfortable with:**
![My Skills](https://skillicons.dev/icons?i=py,ts,js,r,c,java,react,nodejs,postgres,docker,git,linux)

**Currently learning:**
![Learning](https://skillicons.dev/icons?i=rust,nextjs,aws)

### 🎧 Currently listening on Spotify

[![Spotify](https://spotify-github-profile.kittinanx.com/api/view?uid=12102488428&cover_image=true&theme=novatorem&bar_color=1db954&bar_color_cover=true)](https://open.spotify.com/user/12102488428)

<!---
alymkarim/alymkarim is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
