# Hi, I'm John Mba 👋 

### 🚀 Software Engineer & AI Integrator | Web Development • Cloud Architecture • Distributed Systems

I specialize in building intelligent, highly available web applications, geolocation microservices, and robust cloud infrastructure. I blend backend optimization with advanced data pipelines, designing scalable architectures that power enterprise communication APIs, business management platforms, and real-time connectivity systems.

---

### 🛠️ Tech Stack & Skills


| Category | Technologies |
| :--- | :--- |
| **Backend & APIs** | Python, Django, FastAPI, Flask, GraphQL, REST APIs, SMTP/SMS Gateways |
| **Frontend** | JavaScript, HTML5, CSS3 |
| **Cloud, DevOps & Caching** | Kubernetes, Google Kubernetes Engine (GKE), Google Cloud Platform (GCP), Docker, Redis |
| **Databases & Analytics** | Advanced SQL, PostgreSQL (Window Functions, CTEs, Index Optimization, GIS/Spatial Extensions) |
| **Data Structures & Algorithms** | Graphs *(Routing & Networks)*, Binary Trees, Dynamic Programming, Linked Lists *(Python)* |
| **Familiar / Exploring** | Cassandra, MongoDB |

---

### 🏗️ System Architecture Paradigms

I design software systems with a heavy emphasis on reliability, low latency, and horizontally scalable cloud infrastructure. My structural approach focuses on:

```text
       [ Public API Traffic / Client Requests ]
                         │
                         ▼
             [ Cloudflare / Load Balancer ]
                         │
                         ▼
         [ Google Kubernetes Engine (GKE) ]
  ┌──────────────────────┼──────────────────────┐
  ▼                      ▼                      ▼
[Geofencing Engine]   [Auth Service]     [SaaS Core Engines]
  │                      │                      │
  └──────────┬───────────┴───────────┬──────────┘
             ▼                       ▼
      [ Redis Cache ]       [ PostgreSQL (GIS) ]
                             │
                             ▼
                    [ FastAPI Workers ] ──► [ Async SMTP & SMS APIs ]
```

- **Microservices Isolation:** Decentralized services packed into Docker containers, orchestrated via GKE to eliminate single points of failure.
- **Non-Blocking Task Processing:** Offloading computational logic like spatial metrics, transactional business emails, and programmatic SMS dispatches to native **FastAPI BackgroundTasks** to keep the core API client-loop fast and responsive.
- **Spatial Data Management:** Leveraging PostgreSQL along with complex SQL optimizations to calculate accurate proximity boundaries and location metrics instantly.

---

### 📂 Repository Directory & Case Studies

#### 🌐 [DotSpot Tech Services](./CASE_STUDY_DOTSPOT.md)
*An enterprise-grade organization ecosystem built on a modern microservices architecture.*
- **Core Modules:** Geofencing location services, centralized Auth provider, core SaaS engines, and public-facing APIs.
- **Tech Stack:** Python, PostgreSQL, Redis, GraphQL, Docker, Google Kubernetes Engine (GKE).
- **📖 Read the Blueprint:** [Detailed Case Study on Scaling Microservices with GKE & GIS Spatial Indexing](./CASE_STUDY_DOTSPOT.md).

#### 🧹 [TheKleenerApp](./CASE_STUDY_THEKLEENERAPP.md)
*A collaborative partnership project focused on scalable service delivery.*
- **Role:** Joint Core Developer / Infrastructure Engineer.
- **📖 Read the Blueprint:** [Detailed Case Study on Optimizing Service Delivery Communications via Asynchronous Coroutines](./CASE_STUDY_THEKLEENERAPP.md).

#### 🧬 [Python DSA Training Hub](https://github.com/johnmba/dsa)
*A dedicated training playground tracking computational logic, runtime speed, and memory optimization.*
- **Concepts Practiced:** Graphs (Routing Networks), Binary Trees, Dynamic Programming (Optimization Problems), and Linked Lists.
- **Implementation Strategy:** Every challenge includes a brute-force approach, a highly optimized Python revision, and full Time/Space complexity documentation.

---

### 📫 Let's Connect!

- **Email:** [johnmba.se@dotspot.tech](mailto:johnmba.se@dotspot.tech)
- **GitHub:** [@johnmba](https://github.com)
