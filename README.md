# Radu Cristian Cucu

Second-year BSc Civil Engineering student at Politecnico di Milano, from Cluj-Napoca, Romania.
I came into engineering from a maths and computer science high school, so most of what I keep
here sits where structural design meets code. I work in Revit, pyRevit, AutoCAD, SolidWorks,
Excel and Python, and I am familiar with SAP2000, ETABS and OpenSees. I also write engineering
solutions used to train AI models, as a writer for Mercor.

## Projects

**[PowerLaw](https://github.com/cucuradu/PowerLaw)** — A research tool for the EU construction
and building-materials sector, in Python and Streamlit. It pulls legislation from EUR-Lex,
extracts the rules into a graph plus a time-series store, and runs regime, volatility and
supply-chain fragility models on open price data. The app is branded ConstructPulse in its own
interface. All of the commits are mine.

**[GW-back](https://github.com/cucuradu/GW-back)** and
**[GW-front](https://github.com/cucuradu/GW-front)** — GrowWise, a soil-sensor monitoring app:
a Django REST backend and a Flutter client for NPK, moisture and temperature readings, with
rule-based crop recommendations. This was a team university project and most of the commits
are other contributors'. My own work was the containerised Render deployment and the
authenticated-user sensor refactor on the backend, and on the frontend the 2025 UI rework, the
CSV and PDF export, and the Flutter Web build.

**[trading-bot](https://github.com/cucuradu/trading-bot)** — A paper-trading bot that runs on a
schedule: an LLM makes the decisions, Alpaca's paper API executes them, and a tested failsafe
refuses any live order. Paper trading only. Most entries in the commit log are the agent's own
scheduled runs rather than hand-written code.

**[ml-pipeline](https://github.com/cucuradu/ml-pipeline)** — A daily Python pipeline that builds
market features and fits regime (GMM/HMM), volatility (GARCH) and ranking (XGBoost) models,
publishing one JSON signal file for the trading bot to read. Its own write-up is blunt about
the ML ranker losing to a simpler baseline.

## Currently

Second year at Politecnico di Milano, looking for a summer 2027 structural engineering
internship.

My main project, SteelReuse, is in a private repository. It redesigns steel frames around
sections salvaged from demolished buildings: MILP donor-to-demand matching, Eurocode 3 member
checks, an embodied-CO2 passport, IFC export, and frame analysis cross-checked against SAP2000.
I am happy to walk through it or give access on request.
