# Fabric Data Custodian Agent 🤖

An Enterprise AI Agent that monitors Microsoft Fabric data pipelines, 
diagnoses issues using AI reasoning, and auto-fixes them directly in Microsoft Teams.

## Problem
Data teams waste hours every week responding to "why is the dashboard stale?" 
messages from managers. This agent eliminates that entirely.

## Solution
A Teams bot powered by Fabric IQ semantic intelligence that:
- 🔍 Monitors Microsoft Fabric pipelines in real-time
- 🧠 Uses AI multi-step reasoning to diagnose root causes
- ⚡ Auto-fixes stale pipelines with one message
- 📊 Provides business-meaningful context via Fabric IQ
- 🔔 Proactively alerts teams before anyone notices issues

## IQ Integration
Uses **Fabric IQ** semantic layer to understand business meaning of 
workspace data — monitoring lakehouses, pipelines, and semantic models.

## Architecture
![Architecture](architecture.svg)

## Tech Stack
- Microsoft Teams (user interface)
- Azure Bot Service F0 (bot hosting)
- Microsoft Fabric REST API (pipeline monitoring)
- Fabric IQ Semantic Layer (business intelligence context)
- GitHub Models GPT-4o mini (AI reasoning)
- Node.js + Express (bot framework)
- GitHub Copilot (development acceleration)

## Demo Video
[Watch the demo](YOUR_YOUTUBE_URL_HERE)

## Track
Enterprise Agents — Microsoft 365 Copilot

## Setup Instructions
1. Clone this repo
2. Run `npm install`
3. Create `.env` file with your credentials (see `.env.example`)
4. Run `node index.js`
5. Configure Azure Bot Service messaging endpoint
6. Sideload `teams-app.zip` in Microsoft Teams

## Environment Variables
- MicrosoftAppId=your_bot_app_id
- MicrosoftAppPassword=your_bot_secret
- MicrosoftAppTenantId=your_tenant_id
- FABRIC_WORKSPACE_ID=your_fabric_workspace_id
- FABRIC_PIPELINE_ID=your_fabric_pipeline_id
- FABRIC_BEARER_TOKEN=your_fabric_token
- GITHUB_TOKEN=your_github_token
- PORT=3978

## Hackathon
Microsoft Agents League @ AI Skills Fest 2026
