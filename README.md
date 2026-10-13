<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B3D,100:1F6FEB&height=200&section=header&text=Ruchita%20Singla&fontSize=52&fontColor=FFFFFF&fontAlignY=40&desc=Machine%20Learning%20%7C%20MLOps%20%7C%20Python&descSize=18&descAlignY=62" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=1000&color=1F6FEB&center=true&vCenter=true&width=700&lines=Hey+there!+I'm+Ruchita+%F0%9F%91%8B;Machine+Learning+%26+MLOps+Engineer;I+build+ML+models+and+the+pipelines+that+ship+them;Open+to+Work" alt="Typing SVG" />
</a>

<br>
<br>

<img src="https://komarev.com/ghpvc/?username=ruchitasingla&label=Profile%20Views&color=1F6FEB&labelColor=0D1B3D&style=for-the-badge" />
<a href="https://ruchitasingla.github.io/Portfolio/">
  <img src="https://img.shields.io/badge/Portfolio-Visit%20Site-1F6FEB?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0D1B3D"/>
</a>
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-1F6FEB?style=for-the-badge&logo=target&logoColor=white&labelColor=0D1B3D" />

</div>

---

## `~$ whoami`

### About me

```python
class Ruchita:
    def __init__(self):
        self.role      = "Machine Learning & MLOps Engineer (Fresher)"
        self.education = "B.Tech CSE @ JUIT (2022 – 2026)"
        self.location  = "India"
        self.languages = ["Python", "SQL", "C++"]
        self.focus     = ["Machine Learning", "CI/CD & Automation", "Cloud Deployment"]
        self.learning  = ["Kubernetes", "Terraform"]
        self.status    = "Open to Work"

    def philosophy(self):
        return "Learn by building. Ship models that are tested, secure and monitored."
```

- I train and evaluate **ML models** with Python and Scikit-learn
- I automate **testing, security scanning, deployment and monitoring** with Jenkins, GitHub Actions and Docker
- I deploy ML services on **AWS EC2** and watch them with **Prometheus and Grafana**
- Currently learning **Kubernetes** and **Terraform**
- See my work on my portfolio: **[ruchitasingla.github.io/Portfolio](https://ruchitasingla.github.io/Portfolio/)**

```bash
$ ./pipeline --run ruchita
[ok] lint ........ clean, tested code
[ok] test ........ models validated before release
[ok] scan ........ images checked with Trivy
[ok] deploy ...... AWS EC2, automated
[ok] monitor ..... Prometheus + Grafana
$ status: open_to_work
```

### Experience

**Machine Learning Intern** · Yhills Edutech Pvt. Ltd. (Remote) · `Jun 2025 – Jul 2025`

- Built data cleaning and preprocessing workflows in Python and Pandas
- Ran exploratory data analysis and feature preparation
- Trained and evaluated regression and classification models with Scikit-learn

### Education

**B.Tech in Computer Science & Engineering** · Jaypee University of Information Technology (JUIT)
`2022 – 2026` · **CGPA: 7.7 / 10**

---

## `~$ ls ./stack`

### Machine Learning & Data
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

### CI/CD & DevOps
<p>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

### Cloud, Backend & Monitoring
<p>
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
</p>

### Currently Learning
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

---

## `~$ cat ./projects.log`

### Churn MLOps · End-to-End ML Pipeline with CI/CD

A GitHub Actions pipeline that **lints, tests, retrains, validates, scans and deploys** a churn model to AWS EC2 on every push to `main`.

- **Model quality gate** (minimum ROC AUC plus regression checks) blocks weaker models
- Experiments tracked with **MLflow**
- **Trivy** found three HIGH-severity vulnerabilities in a dependency, fixed by upgrading FastAPI
- **Prometheus** metrics and **Grafana** dashboards for API performance and prediction drift

**Built with:** `Python` `FastAPI` `MLflow` `Docker` `GitHub Actions` `AWS EC2` `Prometheus` `Grafana`

<a href="https://github.com/ruchitasingla/churn-mlops">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#E7F0FF","primaryBorderColor":"#1F6FEB","primaryTextColor":"#0D1B3D","lineColor":"#1F6FEB"}}}%%
flowchart LR
    A[git push] --> B[Lint]
    B --> C[Test]
    C --> D[Retrain]
    D --> E{Quality gate}
    E -->|passes| F[Trivy scan]
    F --> G[Deploy to AWS EC2]
    G --> H[Prometheus + Grafana]
    E -->|fails| X[Build stops]
```

---

### Mental Health Signal · ML App with Jenkins CI/CD on AWS

Predicts a student's **mental health score (0 to 10)** from daily habits like sleep, screen time, study hours and stress.

- Random Forest trained on **5,000 records** and **12 features**: **R² 0.878, MAE 0.35** on held-out data
- One Scikit-learn Pipeline, so training and serving use identical preprocessing
- Served with **FastAPI** behind **Nginx** and packaged as Docker images with Docker Compose
- **Jenkins** pipeline on every push: ruff lint, pytest, build, Trivy scan, Docker Hub push, deploy to AWS EC2 and a smoke test

**Built with:** `Python` `Scikit-learn` `FastAPI` `Docker` `Jenkins` `Trivy` `AWS EC2` `Nginx`

<a href="https://github.com/ruchitasingla/mental_health_recorder">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

### Customer Behavior Analysis · Data Analytics

An end-to-end analytics workflow (data preparation, modeling, SQL analysis, visualization and reporting) that turns raw customer data into insights on purchasing behavior, segments and loyalty.

**Built with:** `Python` `Pandas` `PostgreSQL` `Power BI`

<a href="https://github.com/ruchitasingla/Customer_behavior_analysis">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## `~$ gh stats --user ruchitasingla`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ruchitasingla&show_icons=true&rank_icon=github&bg_color=0D1B3D&title_color=58A6FF&text_color=FFFFFF&icon_color=58A6FF&border_color=1F6FEB" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ruchitasingla&layout=compact&bg_color=0D1B3D&title_color=58A6FF&text_color=FFFFFF&border_color=1F6FEB" />

</div>

---

## `~$ ./connect.sh`

<div align="center">

<a href="https://ruchitasingla.github.io/Portfolio/">
  <img src="https://img.shields.io/badge/Portfolio-ruchitasingla.github.io-1F6FEB?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0D1B3D"/>
</a>
<a href="https://www.linkedin.com/in/ruchita-singla/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:ruchitasingla001@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/ruchitasingla">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

<i>Open to internships and full-time roles in Machine Learning and MLOps.</i>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1B3D&height=100&section=footer" width="100%"/>

</div>
