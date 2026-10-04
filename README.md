![Banner](f3606ae3-29b8-4c39-88eb-8be921db43ac.png)

# Hi, I'm Alya

I build software: full-stack apps, machine learning pipelines, and the data work underneath them. I'm based in Ireland.

I completed my MSc in Data Analytics at TUS, where I built a drone-assisted human detection system for search and rescue, using YOLOv5 and YOLOv8 to pick people out of aerial footage. Before that, a Certificate in Software Engineering with Ericsson, where I was Scrum Master in Sprint 2, and a BSc in Applied Physics at UTP, which is where programming started for me: C and an Arduino.

Physics into data into engineering is a strange path, but it means I'm comfortable anywhere from a database schema to a training run. Lately I've been leaning into software engineering while keeping the data science sharp.

Outside of code: film photography, painting, journaling, and Spotify.

---

## Featured Projects

### [DevDesk](https://github.com/alymkarim/DevDesk)

E-commerce store for developer workspace gear, from product catalog through Stripe checkout.

- JWT authentication with password reset
- Reviews, wishlist and discount codes (percentage or fixed amount)
- Order tracking with a four step status timeline
- Cart that works for both guests and signed in users
- Docker Compose for local development, GitHub Actions for CI

**Stack:** FastAPI, React, TypeScript, Tailwind CSS, PostgreSQL, Stripe

**[Live Demo](https://dev-desk-nine.vercel.app)**

---

### [ResearchIQ](https://github.com/alymkarim/researchiq)

Research paper analysis platform. Upload PDFs and get objectives, methodology, findings, strengths and limitations pulled out in seconds.

- Semantic search across a paper collection
- Side by side comparison of two papers
- Conversational Q&A over your own papers using RAG
- Paper discovery from Semantic Scholar and arXiv
- Word clouds, keyword networks and methodology timelines
- Export analysis as PDF or DOCX

**Stack:** Python, FastAPI, SQLAlchemy, FAISS, scikit-learn, OpenAI SDK, React, TypeScript, PostgreSQL on Supabase

**[Live Demo](https://researchiq-omega.vercel.app)** · **[API docs](https://researchiq.onrender.com/docs)**

---

### [InsightForge AI](https://github.com/alymkarim/InsightForge-AI)

Machine learning platform that trains, compares and explains models from a single dataset upload.

- Adapts automatically to classification and regression targets
- Trains and compares several models side by side
- Feature importance for every trained model
- Interactive dashboard for running predictions
- Accepts CSV, Excel and structured PDF data

**Stack:** Python, FastAPI, Pandas, scikit-learn, React, TypeScript

**[Live Demo](https://insight-forge-ai-bb4f.vercel.app/)**

---

### [DataForge](https://github.com/alymkarim/dataforge)

Data engineering platform taking raw event data all the way to analytics ready tables.

- Bronze, Silver and Gold medallion architecture
- Automated data quality validation at every stage
- Invalid records quarantined with lineage preserved
- Pipeline execution history and run tracking
- Observability dashboard over the whole flow
- PySpark and Delta Lake for distributed processing

**Stack:** Python, FastAPI, Pandas, PySpark, Delta Lake, Databricks, React, TypeScript, pytest

**[Live Demo](https://dataforge-ashen.vercel.app/)**

---

### [TaskFlow](https://github.com/alymkarim/taskflow)

Task and notes app with a React frontend talking to a documented REST API.

- Create, complete and delete tasks with optional notes
- FastAPI REST API with Pydantic validation
- API and integration test suite
- Frontend on Vercel, API on Render, database on Supabase

**Stack:** React, TypeScript, FastAPI, SQLAlchemy, PostgreSQL, Docker

**[Live Demo](https://taskflow-six-sandy.vercel.app/)** · **[API docs](https://taskflow-i5u3.onrender.com/docs)**

---

### [Rescue Vision: Drone-Assisted Human Detection](https://github.com/alymkarim/uav-human-detection)

My MSc research. Real-time computer-vision pipeline for detecting people in aerial imagery for search and rescue operations.

- YOLOv8 with five body-posture classes
- ~0.81 mAP@0.5, ~25-30 FPS on laptop
- Dual-scale and tiled inference
- Object tracking with ByteTrack

**Stack:** Python, PyTorch, YOLOv8, ByteTrack, Streamlit

**[Live Demo](https://rescuevision.streamlit.app)**

---

### [DeepGuard (Deepfake Detection)](https://github.com/alymkarim/DeepGuard-Deepfake-Detector)

Deepfake video detector. EfficientNet-B0 trained on Vertex AI, exported to ONNX and served from a Flask function on Vercel. Scores a video frame by frame and shows the test metrics next to the verdict.

- Videos split 70/15/15 before any frames are extracted, so no video leaks across the split
- Two-stage training: frozen backbone first, then the last two blocks fine-tuned
- ONNX export verified against PyTorch before it ships
- Face detection in the browser with MediaPipe, only the face crops get uploaded
- Test accuracy 0.513, ROC-AUC 0.548 — the demo page says so too

**Stack:** Python, PyTorch, EfficientNet-B0, ONNX Runtime, Flask, Streamlit, MediaPipe, OpenCV, Vertex AI

**[Live Demo](https://deep-guard-deepfake-detector.vercel.app/)**

---

## Other Projects

### Software

**[Developer Portfolio](https://github.com/alymkarim/alya-portfolio)** — React, TypeScript, Vite. Responsive portfolio with interactive project explorer and technical blog. [Live](https://alya-portfolio-jade.vercel.app)

**[UrbanTech Co-Working Spaces](https://github.com/alymkarim/UTCS_Ericsson)** — Java management platform delivered by a six-person Agile team. Authentication, workspace reservations, financial reporting. Served as Scrum Master for Sprint 2.

---

### AI and Machine Learning

**[Parkinson's Disease Prediction](https://github.com/alymkarim/Advanced-Machine-Learning-for-Health-Data-Handwriting-Classification-Parkinson-s-Disease-Regression)** — Explainable ML using sensor-based handwriting data. Random Forest, Decision Trees, KNN with SHAP feature interpretation.

**AI for MedTech** — RUN-EU collaborative research exploring AI for CT and MRI analysis. International multidisciplinary project on medical imaging.

---

### Data Engineering and Analytics

**[Research Data Management System](https://github.com/alymkarim/Research_Project_Data_System_SQL)** — Relational database for scientists, research projects, funding and outcomes. Normalised schema with advanced SQL and PL/SQL queries. [Video](https://youtu.be/-6CFcrz3PiY)

**[MongoDB Research Query Framework](https://github.com/alymkarim/Research-Project-Database-Design-using-MongoDB)** — NoSQL research dataset with 25 structured queries and aggregation pipelines. [Video](https://youtu.be/ImHuT0ZtSoQ)

**[GP Practice Analytics](https://github.com/alymkarim/GP-Practice-Analytics-R-Markdown-Project)** — Operational analytics and reporting for an Irish GP practice. R, R Markdown, dplyr, ggplot2.

**Irish Agricultural Productivity Dashboard** — Tableau dashboard combining crop, weather and market trends for Irish regions.

---

### Research

**[Graphene-Iron Oxide Biosensor](https://iopscience.iop.org/article/10.1088/1755-1315/842/1/012016/meta)** — Award-winning impedimetric biosensor for detecting the mycotoxin zearalenone. SEDEX43 Gold FYP Award, Best Presenter, Best Poster.

**Thermally Conductive 3D-Printing Resin** — Nanocomposite research to improve thermal conductivity of printable resins.

**[Graphene/CNT Foam for Oil-Spill Cleanup](https://github.com/alymkarim)** — Recyclable oleophilic nanomaterial foam for oil-water separation.

**Dye-Sensitized Solar Cells** — Low-cost photovoltaic research focused on improving light absorption.

---

### Sustainability

**[EcoZone Mapper](https://github.com/alymkarim/EcoZone-Mapper-GIS-for-Waste-Management-NASA-Space-Apps-2024-)** — GIS waste-management analytics built for NASA Space Apps 2024.

**[Umbrella Green](https://github.com/alymkarim)** — Award-winning modular rainwater-harvesting concept for climate-resilient cities. EU TalentOn second place.

**[UTP-UIR Riau Community Service](https://www.facebook.com/profile.php?id=100068842090190)** — Solar-panel installation and science outreach for a rural island community in Indonesia. Served as Vice President.

**Auto-Vent** — Automated vehicle ventilation concept to reduce hot-car incidents. Intel CREST semi-finalist.

**Aquatic-Plant Wastewater Treatment** — Team study of natural water treatment measured using flame AAS.

---

## Currently Working On

- **DeepGuard** — retraining on a larger dataset, then scoring videos across frames instead of one frame at a time

---

## Learning

- Full-stack development
- System design and software architecture
- Cloud deployment
- Testing and CI/CD
- Data engineering
- Machine learning engineering

---

## Connect

[LinkedIn](https://www.linkedin.com/in/alya-karim/)

**Comfortable with:**
![My Skills](https://skillicons.dev/icons?i=py,r,js,html,css,c,java)

**Currently learning:**
![Learning](https://skillicons.dev/icons?i=react,nodejs,nextjs,stripe)

### 🎧 Currently Listening on Spotify
[![Spotify](https://spotify-github-profile.kittinanx.com/api/view?uid=12102488428&cover_image=true&theme=novatorem&bar_color=1db954&bar_color_cover=true)](https://open.spotify.com/user/12102488428)



<!---
alymkarim/alymkarim is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

