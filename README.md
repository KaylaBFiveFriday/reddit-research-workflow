# Reddit Discussion Research Workflow

This repository contains an n8n workflow used for **read-only research of publicly available Reddit posts** related to vehicle purchasing and ownership discussions in South Africa.

## Purpose

The workflow is designed to:
- Monitor public Reddit posts and metadata (titles, timestamps, subreddit names)
- Identify common questions and trends about car buying and vehicle ownership
- Support **manual, human review** of discussions

The goal is to better understand frequently asked questions and community topics, not to automate engagement.

## Important Notes

- **Read-only:** The workflow does **not** post, comment, vote, or send messages.
- **No automation of interactions:** All responses are written and submitted manually by a human.
- **Public data only:** The workflow only processes publicly available information.
- **No private data collection:** No private user data is accessed or stored.
- **No mass communication or spam:** The system is not used for automated outreach.

## How It Works (High Level)

1. Searches publicly available Reddit posts using relevant queries.
2. Normalises and lightly filters results for relevance.
3. Generates a daily summary report to assist manual review.
4. Any engagement on Reddit is performed manually by a human user.

## Technology

- **n8n** – workflow automation platform
- **Reddit API** – read-only access to public posts and metadata

## Repository Contents

- `workflow.json` – Exported n8n workflow configuration.
- `README.md` – This documentation file.

## Disclaimer

This project is intended for research and analytical purposes only.  
It does not automate posting, messaging, or any form of unsolicited communication on Reddit.
