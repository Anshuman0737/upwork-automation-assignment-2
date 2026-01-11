
# AI Engineer Intern Assignment 2 – Upwork Automation

## Overview
This project implements an AI-driven automation workflow using n8n to fetch, analyze, and prioritize Upwork job listings. The workflow integrates Apify for job ingestion, OpenAI for AI-based job scoring, and Airtable for structured storage of qualified leads.

## Workflow Summary
- Scheduled execution every 8 hours using n8n Schedule Trigger
- Job ingestion via Apify Upwork scraper
- Data normalization and preprocessing
- AI-based job scoring with priority classification (High / Medium / Low)
- Structured output parsing
- Storage of results in Airtable for proposal readiness

## Execution Note
The referenced Apify Upwork scraper actor requires a paid subscription. To avoid unnecessary costs and follow production best practices, the actor was not rented during this submission. Once valid Apify billing is enabled, the workflow will execute end-to-end without any modification.

## Tech Stack
- n8n (self-hosted via Docker)
- Apify
- OpenAI
- Airtable
