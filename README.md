<div align="center">
  <h1>Hi there, I'm <a href="#" target="_blank">Bohdan Senkiv (nwrslept)</a> 👨‍💻</h1>
  <h3>Middle-Focused Backend Developer | System Architect</h3>

  <p>
    I build <b>resilient</b> and <b>scalable</b> server-side applications with a focus on data integrity, 
    concurrency management, and automated infrastructure.
  </p>

  <a href="https://t.me/nwrslept">
    <img src="https://img.shields.io/badge/Telegram-Contact_Me-blue?style=for-the-badge&logo=telegram" alt="Telegram" />
  </a>
  <a href="senkivb44@gmail.com">
    <img src="https://img.shields.io/badge/Email-Send_Email-D14836?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</div>

<br />

---

### 🛠️ Core Stack & Expertise

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  
  <img src="https://img.shields.io/badge/Django_5-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django_Rest_Framework-A30000?style=for-the-badge&logo=django&logoColor=white" />

  <img src="https://img.shields.io/badge/PostgreSQL_15-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_&_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white" />
  
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Poetry-60A5FA?style=for-the-badge&logo=poetry&logoColor=white" />
</div>

<br />

---

### 🚀 Key Projects

#### 🏭 [SmartWarehouse API]([LINK](https://github.com/nwrslept/SmartWarehouse.git))
> **Advanced Inventory & Logistics Management System**



* **Architecture & Design:** Implemented a **Service Layer** to maintain clean separation between HTTP handling and complex business logic.
* **Challenge:** Solved the **"Double Spend" problem** in inventory management. Multiple concurrent requests for the same SKU are handled using `select_for_update` row-level locking.
* **Infrastructure:** Full Dockerization with PostgreSQL and Gunicorn. Includes automated DB seeding and comprehensive stress tests for concurrency.
* **Tech:** Python 3.11, Django 5, DRF, PostgreSQL, Docker, Pytest.

#### ⚡ [EventFlow]([LINK](https://github.com/nwrslept/EventFlow.git))
> **Asynchronous Event Tracking & Management System**

* **Performance:** Built on **FastAPI** to leverage asynchronous I/O for high-throughput registration flows.
* **Data Integrity:** Heavy use of **Pydantic** for strict data validation and **SQLAlchemy (Async)** for non-blocking database operations.
* **Key Feature:** Designed a scalable Dependency Injection system for easier testing and modularity.
* **Tech:** Python, FastAPI, SQLAlchemy, Alembic, PostgreSQL.

---

### 📊 Professional Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=dark&hide_border=true" />
</div>

<br />

---

### 🧠 My Principles
- **Code is for humans:** Writing clean, self-documenting code with comprehensive docstrings and types.
- **Tests are not optional:** If it's not tested, it's broken. Focus on Unit, Integration, and Concurrency testing.
- **Automation is key:** If a task is repeated twice, it should be a script or a Docker command.

<div align="center">
  <i>Open for collaborations on interesting Backend & Architecture challenges!</i>
</div>
