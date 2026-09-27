# Algorithmic-Online-Code-Judge-Contest-Arena

A high-performance, full-stack competitive programming platform engineered to securely compile, execute, and evaluate multi-language code submissions in real-time. 

Built with **FastAPI** and **SQLAlchemy**, this system features a dynamic Monaco Code Editor, live WebSocket streaming for execution verdicts, and a fully functional contest ecosystem with penalty-adjusted leaderboards.

##  Features

* **Multi-Language Execution Engine:** Supports Python 3, C++, and Java code execution using native system processes.
* **Real-Time WebSocket Streaming:** Delivers millisecond-level, case-by-case execution verdicts (e.g., *Compiling...*, *Running Case 1/2...*, *Accepted*) directly to the UI with a robust fallback polling mechanism.
* **Resource Monitoring:** Enforces strict wall-time limits (Time Limit Exceeded) and tracks peak memory usage (Memory Limit Exceeded) using `psutil`.
* **Contest Ecosystem:** Includes JWT-based user authentication, time-frozen live standings, and penalty-calculated leaderboards.
* **Advanced Evaluation:** Supports hidden test cases, partial scoring (points-based), and configurable checker types (exact string matching vs. floating-point tolerance).
* **Integrated IDE:** Features a fully customized Monaco Editor (the engine behind VS Code) with syntax highlighting and theme toggling.

##  Tech Stack

* **Backend:** Python 3, FastAPI, Uvicorn
* **Database:** SQLite, SQLAlchemy (ORM)
* **Real-Time:** WebSockets, `asyncio` background tasks
* **Security & Auth:** JSON Web Tokens (JWT), Passlib, Bcrypt
* **Process Management:** `subprocess`, `psutil`
* **Frontend:** Vanilla HTML5, CSS Grid, JavaScript (Fetch API), Monaco Editor CDN


## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
   cd your-repo-name
