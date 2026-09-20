<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=230&section=header&color=0:4F46E5,100:7C3AED&text=YONG%20LYHOR&fontSize=52&fontColor=ffffff&fontAlignY=42&desc=Data%20Science%20Student%20%C2%B7%20AI%20%C2%B7%20Data%20Engineering&descFontSize=18&descAlignY=62&animation=twinkling)

![typing](https://readme-typing-svg.demolab.com/?duration=3500&pause=400&color=6C63FF&center=true&vCenter=true&width=760&height=60&lines=Data+Science+Student+%40+Institute+of+Technology+of+Cambodia;Building+real-time+data+pipelines+with+Airflow+%26+Spark;Machine+Learning+with+TensorFlow+%26+scikit-learn;FastAPI+backends+%2B+Docker+-+from+data+to+product;Khmer+%2B+English+NLP+and+RAG+chatbots)

</div>

```text
$ whoami
> YONG Lyhor
> Data Science student at Institute of Technology of Cambodia (ITC) - 4th year
> Interests: Data Engineering | Machine Learning | AI | Backend | IoT data

$ echo what_i_build
> real-time ETL pipelines, ML/DL models, REST APIs, interactive dashboards

$ ls ./now
> real-time weather ETL  (Airflow + PySpark + PostgreSQL + Streamlit)
> IoT telemetry platform (EMQX + FastAPI + TimescaleDB)
> Khmer NLP translator  (TensorFlow LSTM)
> RAG Khmer tutor       (LLM + GPT-4o)
```

---

## About Me

I'm a data-focused developer who works across the full data lifecycle — from ingesting
streaming sensor data over MQTT to orchestrating ETL pipelines, training ML/DL models,
and serving insights through FastAPI backends and interactive dashboards.

- 🎓 Fourth-year **Data Science** student at **ITC**
- 🧠 Currently building: **real-time ETL pipelines**, **RAG / LLM applications**, and **REST APIs**
- 📈 Focus: **Data Engineering · Machine Learning · Backend Engineering · IoT Data**
- 🛠️ Passionate about turning raw data into clean, reliable, and useful systems

---

## GitHub Statistics & Contribution Streak

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=YongLyhor&theme=github-dark-blue&hide_border=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=YongLyhor&theme=default&hide_border=true">
  <img alt="Contribution streak" src="https://github-readme-streak-stats.herokuapp.com/?user=YongLyhor&theme=github-dark-blue&hide_border=true">
</picture>

**29 public repositories · 5 followers · 4 following · GitHub Pro · 79 total contributions (longest streak: 5 days)**

</div>

---

## Contribution Activity

### Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="output/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake" src="output/github-contribution-grid-snake.svg">
</picture>

### Pac-Man Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="output/pacman-contribution-graph.svg">
  <img alt="Pac-Man contribution graph" src="output/pacman-contribution-graph.svg">
</picture>

### 3D Contribution Calendar

<img src="profile-3d-contrib/profile-season-animate.svg" alt="3D contribution calendar" width="100%">

---

## Tech Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,java,js,ts,react,vue,fastapi,spring,postgres,mysql,docker,git,github,linux&perline=8&theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,java,js,ts,react,vue,fastapi,spring,postgres,mysql,docker,git,github,linux&perline=8&theme=light">
  <img alt="Tech stack" src="https://skillicons.dev/icons?i=python,java,js,ts,react,vue,fastapi,spring,postgres,mysql,docker,git,github,linux&perline=8&theme=dark">
</picture>

**Data & AI:** Python · Pandas · NumPy · scikit-learn · TensorFlow · Keras · Apache Spark / PySpark · Apache Airflow · Streamlit

**Backend:** FastAPI · Spring Boot · REST APIs · JWT

**Data & IoT:** PostgreSQL · MySQL · TimescaleDB · MQTT · EMQX

**DevOps & Tools:** Docker · Git · GitHub Actions · Jenkins

</div>

---

## Data Engineering Pipeline

```text
[ Data Sources ]   [ Ingestion ]    [ Processing ]    [ Storage ]      [ Serving ]
    Weather API  →   Airflow DAG  →  PySpark ETL  →   PostgreSQL  →   Streamlit
      Sensors         (schedules)     (transform +     (raw & clean)   dashboard
      (EMQX MQTT)     & retries)      validate)        TimescaleDB     + FastAPI
```

---

## Project Architectures

### Real-Time Weather ETL Pipeline

```text
[ Open-Meteo API (8 cities) ]
             │
             ▼
[ Apache Airflow ]  → schedules & retries
             │
             ▼
[ PySpark (3.5) ]  → transform, clean, validate
             │
             ▼
[ PostgreSQL 15 ]  → raw + cleaned tables
             │
             ▼
[ Streamlit ]  → live weather dashboard
```

**Apache Airflow · Apache Spark / PySpark · PostgreSQL · Streamlit · Docker**

[![Repo](https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/YongLyhor/Real-Time_Weather_Pipline_ETL-)

### IoT Platform API (MQTT · EMQX)

```text
[ Smart-meter / sensors ]
             │
             ▼
[ EMQX MQTT Broker ]
             │
             ▼
[ FastAPI consumer (paho-mqtt) ]  → validate & persist
             │
             ▼
[ TimescaleDB ]  → time-series storage
             │
             ▼
[ REST API / monitoring dashboards ]
```

**MQTT · EMQX · FastAPI · SQLAlchemy · Alembic · TimescaleDB · Docker**

[![Repo](https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/YongLyhor/Test_emqx)

---

## Featured Projects

<div align="center">

<table>
  <tr>
    <td width="50%">
      <h3 align="center">Real-Time Weather ETL Pipeline</h3>
      <p align="center">End-to-end data engineering pipeline collecting live weather data for 8 Cambodian cities - orchestrated with Airflow, transformed with PySpark, stored in PostgreSQL, served via Streamlit, fully containerized with Docker.</p>
      <p align="center"><b>Airflow · PySpark · PostgreSQL · Streamlit · Docker</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/Real-Time_Weather_Pipline_ETL-"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
    <td width="50%">
      <h3 align="center">IoT Platform API (MQTT · EMQX)</h3>
      <p align="center">IoT data platform for smart-meter sensor telemetry - an EMQX MQTT broker feeds a FastAPI service that ingests, validates, and stores time-series sensor readings in TimescaleDB.</p>
      <p align="center"><b>MQTT · EMQX · FastAPI · TimescaleDB · Docker</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/Test_emqx"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">English-to-Khmer Translator</h3>
      <p align="center">Sequence-to-sequence machine translation model built with TensorFlow/Keras (LSTM) and deployed as an interactive Streamlit app.</p>
      <p align="center"><b>TensorFlow · Keras · LSTM · Streamlit</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/English-to-Khmer-Translator"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
    <td width="50%">
      <h3 align="center">Image Caption Generator</h3>
      <p align="center">Deep learning image captioning system combining computer vision and NLP, served through a Streamlit interface.</p>
      <p align="center"><b>TensorFlow · Image Captioning · Streamlit</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/Image-Caption-Generator"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Rice Yield Prediction System</h3>
      <p align="center">Machine learning project predicting rice yield using scikit-learn models, exposed through a web interface.</p>
      <p align="center"><b>scikit-learn · Python · Web</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/Rice-Yield-Prediction-System"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
    <td width="50%">
      <h3 align="center">Student Management System API</h3>
      <p align="center">RESTful backend built with FastAPI and PostgreSQL for managing students, teachers, and courses - with JWT authentication, Docker Compose, and Alembic migrations.</p>
      <p align="center"><b>FastAPI · PostgreSQL · JWT · Docker</b></p>
      <p align="center"><a href="https://github.com/YongLyhor/demo_fastapi_student_ms"><img src="https://img.shields.io/badge/View%20Repository-181717?style=flat&logo=github&logoColor=white" alt="Repo"></a></p>
    </td>
  </tr>
</table>

</div>

---

<!--
The snake, Pac-Man, and 3D contribution visuals are refreshed automatically by the workflows in .github/workflows/ .
Run each workflow manually once after pushing (Actions → Run workflow) so the initial SVGs are generated.
github-readme-stats and github-profile-trophy are currently unavailable (HTTP 503/402), so live stat cards from those services are intentionally not included.
-->

## Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/YongLyhor)
[![All Repositories](https://img.shields.io/badge/All%20Repositories-181717?style=flat&logo=github&logoColor=white)](https://github.com/YongLyhor?tab=repositories)

</div>