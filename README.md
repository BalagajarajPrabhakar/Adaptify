# Adaptify

# Leveraging IoT and RAG with Watsonx.ai to Smartly Track, Optimize, and Reduce Carbon Footprint for Businesses and Individuals

A real-time environmental monitoring dashboard and AI assistant designed to analyze CO₂ emissions, provide actionable insights, and calculate carbon credits — powered by IBM watsonx.ai and Retrieval-Augmented Generation (RAG).

---

## Overview

This project was developed for the Hackathon for Progress, focusing on sustainability and smart environmental monitoring. It enables stakeholders to:
- Monitor real-time CO₂ levels from smart sensors.
- Analyze monthly and yearly emission trends.
- Ask AI-powered questions about emissions, carbon credits, and reduction strategies.
- Earn insights from web sources via a RAG-based assistant.
- Visualize environmental progress in an intuitive dashboard.

---

## Powered By

- IBM watsonx.ai – AI model (Granite 3-8B Instruct) for intelligent Q&A.
- Tavily – Web search API for real-time RAG context enrichment.
- Gradio – Interactive user interface.
- Plotly – CO₂ visualization and trend charts.
- MySQL – Backend database for sensor and summary data.

---

## Features

### Real-Time Monitoring
- Live fetch from MySQL database.
- Displays the last 10 CO₂ records.
- Line graph showing emission trends.

### Carbon Credit Calculation
- Compares yearly totals to quantify reduction.
- Calculates earned carbon credits based on emission drop.

### AI RAG Assistant
- Combines structured data + web results.
- Uses IBM Watsonx Granite model for domain-specific question answering.
- Out-of-scope detection for unrelated topics.

### Web Search Integration
- Uses Tavily API to fetch relevant web insights for each user query.
- Enriches the AI's responses with up-to-date information.

---

## Interface Preview

Built using Gradio with two interactive tabs:
1. Live Dashboard — CO₂ data and carbon credit visualization.
2. RAG Assistant — Ask questions and get AI-generated, data-aware responses.

---

## Sample Data

To simulate sensor inputs, populate your MySQL DB with tables:
- `realtime_emission_data`
- `monthly_emission_summary`
- `yearly_emission_summary`

You may include a simple script to insert mock data for testing.

---

## Carbon Credit Logic

- Carbon Reduced = Total_Emission_Year_N - Total_Emission_Year_N-1  
- Credit Earned = Carbon Reduced / 1000 (1 credit = 1000 units reduction)

---

## Example Use Cases

- “Are this year’s emissions lower than last?”
- “How many carbon credits have we earned this year?”
- “Suggest ways to reduce CO₂ emissions in smart buildings.”
- “What are the latest carbon offset technologies?”

---

## Acknowledgments

- IBM watsonx.ai – for enabling intelligent, sustainable solutions.
- Tavily API – for enhancing RAG responses with real-time search.
- Gradio and Plotly – for seamless visualization and interaction.

---

## Link

[https://youtu.be/ybUqVFnjNag](https://youtu.be/ybUqVFnjNag)


