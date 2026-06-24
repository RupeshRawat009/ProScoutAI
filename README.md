# Pro Scout AI: Elite Analytics Agent

Pro Scout AI is an intelligent, multi-agent system built to revolutionize football player recruitment. By integrating real-time data APIs with autonomous analytical logic, the system helps scouts identify high-value targets by shifting from manual, subjective assessment to data-driven performance analysis.

## 🧠 The Agentic Architecture
- **Analyst Agent:** Interfaces with live football data via MCP-compliant API patterns to ingest, clean, and calculate player performance metrics.
- **Strategist Agent:** Executes a decision-making heuristic to provide binary (BUY/MONITOR) recruitment recommendations based on league-wide efficiency benchmarks.

## 🚀 Key Features
- **Intelligent Scouting:** Automatic calculation of `EfficiencyScore` using Goals, Assists, and Minutes.
- **Tactical Radar:** Visual representation of player profiles using radar analysis.
- **Secure Integration:** API security handled via environment-based secret management.
- **Antigravity Framework:** Implements non-standard library integration for auxiliary system functionality.

## 🛠 Tech Stack
- **Framework:** Streamlit
- **Analytics:** Pandas, PyODBC (SQL Server integration)
- **Visualization:** Apache ECharts
- **Agent Framework:** Custom Agentic Logic

## 📋 Quick Start
1. Clone the repo: `git clone https://github.com/RupeshRawat009/ProScoutAI.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Configure your API key in `.streamlit/secrets.toml`.
4. Run the agent: `python -m streamlit run scout_agent.py`
