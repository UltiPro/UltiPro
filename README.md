<h1 align="center">Hi, I'm Patryk "Ulti" Wójtowicz :wave:</h1>

<img src="https://github-readme-stats-n50491bd0-ulti-9504.vercel.app/api/top-langs/?username=UltiPro&langs_count=10&layout=pie&theme=dark&text_color=ffffff&border_radius=0&hide=HTML,Java,Objective-C,SHELL,Makefile,HACK,GLSL,Lua,Dockerfile" alt="Patryk 'Ulti' Wójtowicz Most Used Languages" align="right" width="350"/>

### 👉 Full-Stack & ML Engineer

<img src="https://skillicons.dev/icons?i=html" width="60"/> <img src="https://skillicons.dev/icons?i=css" width="60"/> <img src="https://skillicons.dev/icons?i=bootstrap" width="60"/> <img src="https://skillicons.dev/icons?i=sass" width="60"/> <img src="https://skillicons.dev/icons?i=tailwind" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=js" width="60"/> <img src="https://skillicons.dev/icons?i=jquery" width="60"/> <img src="https://skillicons.dev/icons?i=ts" width="60"/> <img src="https://skillicons.dev/icons?i=angular" width="60"/> <img src="https://skillicons.dev/icons?i=vue" width="60"/> <img src="https://skillicons.dev/icons?i=react" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=dotnet" width="60"/> <img src="https://skillicons.dev/icons?i=cs" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=py" width="60"/> <img src="https://skillicons.dev/icons?i=django" width="60"/> <img src="https://skillicons.dev/icons?i=flask" width="60"/> <img src="https://skillicons.dev/icons?i=sklearn" width="60"/> <img src="https://skillicons.dev/icons?i=tensorflow" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=c" width="60"/> <img src="https://skillicons.dev/icons?i=cpp" width="60"/> <img src="https://skillicons.dev/icons?i=rust" width="60"/> <img src="https://skillicons.dev/icons?i=php" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=git" width="60"/> <img src="https://skillicons.dev/icons?i=docker" width="60"/> 
<img src="https://skillicons.dev/icons?i=gcp" width="60"/> 
<br/>
<img src="https://skillicons.dev/icons?i=unity" width="60"/> <img src="https://skillicons.dev/icons?i=godot" width="60"/> <img src="https://skillicons.dev/icons?i=unreal" width="60"/> 

<hr/>

<img src="https://komarev.com/ghpvc/?username=UltiPro&color=blueviolet&style=for-the-badge" alt="Patryk 'UltiPro' Wójtowicz Profile Views" align="right" width="350" height="60"/>

<a href="https://www.linkedin.com/in/patryk-ulti-wojtowicz/"><img src="./icons/linkedin.svg" width="60"/></a>
<a href="https://www.facebook.com/patryk.ulti/"><img src="./icons/facebook.svg" width="60"/></a>
<a href="https://www.instagram.com/ulti_pl/"><img src="./icons/instagram.svg" width="60"/></a>
<a href="https://steamcommunity.com/id/ulti_pro/"><img src="./icons/steam.svg" width="60"/></a>

<hr/>

### 💼 Professional Experience

**DS360 — Full-Stack & ML Engineer**  
*July 2024 – Present*

🛠️ **Expansion Models** — a production ML platform deciding where a retail chain opens its next
store. Four models behind one API: predicted turnover of a new location, cannibalisation of the
stores around it, twin-store lookup and seasonality.

- **ML service** — Flask + flask-smorest REST API with an OpenAPI/Swagger contract and marshmallow
  validation, serving LightGBM and scikit-learn models (regression, classification, similarity
  search) together with prediction intervals. Containerised and deployed to Cloud Run across
  dev/stg/prod behind Identity-Aware Proxy, with a one-command deployment script
  (Cloud Build → Artifact Registry → Cloud Run).
- **Network simulation** — one request scoring several openings, relocations and closures at once:
  cannibalisation composed across overlapping catchment areas, turnover of the affected network
  before and after the change, and twin-store suggestions for every new location.
- **Geospatial feature engineering** — a bronze/silver/gold pipeline on PostgreSQL + PostGIS and
  BigQuery: OpenStreetMap data, walk- and drive-time isochrones from an external service, POI
  density and distance decay — several hundred features per location.
- **MLOps** — model artefacts versioned in GCS, every prediction historised to BigQuery for
  monitoring and back-testing, structured logging in Cloud Logging, scheduled data refresh in
  Cloud Composer (Airflow).

📊 **Project Management** — led the migration of a client's suite of web applications: independent
tools serving different departments under one solution, running on an ageing PHP version and on VMs
that kept filling their own disks until they died. They now run as containers on Hetzner against a
shared database. The work also covered the environment itself: configuration, and fixes to code and
outdated libraries inherited from the old stack. Keeping every application reachable throughout
meant designing the cutover itself: how the new environment goes live, and how all of it returns to
the previous revision the moment anything misbehaves. Deployment windows were at night, which made
coordination the harder half of the job: three people at DS360 on my side, six on the client's, run
jointly with their own project manager.

🎮 **Simulation Development** — extended an airport simulator used for air-traffic-control training
(Unity, 3D) with ground vehicle traffic driving across the airport model, giving instructors a new
class of events to train on.

🎨 **Frontend Development** — reworked the structure and code of an existing Vue.js website for a
consulting firm and adapted it to new requirements; deployed to Cloud Run through automated CI/CD
from GitHub.

`Python` `Flask` `LightGBM` `scikit-learn` `pandas` `PostgreSQL` `PostGIS` `BigQuery` `Docker` `Cloud Run` `Cloud Build` `Cloud Composer` `Vue.js` `Unity` `CI/CD`

<hr/>

### 🎓 Education

- **MSc Eng. (mgr inż.)** — Computer Science (spec. Intelligent Internet Technologies), Bialystok University of Technology · 2026
- **BEng (inż.)** — Computer Science, Bialystok University of Technology · 2024
- **IT Technician (technik informatyk)** — technical secondary school · 2020

<hr/>

### 🛠️ Languages | Technologies

- HTML, CSS, Bootstrap, SCSS/SASS, Tailwind
- JavaScript, jQuery, Axios, TypeScript, Angular, Vue, React
- C# (.NET) — LINQ, EF Core, WPF, ASP.NET Core (Web API, MVC, Razor Pages)
- Python — Django, Flask, SQLAlchemy, psycopg
  - **Data Science & Machine Learning**: Scikit-Learn, LightGBM, TensorFlow, Pandas, Jupyter Notebook
- C/C++
- Rust
- PHP
- SQL
- Regex

### 🎓 Fundamentals & Practices

- Design Patterns, Clean Code
- RESTful APIs (incl. HATEOAS)
- Geospatial Data Processing (Python, PostGIS, BigQuery, OSM)

<hr/>

### 💾 Databases

- PostgreSQL (incl. PostGIS)
- Microsoft SQL Server
- Oracle SQL
- MySQL | MariaDB
- SQLite
- MongoDB

### ☁️ Cloud & Infrastructure

- Google Cloud Platform — Cloud Run, Cloud SQL, Cloud Build, Artifact Registry, GCS, BigQuery, Cloud Composer
- Docker, Virtual Machines (VM)
- CI/CD

### 🎮 Engines

- Unity 2D/3D
- Godot
- Unreal Engine 5

<hr/>

### 🖥️ Environment

- 🪟 Windows, 🐧 Linux, 🍎 macOS
- Visual Studio, VS Code

### ⚙️ Tools & Others

- Webpack, Vite
- Swagger, Postman
- SSMS, Oracle SQL Developer, DBeaver
- GitHub Desktop, Pages, Codespaces, Actions, Copilot
- Azure DevOps (TFS)

<hr/>

<a href="https://github.com/UltiPro/Certifications"><img src="https://github-readme-stats-n50491bd0-ulti-9504.vercel.app/api/pin/?username=ultipro&repo=certifications&theme=dark&text_color=ffffff&border_radius=0" alt="Patryk 'UltiPro' Wójtowicz Certifications" align="right" width="350" /></a>

### 🌐 Hosted Projects & Certifications

<a href="https://ultipro.github.io/TicTacToe/"><img src="./icons/projects/tictactoe.svg" width="60"/></a>
<a href="https://ultipro.github.io/GitHub-Users/"><img src="./icons/projects/github-users.svg" width="60"/></a>
<a href="https://ultipro.github.io/Memory-Color-Master/"><img src="./icons/projects/memory-color-master.svg" width="60"/></a>
<a href="https://ultipro.github.io/JustDoIt/"><img src="./icons/projects/justdoit.svg" width="60"/></a>

<hr/>

<h3 align="center">👋 <i>See You Later, Alligator!</i> 🐊</h3>
