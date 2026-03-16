<div align="center"><img src="images/dashboard_psgacademie.png" style="width:80%;"></div>

<div align="center">

# Portfolio-Project
</div>

## Summary
This portfolio project showcases my skills and achievements in software development through various projects completed during my training. It highlights my technical expertise, organizational abilities, and capacity to successfully carry out IT projects.

## 📚 Table of Contents

Stage 1
- [Team Formation and roles definition](#team-Formation-and-roles-definition)
- [Brainstorming and idea evaluation](#brainstorming-and-idea-evaluation)
- [Decision and Refinement](#decision-and-refinement)

Stage 2
- [High-Level Project Plan](#high-level-project-plan)

Stage 3
- [User Stories and Mockups](#user-stories-and-mockups)
- [System Architecture](#system-architecture)
- [Components, Classes, and Database Design](#components-classes-and-database-design)
- [High-Level Sequence Diagrams](#high-level-sequence-diagrams)
- [External and Internal APIs](#external-and-internal-apis)
- [SCM and QA Strategies](#scm-and-qa-strategies)
- [Technical Justifications](#technical-justifications)

Stage 4
- [Plan and Define Sprints](#plan-and-define-sprints)
- [Execute Development Tasks](#execute-development-tasks)
- [Monitor Progress and Adjust](#monitor-progress-and-adjust)
- [Conduct Sprint Reviews and Retrospectives](#conduct-sprint-reviews-and-retrospectives)
- [Final Integration and QA Testing](#final-integration-and-qa-testing)
- [Deliverables](#deliverables)
- [Technical Manual Review](#technical-manual-review)
- [PSG-Academy link](#psg-academy-link)

Stage 5
- [Document Results and Lessons Learned](#document-results-and-lessons-learned)
- [Presentation Slide Deck](#presentation-slide-deck)


About
- [Author](#author)

---

# Stage 1/ Team Formation, Brainstorming and MVP.

## [Team Formation and roles definition](#-table-of-contents)
Our team began by getting to know each member’s background, strengths, and interests. We assigned initial responsibilities, including a temporary Project Manager to guide the early stages. Communication and collaboration guidelines were set up using tools like Slack or Discord. Each member took on a technical role—such as UI designer, backend developer, or frontend developer—based on their skills and preferences, ensuring balanced coverage of project needs. Stakeholders were identified and their influence on the project clarified where relevant.

The team is made up of three members:
- Pierre-Yves, who is specializing in cybersecurity.
- Jules, who is also specializing in cybersecurity.
- Loïc, who is in the third quarter of the fundamentals track.

At the start, we held a meeting to introduce ourselves, discuss our skills, and set expectations. We agreed to work as co-developers, without assigning a permanent Project Manager, but one member coordinates meetings and deadlines when needed.

We established communication norms: regular in-person meetings at school, a Discord group for technical discussions, and WhatsApp for client communication. Decisions are made collectively, with everyone’s input considered.

Technical roles were distributed based on project needs and individual strengths. The project is divided into three main parts, each managed by Pierre-Yves, Jules, or Loïc, who handle both front-end and back-end tasks. 

The direct stakeholders are obviously the co-developers, therefore Pierre-Yves, Jules, Valentin, and myself.
The indirect stakeholders are the clients :
- Pierre, who is the financial director.
- Florian, who is a goalkeepers’ coach.
- Sebastien, who is an assistant coach.
- Lucas, who is a fitness coach.

## [Brainstorming and idea evaluation](#-table-of-contents)
You need to research project ideas, organize a brainstorming session using techniques such as mind mapping, SCAMPER, and “How Might We” questions. Then you must define criteria to evaluate the ideas, write a list of ideas with a short description for each one, and finally rank these ideas based on their feasibility, risks, and impact.


To identify our project direction, we first researched current industry trends and real-world challenges in sports analytics and team management. Each team member contributed ideas inspired by personal interests and client needs.

We organized a brainstorming session using mind mapping and “How Might We” questions to generate and connect ideas. We also applied the SCAMPER framework to explore how existing solutions could be improved or adapted.

**Evaluation Criteria:**
- Feasibility (can we build it with our skills and resources?)
- Potential impact (usefulness for users and stakeholders)
- Technical alignment (matches our expertise)
- Scalability (can the solution grow or be adapted?)

**Project Ideas:**
1. **Player Performance Dashboard**  
   A web app to track and visualize player statistics, training progress, and match performance.
2. **Team Communication Platform**  
   A tool for coaches and players to share updates, schedules, and feedback.
3. **Fitness & Injury Tracker**  
   An application to monitor player fitness levels and injury recovery, with alerts for coaches.

**Ranking:**
1. **Player Performance Dashboard**  
   - Feasibility: High  
   - Impact: High  
   - Risks: Manageable  
   - Chosen for its direct relevance to client needs and our technical strengths.
2. **Fitness & Injury Tracker**  
   - Feasibility: Medium  
   - Impact: Medium  
   - Risks: Data privacy, medical accuracy
3. **Team Communication Platform**  
   - Feasibility: High  
   - Impact: Medium  
   - Risks: Competes with existing solutions

After discussion, we selected the Player Performance Dashboard as our MVP due to its strong alignment with stakeholder needs and our team's expertise.

## [Decision and Refinement](#-table-of-contents)
You need to choose the final MVP idea, clearly explain the problem it solves, the solution it provides, the target users, and the type of application. You must also justify why you chose this idea, define 2 to 3 key features, specify what will be included or not included in the project, and identify the main risks along with how you will manage them.


### Selected MVP: Player Performance Dashboard

**Problem to solve:**  
Coaches and staff lack a centralized tool to track player progress, statistics, and fitness, making decision-making and training optimization more difficult.

**Solution provided:**  
A web application that visualizes and analyzes performance, training, and match data for each player, making it easier to monitor and improve both individual and team results.

**Target users:**  
Coaches, technical staff, players, and sports analysts.

**Type of application:**  
Web application accessible on computers and tablets.

**Why this idea?**  
This project directly addresses the needs expressed by our clients and leverages our team’s technical skills. It offers immediate value and impact, while other ideas were either too complex for the available timeframe or already covered by existing solutions.

**Key features and objectives:**
1. Visualization of individual and team statistics (SMART goal: allow coaches to access clear, personalized reports for each player).
2. Tracking training progress (SMART goal: generate progress charts for each player over a given period).
3. Alerts and notifications for outstanding performances or drops in form (SMART goal: automate alerts when key indicators change significantly).

**In-scope deliverables:**
- Interactive dashboard with data visualization.
- Import/export system for statistics.
- Alerts and notification module.

**Out-of-scope:**
- Advanced medical analysis or injury tracking.
- Internal messaging platform.
- Native mobile application.

**Risks and mitigation:**
- **Risk:** Lack of experience with some data visualization technologies.  
  **Mitigation:** Plan training sessions and use proven libraries.
- **Risk:** Difficulty collecting reliable data.  
  **Mitigation:** Work closely with clients to define clear data formats and sources.
- **Risk:** High workload for the team.  
  **Mitigation:** Prioritize essential features and schedule regular progress reviews.

---

# Stage 2/ Project Planning.

## [High-Level Project Plan](#-table-of-contents)

### Timeline and Phases

| Stage / Milestone                  | Target Date      | Key Deliverables / Description                          |
|------------------------------------|:----------------:|---------------------------------------------------------|
| 1. Idea Development                | December 14      | Team formation, brainstorming, MVP selection            |
| 2. Project Planning                | December 21      | High-level plan, timeline, roles and responsibilities   |
| 3. Technical Documentation         | January 04       | Complete technical documentation                        |
| 4. CSV Data Processing Complete    | January 10       | All raw data cleaned and ready for use                  |
| 5. Backend Implementation Complete | End of January   | Core backend features developed and tested              |
| 6. Frontend Implementation Complete| End of February  | User interface and dashboard ready                      |
| 7. MVP Ready                       | March 10         | Fully functional MVP for demo and client review         |
| 8. Project Closure                 | mid-March        | Final presentation, documentation, handover             |

This integrated timeline provides a clear overview of all major phases and milestones, helping the team track progress and meet key deadlines throughout the project.

---

# Stage 3/ Technical Documentation.

## [User Stories and Mockups](#-table-of-contents)

**User Stories (MoSCoW Prioritization):**

**Must Have:**
1. As a coach, I want to view individual player statistics on a dashboard, so that I can quickly assess their performance.
2. As a coach, I want to import CSV data files containing player statistics, so that I can update the dashboard with the latest information.
3. As a coach, I want to visualize player progress over time through charts and graphs, so that I can identify trends and areas for improvement.
4. As a data analyst, I want to filter and sort player data by various criteria (position, date, performance metrics), so that I can perform detailed analysis.

**Should Have:**

5. As a coach, I want to receive alerts when a player's performance drops significantly, so that I can take corrective action quickly.
6. As a player, I want to view my own performance statistics, so that I can track my progress and set personal goals.
7. As a coach, I want to compare multiple players side-by-side, so that I can make informed decisions about team composition.

**Could Have:**

8. As a coach, I want to export customized reports in PDF format, so that I can share insights with management.
9. As a coach, I want to add notes and comments on individual player profiles, so that I can document observations and recommendations.

**Won't Have (for MVP):**

10. Advanced predictive analytics for future performance forecasting.
11. Mobile application version.
12. Integration with wearable fitness trackers.

**Mockups:**

[Here](images/mockups) is the link to the mockups.

## [System Architecture](#-table-of-contents)

### High-Level Architecture Diagram

```mermaid
graph TB
    subgraph "Client Layer"
        Browser["Web Browser<br/>(Coach Dashboard)"]
    end
    
    subgraph "Presentation Layer"
        Nginx["Nginx<br/>(Reverse Proxy / HTTPS)"]
    end
    
    subgraph "Frontend Layer"
        React["React + TypeScript<br/>Material UI / Chakra<br/>Recharts / Chart.js"]
    end
    
    subgraph "Backend Layer"
        FastAPI["Python FastAPI<br/>JWT OAuth2<br/>Business Logic"]
    end
    
    subgraph "Data Layer"
        PostgreSQL["PostgreSQL<br/>SQLAlchemy/SQLModel<br/>(Players, Matches, Stats)"]
        Redis["Redis<br/>(Cache - Optional)"]
    end
    
    subgraph "Services"
        CSV["CSV/Excel Import<br/>pandas + openpyxl"]
        PDF["PDF Export<br/>wkhtmltopdf/WeasyPrint"]
    end
    
    Browser -->|HTTPS| Nginx
    Nginx -->|Route| React
    React -->|REST API| FastAPI
    FastAPI -->|Query| PostgreSQL
    FastAPI -->|Cache| Redis
    FastAPI -->|Process| CSV
    FastAPI -->|Generate| PDF
    
    style Browser fill:#e1f5ff
    style React fill:#61dafb
    style FastAPI fill:#009688
    style PostgreSQL fill:#336791
    style Redis fill:#dc382d
```

### Deployment Architecture (Docker Compose)

```mermaid
graph TB
    subgraph Docker["Docker Compose Environment"]
        subgraph Frontend["Frontend Container"]
            ReactApp["React App<br/>TypeScript<br/>Port 3000"]
        end
        
        subgraph Backend["Backend Container"]
            FastAPIApp["FastAPI<br/>Python<br/>Port 8000"]
        end
        
        subgraph Database["Database Container"]
            PostgreSQLDB["PostgreSQL<br/>Port 5432"]
        end
        
        subgraph Cache["Cache Container"]
            RedisCache["Redis<br/>Port 6379"]
        end
        
        subgraph WebServer["Web Server Container"]
            NginxServer["Nginx<br/>Port 80/443"]
        end
    end
    
    subgraph CICD["CI/CD Pipeline"]
        GitHub["GitHub Repository"]
        Actions["GitHub Actions<br/>(Automated Testing & Deployment)"]
    end
    
    NginxServer -->|Proxy| ReactApp
    NginxServer -->|Proxy API| FastAPIApp
    FastAPIApp -->|Connect| PostgreSQLDB
    FastAPIApp -->|Connect| RedisCache
    
    GitHub -->|Trigger| Actions
    Actions -->|Deploy| Docker
    
    style ReactApp fill:#61dafb
    style FastAPIApp fill:#009688
    style PostgreSQLDB fill:#336791
    style RedisCache fill:#dc382d
    style NginxServer fill:#269539
    style GitHub fill:#e1f5ff
    style Actions fill:#2088ff
```

### Components Description

**Front-end:**
- **Technology:** React + TypeScript
- **UI Library:** Material UI / Chakra UI / Mantine
- **Charts:** Recharts / Chart.js
- **Responsibilities:** Coach dashboard interface, data visualization, CSV file upload, player statistics display
- **Key Features:** Interactive charts, filtering, player comparison, responsive design

**Back-end:**
- **Technology:** Python + FastAPI
- **ORM:** SQLAlchemy / SQLModel
- **Authentication:** JWT (OAuth2 Password Flow)
- **Responsibilities:** REST API endpoints, business logic, authentication, data processing
- **Key Features:** 
  - CRUD operations for players, matches, and sessions
  - CSV/Excel import with pandas + openpyxl
  - User authentication and role management (coach, admin)
  - Performance alerts generation

**Database:**
- **Technology:** PostgreSQL
- **ORM:** SQLAlchemy / SQLModel
- **Responsibilities:** Store player data, match statistics, training sessions, user accounts
- **Structure:** Relational tables for players, matches, sessions, coaches, statistics

**Cache Layer (Optional for Performance):**
- **Technology:** Redis
- **Responsibilities:** Cache frequently accessed data to improve performance
- **Usage:** Store recent player statistics, dashboard data

**Import/Export:**
- **CSV/Excel Import:** pandas + openpyxl / csv module
- **PDF Export:** HTML + CSS + wkhtmltopdf / WeasyPrint for generating player reports and schedules

**Web Server:**
- **Technology:** Nginx
- **Responsibilities:** Reverse proxy, HTTPS, static file serving, load balancing
- **Features:** SSL/TLS termination, request routing, security

**Development & Deployment:**
- **Containerization:** Docker + Docker Compose
- **Version Control:** GitHub
- **CI/CD:** GitHub Actions for automated testing and deployment
- **Environment Consistency:** All team members work in identical Docker environments

**Future Enhancement:**
- **Mobile App:** React PWA (Progressive Web App) for players to view their own statistics

### Data Flow

1. **Coach uploads CSV file** → React frontend sends file to FastAPI backend
2. **Backend processes CSV** → pandas parses and validates data → stores in PostgreSQL via SQLAlchemy
3. **Coach requests dashboard** → React app calls FastAPI endpoints with JWT token
4. **Backend authenticates request** → Validates JWT → queries PostgreSQL (or Redis cache)
5. **Frontend renders charts** → Recharts/Chart.js displays player statistics
6. **Coach exports PDF report** → Backend generates PDF with wkhtmltopdf/WeasyPrint
7. **Performance alert** → Backend detects drop in statistics → triggers notification

### Architecture Justification

| Component | Technology | Justification |
|-----------|-----------|---------------|
| Backend API | Python + FastAPI | Versatile language, ideal for data manipulation; FastAPI is modern, fast, and simple to structure |
| Database | PostgreSQL | Reliable, performant, well-suited for relationships between players, matches, sessions |
| ORM | SQLAlchemy/SQLModel | Simplifies SQL queries, keeps code readable and maintainable |
| Frontend | React + TypeScript | Fluid, modern, reactive interface; TypeScript makes code safer and easier to maintain in teams |
| UI Components | Material UI/Chakra/Mantine | Ready-to-use components (tables, buttons, forms) to save development time |
| Charts | Recharts/Chart.js | Simple tools for displaying performance graphs and player statistics |
| Data Import | pandas + openpyxl | Easy import and transformation of stats files from external systems |
| Authentication | JWT (OAuth2) | Modern standard for securing connections and managing users (coach, admin, etc.) |
| PDF Export | wkhtmltopdf/WeasyPrint | Generates clean PDFs (reports, schedules) from application pages |
| Deployment | Docker Compose | Ensures all team members work in the same environment |
| Web Server | Nginx | Fast and secure production serving (HTTPS, redirects, etc.) |
| CI/CD | GitHub Actions | Facilitates collaborative work, backups, and automated deployments |
| Cache | Redis (optional) | Speeds up application by temporarily storing frequently requested data |
| Mobile (future) | React PWA | Reuses the same React codebase to create a simple mobile version for players |

## [Components, Classes, and Database Design](#-table-of-contents)

### Database Schema (PostgreSQL)
```mermaid
erDiagram
    COUNTRY ||--o{ COUNTRY_ACADEMY : "contains"
    COUNTRY_ACADEMY ||--o{ ACADEMY_TEAM : "contains"
    ACADEMY_TEAM ||--o{ TEAM_HUB : "contains"
    TEAM_HUB ||--o{ USER : "has"
    TEAM_HUB ||--o{ PLAYER_CARD : "manages"
    TEAM_HUB ||--o{ COLLECTIVE_SQUAD_STATS : "calculates"
    TEAM_HUB ||--o{ TRAINING_CALENDAR : "plans"
    TEAM_HUB ||--o{ DATA_IMPORT : "receives"
    
    PLAYER_CARD ||--|| PLAYER_PROFILE : "has"
    PLAYER_CARD ||--|| PLAYER_POSITION : "has"
    PLAYER_CARD ||--o{ MATCH_STATISTIC : "records"
    PLAYER_CARD ||--o{ PHYSICAL_STATISTIC : "measures"
    PLAYER_CARD ||--o{ ALERT : "generates"
    
    USER ||--o{ ALERT : "receives"
    USER ||--o{ DATA_IMPORT : "performs"
    USER ||--o{ DATA_EXPORT : "generates"
    
    COUNTRY {
        int id PK
        string name
        string iso_code
        datetime created_at
        datetime updated_at
    }
    
    COUNTRY_ACADEMY {
        int id PK
        string name
        string city
        int country_id FK
        datetime created_at
        datetime updated_at
    }
    
    ACADEMY_TEAM {
        int id PK
        string name
        string category
        int academy_id FK
        datetime created_at
        datetime updated_at
    }
    
    TEAM_HUB {
        int id PK
        string name
        string description
        int team_id FK
        datetime created_at
        datetime updated_at
    }
    
    USER {
        int id PK
        string last_name
        string first_name
        string email UK
        string password_hash
        string role
        int hub_id FK
        datetime created_at
        datetime updated_at
    }
    
    PLAYER_CARD {
        int id PK
        int hub_id FK
        int jersey_number
        string status
        datetime created_at
        datetime updated_at
    }
    
    PLAYER_PROFILE {
        int id PK
        int player_card_id FK
        string last_name
        string first_name
        date birth_date
        int age
        float height
        float weight
        string nationality
        string preferred_foot
        datetime created_at
        datetime updated_at
    }
    
    PLAYER_POSITION {
        int id PK
        int player_card_id FK
        string main_position
        string secondary_positions
        datetime created_at
        datetime updated_at
    }
    
    MATCH_STATISTIC {
        int id PK
        int player_card_id FK
        date match_date
        string opponent
        int minutes_played
        int goals
        int assists
        int shots_on_target
        int successful_passes
        int duels_won
        float match_rating
        string veo_url
        string activity_zones
        datetime created_at
        datetime updated_at
    }
    
    PHYSICAL_STATISTIC {
        int id PK
        int player_card_id FK
        date test_date
        string test_type
        float vma
        float max_speed
        float total_distance
        int sprints
        float endurance
        float strength
        float flexibility
        datetime created_at
        datetime updated_at
    }
    
    ALERT {
        int id PK
        int player_card_id FK
        int user_id FK
        string type
        string priority
        string message
        datetime creation_date
        boolean read
        datetime read_date
    }
    
    COLLECTIVE_SQUAD_STATS {
        int id PK
        int hub_id FK
        int total_squad
        float average_age
        float average_height
        date calculation_date
        datetime created_at
    }
    
    TRAINING_CALENDAR {
        int id PK
        int hub_id FK
        string title
        datetime session_date
        int duration
        string session_type
        string location
        datetime created_at
        datetime updated_at
    }
    
    DATA_IMPORT {
        int id PK
        int user_id FK
        int hub_id FK
        string file_name
        string file_type
        string status
        int lines_processed
        datetime import_date
    }
    
    DATA_EXPORT {
        int id PK
        int user_id FK
        string export_type
        string format
        datetime export_date
        string file_path
    }
```

### Database Tables Description

**Main Tables:**

1. **COUNTRY**: Stores countries where academies are located
2. **COUNTRY_ACADEMY**: Football academies by country
3. **ACADEMY_TEAM**: Teams within an academy
4. **TEAM_HUB**: Management hub for each team
5. **USER**: System users (coaches, admins, analysts)
6. **PLAYER_CARD**: Central card grouping all player information
7. **PLAYER_PROFILE**: Player's personal information
8. **PLAYER_POSITION**: Player's positions on the field
9. **MATCH_STATISTIC**: Detailed stats per match
10. **PHYSICAL_STATISTIC**: Physical tests and athletic metrics
11. **ALERT**: Performance alerts for coaches
12. **COLLECTIVE_SQUAD_STATS**: Collective team statistics
13. **TRAINING_CALENDAR**: Training schedule
14. **DATA_IMPORT**: Data import history
15. **DATA_EXPORT**: Export history (PDF, CSV)

**Constraints and Indexes:**
- Primary Keys (PK) on all id columns
- Foreign Keys (FK) to maintain referential integrity
- Unique Key (UK) on user.email
- Indexes on frequently searched columns (match_date, test_date, player_card_id)
- Cascade delete on certain relationships (e.g., deleting a player_card deletes their stats)

### Frontend Components Architecture

**Main Pages:**
1. **HomePage** (1Home.png) - Dashboard overview with key statistics
2. **AcademiesPage** (2Academies.png) - List of academies
3. **TeamsPage** (3Teams.png) - List of teams
4. **PlayersPage** (4Players.png) - List of all players
5. **PlayerDetailPage** (5Player.png) - Individual player details
6. **ProfilePage** (6Profil.png) - Player profile information
7. **VEOPage** (7VEO.png) - VEO performance analysis
8. **CatapultPage** (8Catapult.png) - Catapult physical data
9. **SessionReportPage** (9Rapport de séance.png) - Training session report
10. **WeeklyReportPage** (10Rapport Hebdomadaire.png) - Weekly team report
11. **IndividualWeeklyReportPage** (11Rapport semaine individuel.png) - Individual weekly report

```
src/
├── components/
│   ├── layout/
│   │   ├── Header.tsx              # Header with navigation
│   │   ├── Sidebar.tsx             # Side navigation menu
│   │   └── Layout.tsx              # Main wrapper component
│   │
│   ├── auth/
│   │   ├── LoginForm.tsx           # Login form
│   │   └── ProtectedRoute.tsx     # Authentication-protected route
│   │
│   ├── dashboard/
│   │   ├── DashboardOverview.tsx   # Home dashboard (1Home.png)
│   │   └── StatCard.tsx            # Individual statistic card
│   │
│   ├── academies/
│   │   ├── AcademyList.tsx         # List of academies (2Academies.png)
│   │   └── AcademyCard.tsx         # Academy card component
│   │
│   ├── teams/
│   │   ├── TeamList.tsx            # List of teams (3Teams.png)
│   │   └── TeamCard.tsx            # Team card component
│   │
│   ├── players/
│   │   ├── PlayerList.tsx          # List of players (4Players.png)
│   │   ├── PlayerCard.tsx          # Player card component
│   │   ├── PlayerDetail.tsx        # Player detail view (5Player.png)
│   │   ├── PlayerProfile.tsx       # Player profile (6Profil.png)
│   │   └── PlayerFilter.tsx        # Search and filter component
│   │
│   ├── performance/
│   │   ├── VEOStats.tsx            # VEO performance data (7VEO.png)
│   │   ├── CatapultStats.tsx       # Catapult physical data (8Catapult.png)
│   │   ├── PerformanceChart.tsx    # Charts for performance visualization
│   │   └── ActivityZoneMap.tsx     # Activity zones display
│   │
│   ├── reports/
│   │   ├── SessionReport.tsx       # Training session report (9Rapport de séance.png)
│   │   ├── WeeklyReport.tsx        # Weekly team report (10Rapport Hebdomadaire.png)
│   │   ├── IndividualWeeklyReport.tsx # Individual weekly report (11Rapport semaine individuel.png)
│   │   └── ExportButtons.tsx       # PDF export buttons
│   │
│   ├── import-export/
│   │   ├── CSVImport.tsx           # CSV file upload
│   │   └── FileUploader.tsx        # Generic upload component
│   │
│   └── common/
│       ├── Button.tsx              # Custom button
│       ├── Table.tsx               # Generic table
│       ├── Loading.tsx             # Loading indicator
│       └── ErrorMessage.tsx        # Error message
│
├── pages/
│   ├── HomePage.tsx                # Dashboard (1Home.png)
│   ├── AcademiesPage.tsx           # Academies list (2Academies.png)
│   ├── TeamsPage.tsx               # Teams list (3Teams.png)
│   ├── PlayersPage.tsx             # Players list (4Players.png)
│   ├── PlayerDetailPage.tsx        # Player detail (5Player.png)
│   ├── ProfilePage.tsx             # Player profile (6Profil.png)
│   ├── VEOPage.tsx                 # VEO analysis (7VEO.png)
│   ├── CatapultPage.tsx            # Catapult data (8Catapult.png)
│   ├── SessionReportPage.tsx       # Session report (9Rapport de séance.png)
│   ├── WeeklyReportPage.tsx        # Weekly report (10Rapport Hebdomadaire.png)
│   ├── IndividualWeeklyReportPage.tsx # Individual report (11Rapport semaine individuel.png)
│   └── LoginPage.tsx               # Login page
│
├── hooks/
│   ├── useAuth.ts                  # Authentication hook
│   ├── usePlayers.ts               # Player management hook
│   ├── useStats.ts                 # Statistics retrieval hook
│   └── useApi.ts                   # Generic API call hook
│
├── services/
│   ├── api.ts                      # API client
│   ├── authService.ts              # Authentication service
│   ├── playerService.ts            # Player service
│   ├── statsService.ts             # Statistics service
│   ├── importService.ts            # CSV import service
│   └── exportService.ts            # PDF export service
│
└── types/
    ├── player.ts                   # Player types
    ├── stats.ts                    # Statistics types
    └── user.ts                     # User types
```

### Main Component Interactions

**Navigation Flow:**
1. `HomePage` → Overview dashboard
2. `AcademiesPage` → Select academy → `TeamsPage`
3. `TeamsPage` → Select team → `PlayersPage`
4. `PlayersPage` → Select player → `PlayerDetailPage`

**Player Detail Flow:**
1. `PlayerDetailPage` → Main player info (5Player.png)
2. Tabs/Navigation to:
   - `ProfilePage` → Personal info (6Profil.png)
   - `VEOPage` → Match performance (7VEO.png)
   - `CatapultPage` → Physical data (8Catapult.png)

**Reporting Flow:**
1. `SessionReportPage` → Training session analysis (9Rapport de séance.png)
2. `WeeklyReportPage` → Team weekly summary (10Rapport Hebdomadaire.png)
3. `IndividualWeeklyReportPage` → Player weekly summary (11Rapport semaine individuel.png)
4. Export buttons → Generate PDF reports

**Data Import:**
1. CSV import component → Upload player statistics
2. Backend processes → Updates database
3. Frontend refreshes → Displays updated data

## [High-Level Sequence Diagrams](#-table-of-contents)

### Use Case 1: User Authentication

```mermaid
sequenceDiagram
    actor Coach
    participant Frontend as React Frontend
    participant Nginx
    participant Backend as FastAPI Backend
    participant DB as PostgreSQL
    
    Coach->>Frontend: Enter credentials (email, password)
    Frontend->>Frontend: Validate form inputs
    Frontend->>Nginx: POST /api/auth/login
    Nginx->>Backend: Forward request
    Backend->>DB: Query user by email
    DB-->>Backend: Return user data
    
    alt User found and password correct
        Backend->>Backend: Verify password hash
        Backend->>Backend: Generate JWT token
        Backend-->>Nginx: 200 OK + JWT + user info
        Nginx-->>Frontend: Return JWT token
        Frontend->>Frontend: Store JWT in localStorage
        Frontend->>Frontend: Redirect to Dashboard
        Frontend-->>Coach: Display Dashboard
    else User not found
        Backend-->>Nginx: 404 Not Found
        Nginx-->>Frontend: Error response
        Frontend-->>Coach: Show "User not found" error
    else Wrong password
        Backend-->>Nginx: 401 Unauthorized
        Nginx-->>Frontend: Error response
        Frontend-->>Coach: Show "Invalid credentials" error
    else Invalid input
        Backend-->>Nginx: 400 Bad Request
        Nginx-->>Frontend: Error response
        Frontend-->>Coach: Show validation errors
    end
    
    Note over Coach,DB: Subsequent requests include JWT in Authorization header
```

### Use Case 2: CSV Data Import

```mermaid
sequenceDiagram
    actor Coach
    participant Frontend as React Frontend
    participant Nginx
    participant Backend as FastAPI Backend
    participant Pandas as pandas Library
    participant DB as PostgreSQL
    
    Coach->>Frontend: Select CSV file
    Frontend->>Frontend: Validate file format
    
    alt Valid CSV file
        Frontend->>Nginx: POST /api/import/csv
        Nginx->>Backend: Forward file upload
        Backend->>Backend: Validate JWT token
        
        alt Valid JWT
            Backend->>Pandas: Parse CSV file
            Pandas-->>Backend: Return DataFrame
            Backend->>Backend: Validate data structure
            
            alt Valid data structure
                Backend->>Backend: Transform data
                
                loop For each player record
                    Backend->>DB: INSERT/UPDATE player stats
                    DB-->>Backend: Confirm transaction
                end
                
                Backend->>DB: Create import log entry
                DB-->>Backend: Confirm log saved
                Backend-->>Nginx: 200 OK + import summary
                Nginx-->>Frontend: Return result
                Frontend->>Frontend: Display success message
                Frontend-->>Coach: Show import summary
            else Invalid data structure
                Backend-->>Nginx: 400 Bad Request
                Nginx-->>Frontend: Validation errors
                Frontend-->>Coach: Show data errors
            end
        else Invalid/Expired JWT
            Backend-->>Nginx: 401 Unauthorized
            Nginx-->>Frontend: Auth error
            Frontend-->>Coach: Redirect to login
        end
    else Invalid file format
        Frontend-->>Coach: Show "Please select a CSV file" error
    end
```

### Use Case 3: View Player Performance Dashboard

```mermaid
sequenceDiagram
    actor Coach
    participant Frontend as React Frontend
    participant Nginx
    participant Backend as FastAPI Backend
    participant Redis as Redis Cache
    participant DB as PostgreSQL
    
    Coach->>Frontend: Click on player card
    Frontend->>Nginx: GET /api/players/{player_id}
    Nginx->>Backend: Forward request
    Backend->>Backend: Validate JWT token
    
    alt Valid JWT
        Backend->>Redis: Check cache for player data
        
        alt Cache hit
            Redis-->>Backend: Return cached data
            Backend-->>Nginx: 200 OK + player data
        else Cache miss
            Backend->>DB: Query player profile
            
            alt Player exists
                DB-->>Backend: Return profile data
                Backend->>DB: Query match statistics
                DB-->>Backend: Return match stats
                Backend->>DB: Query physical statistics
                DB-->>Backend: Return physical stats
                Backend->>Backend: Aggregate data
                Backend->>Redis: Store in cache (TTL: 5 min)
                Backend-->>Nginx: 200 OK + player data (JSON)
            else Player not found
                DB-->>Backend: No data
                Backend-->>Nginx: 404 Not Found
                Nginx-->>Frontend: Error response
                Frontend-->>Coach: Show "Player not found"
            end
        end
        
        Nginx-->>Frontend: Return player data
        Frontend->>Frontend: Render PlayerDetail component
        Frontend->>Frontend: Generate charts
        Frontend-->>Coach: Display player dashboard
    else Invalid/Expired JWT
        Backend-->>Nginx: 401 Unauthorized
        Nginx-->>Frontend: Auth error
        Frontend-->>Coach: Redirect to login
    end
```

### Sequence Diagrams Description

**1. User Authentication:**
- Coach enters credentials
- Frontend validates and sends to backend via Nginx
- Backend verifies credentials against database
- **Success case:** JWT token generated and returned to frontend, token stored for subsequent requests
- **Error cases:**
  - 404 Not Found: User doesn't exist
  - 401 Unauthorized: Wrong password
  - 400 Bad Request: Invalid input format

**2. CSV Data Import:**
- Coach uploads CSV file through frontend
- Frontend validates file format
- Backend receives and validates JWT token
- pandas library parses CSV data
- Data validated and transformed
- Each record inserted/updated in PostgreSQL
- Import log created for tracking
- **Success case:** Summary returned to coach with number of processed records
- **Error cases:**
  - 400 Bad Request: Invalid file format or data structure
  - 401 Unauthorized: Invalid or expired JWT token

**3. View Player Performance Dashboard:**
- Coach selects a player
- Backend validates JWT token
- Backend checks Redis cache first (performance optimization)
- If cache miss, queries PostgreSQL for all player data
- Data aggregated and cached for future requests
- Frontend receives data and renders dashboard with charts
- **Success case:** Coach views comprehensive player statistics
- **Error cases:**
  - 404 Not Found: Player doesn't exist
  - 401 Unauthorized: Invalid or expired JWT token

These sequence diagrams illustrate the main interactions between system components for critical MVP functionalities, including proper error handling and HTTP status codes.

## [External and Internal APIs](#-table-of-contents)

### External APIs

The project currently does not integrate external third-party APIs. All data processing is done internally using:

1. **pandas** - For CSV/Excel file parsing and data manipulation (internal library, not an external API)
2. **matplotlib/seaborn** - For data visualization and graph generation (internal library)

**Future Considerations:**
- **Email Service API** (e.g., SendGrid, Mailgun) - For sending performance alert notifications
- **Cloud Storage API** (e.g., AWS S3, Google Cloud Storage) - For storing uploaded files and generated reports
- **Authentication Provider** (e.g., Auth0, Firebase Auth) - For enhanced authentication management

### Internal API Endpoints

**Base URL:** `http://localhost:8000/api` (development) | `https://yourdomain.com/api` (production)

**Authentication:** JWT Bearer Token (for protected endpoints)

---

#### **Countries**

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/countries/` | Create a new country | Yes |
| GET | `/countries/` | Get all countries | Yes |
| PUT | `/countries/{country_id}` | Update a country | Yes |
| DELETE | `/countries/{country_id}` | Delete a country | Yes |


**Exemple : GET /countries/**
```json
// Response (200 OK)
[
  {
    "id": 1,
    "name": "France"
  },
  {
    "id": 2,
    "name": "Spain"
  }
]
```

---

#### **Academies**

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/academies/` | Create a new academy | Yes |
| GET | `/academies/` | Get all academies | Yes |
| GET | `/academies/country/{country_id}` | Get academies by country | Yes |
| PUT | `/academies/{academy_id}` | Update an academy | Yes |
| DELETE | `/academies/{academy_id}` | Delete an academy | Yes |


**Exemple : GET /academies/country/{country_id}**
```json
// Response (200 OK)
[
  {
    "id": 1,
    "name": "PSG Academy Paris",
    "country_id": 1
  },
  {
    "id": 2,
    "name": "PSG Academy Marseille",
    "country_id": 1
  }
]
```

---

#### **Teams**

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/teams/` | Create a new team | Yes |
| GET | `/teams/` | Get all teams | Yes |
| GET | `/teams/academy/{academy_id}` | Get teams by academy | Yes |
| PUT | `/teams/{team_id}` | Update a team | Yes |
| DELETE | `/teams/{team_id}` | Delete a team | Yes |


**Exemple : GET /teams/academy/{academy_id}**
```json
// Response (200 OK)
[
  {
    "id": 1,
    "name": "U17 Team",
    "academy_id": 1
  },
  {
    "id": 2,
    "name": "U19 Team",
    "academy_id": 1
  }
]
```

---

#### **Players**

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/players/` | Create a new player | Yes |
| GET | `/players/` | Get all players | Yes |
| GET | `/players/team/{team_id}` | Get players by team | Yes |
| PUT | `/players/{player_id}` | Update a player | Yes |
| DELETE | `/players/{player_id}` | Delete a player | Yes |


**Exemple : GET /players/team/{team_id}**
```json
// Response (200 OK)
[
  {
    "id": 1,
    "name": "Jean Dupont",
    "age": 17,
    "team_id": 1
  },
  {
    "id": 2,
    "name": "Pierre Martin",
    "age": 16,
    "team_id": 1
  }
]
```

---

#### **Catapult GPS Data**

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/catapult/upload` | Upload and process Catapult CSV file | Yes |
| GET | `/catapult/sessions` | Get all training sessions | Yes |
| GET | `/catapult/sessions/title/{session_title}` | Get sessions by title | Yes |
| GET | `/catapult/sessions/player/{player_name}` | Get sessions by player name | Yes |
| GET | `/catapult/sessions/{session_id}` | Get specific session by ID | Yes |
| POST | `/catapult/analyze/session/{session_title}` | Analyze session with split detection | Yes |

**POST /catapult/upload**
```json
// Request (multipart/form-data)
Content-Type: multipart/form-data
file: [CSV file]

// Response (200 OK)
{
  "filename": "training_session_2024.csv",
  "records_stored": 25,
  "players_count": 25,
  "session_title": "Training Session - 2024-01-04",
  "summary": {
    "total_distance_avg": 5420.5,
    "max_speed_avg": 28.3,
    "sprint_count_avg": 12
  }
}
```

**GET /catapult/sessions**
```json
// Response (200 OK)
[
  {
    "id": 1,
    "session_title": "Training Session - 2024-01-04",
    "player_name": "Jean Dupont",
    "total_distance": 5420.5,
    "max_speed": 28.3,
    "sprint_count": 12,
    "high_speed_running": 850.2
  }
]
```

---

### API Design Principles

**1. RESTful Design:**
- Resources are nouns (countries, academies, teams, players)
- HTTP methods match actions (GET=read, POST=create, PUT=update, DELETE=delete)
- Consistent URL structure

**2. Status Codes:**
- `200 OK` - Successful GET, PUT, DELETE
- `201 Created` - Successful POST
- `400 Bad Request` - Invalid input
- `401 Unauthorized` - Missing/invalid authentication
- `404 Not Found` - Resource doesn't exist
- `409 Conflict` - Duplicate resource (e.g., country name already exists)

**3. Response Format:**
- All responses are JSON
- Consistent error format:
```json
{
  "detail": "Error message description"
}
```

**4. Authentication:**
- Protected endpoints require JWT token in Authorization header:
```
Authorization: Bearer <token>
```

**5. Validation:**
- Input validation using Pydantic models
- Type checking enforced by FastAPI
- Automatic OpenAPI documentation at `/docs`

---

### Future API Endpoints (Planned)

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/login` | User authentication |
| POST | `/auth/logout` | User logout |
| GET | `/auth/me` | Get current user info |
| GET | `/players/{player_id}/stats/match` | Get player match statistics |
| GET | `/players/{player_id}/stats/physical` | Get player physical statistics |
| POST | `/players/{player_id}/stats/match` | Add match statistics |
| POST | `/players/{player_id}/stats/physical` | Add physical test results |
| GET | `/players/{player_id}/performance-trend` | Get performance trend over time |
| GET | `/alerts/` | Get all alerts |
| GET | `/alerts/unread` | Get unread alerts |
| PATCH | `/alerts/{alert_id}/read` | Mark alert as read |
| POST | `/reports/session` | Generate session report PDF |
| POST | `/reports/weekly` | Generate weekly report PDF |
| POST | `/reports/individual` | Generate individual player report PDF |
| GET | `/calendar/sessions` | Get training calendar |
| POST | `/calendar/sessions` | Create training session |
| PUT | `/calendar/sessions/{session_id}` | Update training session |
| GET | `/calendar/export/pdf` | Export calendar as PDF |
| GET | `/calendar/export/ics` | Export calendar as ICS |

## [SCM and QA Strategies](#-table-of-contents)

### Source Control Management (SCM)

**Version Control:** Git + GitHub

**Branching Strategy:**
- `main` - Production-ready code (protected)
- `develop` - Integration branch for development
- `Loïc` - Loïc's part
- `Pierre-Yves` - Pierre-Yves's part
- `Jules` - Jules's part

**Workflow:**
1. Create feature branch from `develop`
2. Develop and commit regularly with clear messages
3. Push and create Pull Request to `develop`
4. Code review by at least 1 team member
5. Merge after approval and passing tests

**Commit Convention:**
```
feat: add new feature
fix: bug correction
docs: documentation update
test: add or update tests
```

**Code Review Requirements:**
- Minimum 1 approval
- All tests must pass
- No merge conflicts
- Code follows style guidelines

---

### Quality Assurance (QA)

**Testing Strategy:**

**1. Unit Tests**
- **Backend:** `pytest` (coverage target: 80%)
  - Test individual functions, parsers, models
- **Frontend:** `Jest` + `React Testing Library` (coverage target: 70%)
  - Test components, hooks, utilities

**2. Integration Tests**
- **Backend:** `pytest` + `TestClient` for API endpoints
- **Frontend:** `Cypress` for user flows and navigation

**3. Manual Testing**
- CSV import with various file sizes
- PDF report generation
- Chart visualizations
- Cross-browser compatibility (Chrome, Firefox, Safari)

**Testing Tools:**
| Layer | Frontend | Backend |
|-------|----------|---------|
| Unit | Jest | pytest |
| Integration | Cypress | pytest + TestClient |
| Linting | ESLint | pylint / black |

**CI/CD Pipeline (GitHub Actions):**
```
Pull Request → Automated Tests → Code Review → Merge
     ↓
develop branch → Deploy to Staging → Manual QA
     ↓
main branch → Deploy to Production
```

**Quality Metrics:**
- Code coverage: ≥80% backend, ≥70% frontend
- API response time: <200ms average
- All tests pass before deployment

**Environments:**
- **Development:** Local Docker containers
- **Staging:** Cloud deployment for testing
- **Production:** Live environment

## [Technical Justifications](#-table-of-contents)

[Here](https://github.com/loicleguen/Portfolio-Project/blob/main/PSG-Academy-Technos.pdf) the link to document

---

# Stage 4/ MVP Development and Execution.

## [Plan and Define Sprints](#-table-of-contents)

To efficiently organize the development phase, we planned our first sprint by breaking down the work into clear tasks. Each task was prioritized using the MoSCoW method and assigned to team members based on their skills and involvement in the project.

| Task                                  | MoSCoW Priority | Assigned To      | Deadline      | Dependencies           |
|-------------------------------------- |:--------------: |:---------------: |:------------: |:----------------------:|
| Backend Catapult (API, DB, routes)    | Must Have       | Loïc             | 15/02/2026    | PostgreSQL setup       |
| Frontend Catapult (UI, dashboard)     | Must Have       | Loïc             | 30/02/2026    | Backend Catapult       |
| Backend Veo (API, DB, routes)         | Must Have       | Jules            | 15/02/2026    | PostgreSQL setup       |
| Frontend Veo (UI, dashboard)          | Must Have       | Jules            | 30/02/2026    | Backend Veo            |
| Nginx reverse proxy configuration     | Must Have       | Loïc             | 30/02/2026    | Backend, Frontend      |
| Backend Veo “Copier Intelligent”      | Should Have     | Pierre-Yves      | 30/02/2026    | Backend Veo            |
| Frontend “Copier Intelligent”         | Should Have     | Pierre-Yves      | 05/03/2026    | Backend Veo Copier     |
| Documentation (README, API docs)      | Should Have     | Loïc             | 10/03/2026    | All previous tasks     |

## [Execute Development Tasks](#-table-of-contents)

**Purpose:**  
Implement the sprint features and deliverables for the PSG Académie platform.

### Concrete process for PSG Académie

- Each collaborator works on their own dedicated Git branch (e.g., `loic`, `jules`, `pierre-yves`).
- Features are developed and tested on these personal branches.
- Once a feature is completed and validated, it is merged into the `develop` branch.
- API endpoints are tested using Swagger to ensure all routes (Catapult, Veo, etc.) function correctly.
- Frontend interfaces are checked in the browser to verify proper display and interactions.
- Bugs or improvements are reported and fixed before final validation.

**Concrete example:**  
For the creation of the Catapult API:
- Loïc develops the endpoints on his personal branch.
- Once finished and tested with Swagger, the feature is merged into the `develop` branch.
- Other team members can then integrate and test the feature on the common development branch.



## [Monitor Progress and Adjust](#-table-of-contents)

**Purpose:**  
Track team progress and ensure the project advances according to plan.

### Concrete practice for PSG Académie

- Progress meetings were held about once a week to review completed tasks, discuss any blockers, and plan the next steps.
- Task tracking and progress monitoring were done mainly verbally and through Git branches, without using a dedicated project management tool.
- Sprint goals and task assignments remained stable, with no major adjustments needed.

**Metrics tracked (informally):**
- Number of features completed versus those planned.
- Bug tracking and fixes handled as they arose during testing.

## [Conduct Sprint Reviews and Retrospectives](#-table-of-contents)

**Purpose:**  
To review progress, demo completed features, and reflect on process improvements.

### Concrete practice for PSG Académie

- At the end of each sprint (or major milestone), team members met to present and demo the completed features.
- A retrospective was held to discuss what went well, what challenges were encountered, and how to improve for the next sprint.
- Discussions focused on:
  - What worked well during the sprint.
  - The main challenges or blockers faced.
  - Ideas for improving organization or communication in the next sprint.

**Example questions for retrospectives:**
- What worked well during this sprint?
- What problems or obstacles did we face?
- What can we change to improve the next sprint?

## [Final Integration and QA Testing](#-table-of-contents)

**Purpose:**  
Ensure that all components work together smoothly and that the project meets quality standards.

### Concrete practice for PSG Académie

- Integration tests were performed to verify the end-to-end functionality of the MVP, making sure the front-end communicated correctly with the back-end APIs (Catapult and Veo).
- QA was carried out by following a final test plan, mainly through manual testing:
  - The team checked that all user flows worked as expected (e.g., data visualization, report generation).
  - API endpoints were tested using Swagger to ensure correct responses and proper error handling.
  - Database operations were verified to guarantee data integrity and correct behavior in different scenarios.
- Any critical bugs or performance issues identified at this stage were fixed before the final delivery.

**Example:**  
For the PSG Académie web app:
- The front-end was tested to ensure proper integration with both Catapult and Veo back-end APIs.
- Database actions (such as saving and retrieving player data) were checked for reliability and accuracy.

## [Deliverables](#-table-of-contents)

Below are the main deliverables for the PSG Académie project.

- **Sprint Reviews:**  
  No formal written notes; reviews were conducted verbally during team meetings.

- **Retrospectives:**  
  No written summaries; retrospectives were held verbally at the end of each sprint.

- **Sprint Planning:**  
  [Sprint Plan Table](#plan-and-define-sprints) (see above in this README)

- **Source Repository:**  
  [GitHub Repository](https://github.com/loicleguen/psg-academie/tree/develop) 

- **Bug Tracking:**  
  Managed informally via Git branches and team discussions (no dedicated tool used)

- **Testing Evidence and Results:**  
  - API endpoints tested with Swagger (see screenshots or documentation if available)
  - Manual test results discussed during team meetings

- **Production Environment:**  
  Deployed locally using Docker Compose (see project README for setup instructions)

## [Technical Manual Review](#-table-of-contents)

This step consists of passing a technical manual review (MR) scheduled by your SWE. The MR will evaluate:

- The completion of the project (a functional MVP with minor or no bugs)
- A demonstration of the MVP
- The quality of your code, commits, and documentation (README and code comments)
- Your ability to explain, with technical and logical reasoning, the technical decisions you made (database design, application architecture, technology choices, diagrams, etc.)
- Your ability to explain in detail the code and features of your portfolio
- How your application works (frontend, backend, database, etc.)
- How you tested your application (show/explain how tests were conducted and what was tested)
- How you collaborated with your team members (if group project)
- Git & GitHub best practices (branches, testing, etc.)
- Your ability to explain technical concepts applied in your application (e.g., DB relations, frontend design, authentication, hashing, security, RBAC, etc.)

**Preparation checklist:**
- A functional application ready for demonstration
- Application architecture diagram
- Database diagram
- A clean and professional README describing the project
- A complete and well-structured GitHub repository

---

## [PSG-Academy link](#-table-of-contents)

https://github.com/loicleguen/psg-academie/tree/loic

---

# Stage 5/ Project Closure.

## [Document Results and Lessons Learned](#-table-of-contents)

### Results Summary

- The MVP achieved 90% of the planned features.
- Main functionalities delivered:
  - Real-time player performance dashboard (Catapult & Veo integration)
  - Data visualization and report generation
  - “Smart copy” feature for tactical analysis
  - Personal information sheets for players
- The application was not tested directly by clients, but features were presented during a demonstration. Clients were generally satisfied, though they suggested some improvements.
- The project is not yet delivered, as it is still in progress.

### Lessons Learned

- **What went well:**
  - Clear division of tasks by collaborator improved efficiency.
  - Weekly progress meetings helped maintain focus and resolve blockers quickly.
  - Using Swagger for API testing streamlined backend validation.
- **Challenges faced:**
  - Initial onboarding of team members took longer than expected.
  - Some features required more time due to technical complexity (e.g., “smart copy”).
  - I had to learn many new technologies during the project.
  - Manual QA (testing done by hand, without automation) required extra effort.
- **Improvements for future projects:**
  - Allocate more time for testing and bug fixing.
  - Consider introducing automated testing for APIs and frontend.
  - Use a project management tool for better task tracking and visibility.

## [Presentation Slide Deck](#-table-of-contents)

- Includes all major stages of the project
- MVP demonstration
- [Link to the PowerPoint](https://1drv.ms/p/c/8e156011ed185c1c/IQBL8BLc7pcASobgrNHxXFiIARNVIuOaejQt6pJM4LQa4vI?e=E7wolt)
- [Link to the demo video](https://youtu.be/H8QW1jbAXNE)

---

## [Author](#-table-of-contents)

| Author           | Role      | GitHub                                   | Email                        |
|------------------|-----------|------------------------------------------|------------------------------|
| **Loïc Le Guen** | Co-developer | [@loicleguen](https://github.com/loicleguen) | 11510@holbertonstudents.com  |