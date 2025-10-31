# Phase 1 Workflow – Search & Collect URLs

File: phase1-search.json

Purpose:
- Accepts a topic as input
- Searches web using SerpAPI
- Extracts top 10 URLs with title and source
- Outputs clean JSON list

Nodes Used:
- Manual Trigger
- Set Node (topic)
- HTTP Request / API Node (SerpAPI)
- Function Node (extract top 10 URLs)

Usage:
1. Import JSON into n8n
2. Configure API key
3. Run workflow manually to test
