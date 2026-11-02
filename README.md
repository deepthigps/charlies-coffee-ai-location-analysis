# ☕ Charlie's Coffee | AI-Assisted Retail Analytics

**Exploring how AI agents and cloud data tools can turn business questions into actionable insights.**

A hands-on AI and data analytics project developed during **The Gen Academy's Google Data Agent Kit workshop**.

Using Codex, MCP-connected tools, BigQuery, and cloud data sources, I explored retail performance data and built an interactive dashboard to communicate business insights.

### 🚀 [Explore the Live Dashboard](https://deepthigps.github.io/charlies-coffee-ai-location-analysis/charlies-dashboard.html)

## 🎯 Business Problem

Charlie's Coffee operates six stores across San Francisco. How can the business use its data to:

- Compare store revenue and performance?
- Understand neighborhood coffee-market demand?
- Identify products at risk of running out?
- Support more informed retail expansion decisions?

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| OpenAI Codex | AI-assisted analysis and dashboard development |
| Google Data Agent Kit | Workshop agent tooling |
| Model Context Protocol (MCP) | Connecting AI tools to external data services |
| Google BigQuery | Historical sales and market-demand analysis |
| AlloyDB | Inventory and stock-movement information |
| HTML, CSS, JavaScript | Interactive dashboard |
| Google Cloud Run | Initial workshop deployment |
| GitHub Pages | Public portfolio hosting |

## 📊 Dashboard Features

### 1. Store Performance

Compare average weekly revenue across six stores and identify top-performing locations.

### 2. Market Demand Analysis

Explore neighborhood-level estimated coffee spending and compare store revenue with estimated market capture.

### 3. Inventory Monitoring

Identify products below reorder thresholds, investigate replenishment pressure, and review recommended inventory controls.

## 🔎 Selected Findings

**Store performance**
- Six-store average weekly revenue: approximately $152.9K.
- Mission District leads with approximately $32.4K in average weekly revenue.

**Market demand**
- North Beach has the highest estimated market capture among the six stores at 26%.
- High neighborhood demand does not automatically translate into the highest store revenue.

**Inventory**
- Three products are below reorder thresholds.
- Ceremonial Matcha Latte at North Beach has zero units on hand.

These findings reflect the workshop data snapshot and should not be interpreted as live operational metrics.

## 🤖 AI-Assisted Workflow

1. Explore retail business questions using Codex.
2. Use MCP-connected tools to access cloud data sources.
3. Analyze sales, market demand, and inventory information.
4. Translate the results into an interactive dashboard.
5. Publish a standalone version using GitHub Pages.

**Architecture overview**

Business Questions → Codex + MCP Tools → Cloud Data Sources → Analysis → Interactive Dashboard

The published dashboard contains embedded data summaries. It does not make live BigQuery or AlloyDB requests.

## 💡 What I Learned

- How AI agents can support data exploration through natural-language instructions.
- How MCP connects AI workflows with external tools and data sources.
- How to combine business understanding with AI-assisted development.
- Why validating metrics and understanding data limitations matters.
- How to publish and share an interactive analytics project.

## 📂 Repository Structure

```text
charlies-coffee-ai-location-analysis/
├── README.md
└── charlies-dashboard.html
```

## ▶️ Run Locally

Download `charlies-dashboard.html` and open it in a modern web browser. No database credentials or local server are required.

## 🙌 Acknowledgments

Built as a learning project during **The Gen Academy's Google Data Agent Kit workshop** with Aishwarya Srinivasan, Arvind Narayanamurthy, and Jeff Nelson.

The workshop provided the learning environment and guided exercises. The dashboard was developed using AI-assisted tooling as part of that experience.

---

**Sai Deepthi P S G**

*Learning, building, and sharing practical projects in Data Science, Analytics, and AI.*
