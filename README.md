# 🌍 Adaptify

**Leveraging IoT and RAG with Watsonx.ai to Smartly Track, Optimize, and Reduce Carbon Footprint for Businesses and Individuals**

A real-time environmental monitoring dashboard and AI assistant designed to analyze CO₂ emissions, provide actionable insights, and calculate carbon credits — powered by IBM watsonx.ai and Retrieval-Augmented Generation (RAG).

---

## 🚀 Live Demo

🔗 **Try it here**: [https://40bb433ffea8be2d45.gradio.live/](https://40bb433ffea8be2d45.gradio.live/)  
⚠️ *Note: This share link expires in 1 week.*

🎥 **Watch Demo Video**: [YouTube Link](https://youtu.be/ybUqVFnjNag)

---

## 🧭 Overview

Developed for the **Hackathon for Progress**, this project focuses on sustainability through smart environmental monitoring. It enables stakeholders to:

- Monitor real-time CO₂ levels from IoT sensors.
- Analyze monthly and yearly emission trends.
- Ask AI-powered questions about emissions, carbon credits, and reduction strategies.
- Gain actionable insights using Retrieval-Augmented Generation (RAG).
- Visualize environmental progress through an intuitive dashboard.

---

## 🧠 Powered By

- **IBM watsonx.ai** – Granite 3-8B Instruct model for intelligent Q&A.
- **Tavily API** – Real-time web search for RAG context enrichment.
- **Gradio** – Interactive web interface.
- **Plotly** – Dynamic CO₂ charts and trend visualizations.
- **MySQL** – Backend data storage for sensor readings and summaries.

---

## ⚙️ Features

### 📡 Real-Time Monitoring
- Live data from `realtime_emission_data` table.
- Displays the last 10 CO₂ records.
- Line chart showing emissions over time.

### ♻️ Carbon Credit Calculation
- Compares yearly emissions to determine reduction.
- Calculates credits using:  
  `Carbon Reduced = Emission_Year_N - Emission_Year_N-1`  
  `Credits Earned = Carbon Reduced / 1000`

### 🤖 AI RAG Assistant
- Combines structured sensor data with real-time web context.
- Uses IBM Watsonx for question answering.
- Smart detection of off-topic or unsupported queries.

### 🔍 Web Search Integration
- Tavily API enriches AI responses with the latest external information.
- Helps provide credible, real-time insights.

---

## 🧪 Interface Preview

Built using **Gradio**, the UI has two tabs:

1. **Live Dashboard** – Visualizes CO₂ data and earned carbon credits.
2. **RAG Assistant** – Ask AI anything about your emissions and get data-aware answers.

---

## 🧾 Sample Data Structure

To simulate sensor inputs, populate a MySQL database with the following tables:

- `realtime_emission_data`
- `monthly_emission_summary`
- `yearly_emission_summary`

> 💡 You may include a script to auto-populate mock data for demo purposes.

---

## 💡 Example Use Cases

- "Are this year’s emissions lower than last?"
- "How many carbon credits have we earned this year?"
- "Suggest ways to reduce CO₂ emissions in smart buildings."
- "What are the latest carbon offset technologies?"

---

## 🙌 Acknowledgments

- **IBM watsonx.ai** – for enabling intelligent, sustainable AI solutions.
- **Tavily API** – for enriching AI responses with up-to-date information.
- **Gradio** & **Plotly** – for seamless visualization and user interaction.

---

