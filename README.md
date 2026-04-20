# Sales Automation 1

## Overview

A sales lead generation workflow that reads company data from a Google Sheet, uses an AI agent with Tavily web search to find company domains, searches Apollo for decision-makers, enriches contacts with email data, cleans the results, and saves qualified leads to a Google Sheet. It filters leads by ICP criteria before outputting.

## How It Works

```
Manual Trigger -> Google Sheets (read companies) -> Limit -> AI Agent (find domain via Tavily) -> Apollo People Search -> People Enrich -> Data Cleaning -> Filter by ICP -> Google Sheets (save leads)
```

## Integrations

- **Google Sheets** - Company data source and lead output
- **OpenAI** - Domain research via AI agent
- **Tavily** - Web search tool
- **Apollo** - People search and enrichment

## Setup

1. Import `Sales_Automation_1.json` into your n8n instance.
2. Configure all credentials.
3. Update the Google Sheet document ID.
4. Execute manually.
