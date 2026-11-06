<div align="center">

<!-- Animated Waving Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,26&height=220&section=header&text=Sayed%20Elmasry&fontSize=42&fontAlignY=36&desc=Big%20Data%20Engineer%20%7C%20Lakehouse%20Architect&descAlignY=58&descSize=19" width="100%" alt="Sayed Elmasry Header" />

<!-- Dynamic Animated Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00D2FF&center=true&vCenter=true&width=650&lines=Big+Data+Engineer+%26+Lakehouse+Architect;Distributed+Systems+%26+Real-Time+Streaming;Apache+Spark+%7C+Iceberg+%7C+Kafka+%7C+dbt+%7C+Trino;Sub-10ms+Low-Latency+Inference+%26+CDC;Generative+AI+%26+LLM+Pipelines+(RAG))](https://git.io/typing-svg)

<br>

<!-- Hero Socials & Live Portfolio Button -->
<p align="center">
  <a href="https://sayedelmasry.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Live_Portfolio-00DF8F?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/sayed-elmasry" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:elsayed.elmasry456@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/SayedELMASRY2">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://wa.me/201092200821" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-+20_109_220_0821-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
</p>

<!-- Animated Rainbow Divider -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

</div>

### <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="28px"> About Me

I am a **Big Data & Data Engineer** with a strong mathematical background (**B.Sc. in Mathematics, Mansoura University**). I specialize in designing and scaling high-performance **Medallion Lakehouse architectures**, **real-time streaming pipelines**, and **low-latency inference systems**.

- 🎓 **Academic Foundation:** Mathematics & Theoretical Statistics — Mansoura University *(Graduation: 2027)*.
- 🌐 **Interactive Portfolio:** Explore my live work and interactive systems at [**sayedelmasry.vercel.app**](https://sayedelmasry.vercel.app).
- ⚡ **Core Philosophy:** ACID transactions on open table formats (Apache Iceberg), sub-10ms data serving, zero-penny variance ($0.00) in dimensional marts, and rigorous end-to-end testing.

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />
</div>

### 🚀 Top Featured Projects

<table>
  <!-- Project 1 -->
  <tr>
    <td width="100%">
      <div align="between">
        <h3>💳 Real-Time Payment Ingestion & Anti-Fraud Lakehouse</h3>
      </div>
      <p><b>High-throughput streaming ingestion with sub-10ms real-time fraud scoring.</b></p>
      <ul>
        <li>Engineered zero-bottleneck streaming ingestion (<b>10–100 TPS</b>) using <b>FastAPI</b> and <b>PostgreSQL CDC (Debezium WAL)</b>, streaming transactional events directly to an <b>Amazon S3 Medallion Bronze</b> lakehouse.</li>
        <li>Implemented <b>sub-10ms real-time fraud scoring</b> by deploying a 34-feature <b>LightGBM</b> model hydrated via <b>AWS ElastiCache Redis (~1.1ms)</b>, backed by automated Dead-Letter Queue (DLQ) routing and <b>168 automated tests</b>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS_S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
        <img src="https://img.shields.io/badge/ElastiCache_Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Debezium_CDC-009688?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/LightGBM-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <p>
        <a href="https://github.com/SayedELMASRY2/Anti-Fraud-Lakehouse">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Repository" />
        </a>
      </p>
    </td>
  </tr>

  <!-- Project 2 -->
  <tr>
    <td width="100%">
      <div align="between">
        <h3>🏛️ Enterprise Real-Time Big Data Platform</h3>
      </div>
      <p><b>Medallion Lakehouse with open table formats, ACID transactions, and automated table maintenance.</b></p>
      <ul>
        <li>Architected a <b>Medallion Lakehouse (Bronze/Silver/Gold)</b> ingesting streaming events via <b>Apache Kafka (KRaft)</b> into MinIO S3 with <b>Apache Iceberg ACID tables</b> and <b>Project Nessie REST catalog</b>.</li>
        <li>Built dimensional Kimball star-schema marts with <b>dbt-trino</b> processing <b>530K+ records and $500M+ volume</b>, enforcing a <b>9-invariant data quality gate for $0.00 zero-penny variance</b>.</li>
        <li>Automated lakehouse orchestration and table maintenance (Parquet 128MB bin-packing and snapshot expiration) using <b>Apache Airflow</b>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Apache_Iceberg-008080?style=flat-square&logo=apache&logoColor=white" />
        <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white" />
        <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
        <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
        <img src="https://img.shields.io/badge/MinIO-C72C48?style=flat-square&logo=minio&logoColor=white" />
        <img src="https://img.shields.io/badge/Project_Nessie-00B4D8?style=flat-square&logo=git&logoColor=white" />
        <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
      </p>
      <p>
        <a href="https://github.com/SayedELMASRY2/Real-Time-Big-Data-Platform">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Repository" />
        </a>
      </p>
    </td>
  </tr>
</table>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />
</div>

### 💼 Top Experience & Industry Traineeships

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>🏢 Samsung Innovation Campus</h4>
      <p><b>Big Data Engineering Trainee</b><br><code>Jul 2026 – Nov 2026</code></p>
      <ul>
        <li>Specialized in distributed computing architectures using <b>Apache Spark (RDDs, DataFrames, Catalyst Optimizer)</b>.</li>
        <li>Studied real-time streaming architectures, Kafka event broker internals, Medallion Lakehouse patterns, and enterprise-scale orchestration.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>📈 Stunning</h4>
      <p><b>Data Analyst</b><br><code>May 2026 – Aug 2026</code></p>
      <ul>
        <li>Led product analytics and event tracking, analyzing user journeys and behavioural datasets for <b>200K+ users</b> via Microsoft Clarity and SQL.</li>
        <li>Engineered conversion funnels, cohort analysis, and product KPI tracking (retention, churn), translating raw event streams into actionable BI.</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🤖 Information Technology Institute (ITI)</h4>
      <p><b>Generative AI Trainee</b><br><code>Nov 2025 – Feb 2026</code></p>
      <ul>
        <li>Focused on Generative AI data engineering, vector embeddings, chunking algorithms, and semantic retrieval pipelines (<b>RAG</b>).</li>
        <li>Designed prompt orchestration, unstructured text preprocessing, and LLM integration with structured databases and APIs.</li>
      </ul>
    </td>
  </tr>
</table>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />
</div>

### 🛠️ Tech Stack & Tooling

<div align="center">

<p>
  <b>Languages:</b><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-CC292B?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
</p>

<p>
  <b>Data Engineering & Lakehouse:</b><br>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Iceberg-008080?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Debezium_CDC-009688?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72C48?style=for-the-badge&logo=minio&logoColor=white" />
</p>

<p>
  <b>Cloud & Storage:</b><br>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p>
  <b>ML, GenAI & Analytics:</b><br>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS_Vector_DB-0466C8?style=for-the-badge&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
</p>

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />
</div>

### 📈 GitHub Analytics & Motion Stats

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="middle">
        <img src="https://github-readme-stats-fast.vercel.app/api?username=SayedELMASRY2&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub Stats" />
      </td>
      <td align="center" valign="middle">
        <img src="https://streak-stats.demolab.com/?user=SayedELMASRY2&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=SayedELMASRY2&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

<br>

<div align="center">

<!-- Footer Waving Animated Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,26&height=100&section=footer" width="100%" alt="Sayed Elmasry Footer" />

<p>
  <a href="https://sayedelmasry.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Explore_Full_Portfolio-00DF8F?style=for-the-badge&logo=vercel&logoColor=black" alt="Live Portfolio" />
  </a>
  <a href="https://linkedin.com/in/sayed-elmasry" target="_blank">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:elsayed.elmasry456@gmail.com">
    <img src="https://img.shields.io/badge/Get_in_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>
