---
layout: single
title: "Cybersecurity & Financial Threat Intelligence Aggregator"
permalink: /projects/threatfeed/
---

![Dashboard Screenshot](/assets/images/projects/CleanCyberThreatFeedSS.jpg)

📡 My Custom Cybersecurity & Financial Threat Intelligence Aggregator (Flask Web App)

This is a custom-built Flask web application I designed to scrape and collect the latest headlines and alerts from across the cybersecurity, finance, cryptocurrency, geopolitics, crime, and world news ecosystems. It serves as a centralized dashboard for monitoring breaking news, active cyber threats, financial market movements, and geopolitical events relevant to incident response, penetration testing, cloud infrastructure security, and strategic risk monitoring.

Reason being? Well, as someone diving deeper into cybersecurity operations and cloud infrastructure security, I kept running into the same issue: information overload and wasted time. Between dozens of RSS feeds, industry blogs, and sites like Bloomberg removing their RSS endpoints, staying current on relevant threats, incidents, and financial trends was becoming a chore and a drain with all the jumping around. I needed a way to cut through the noise and surface the most actionable, security-relevant headlines — fast.

So, I built it myself.

🛠️ The Idea

I wanted a personal dashboard that could pull news and alerts from multiple trusted sources — cybersecurity sites, financial publications, crime bulletins, and world news — then filter them by keywords relevant to my daily work as an incident responder, pentester, cloud engineer, and sysadmin. Think APT alerts, ransomware incidents, critical vulnerabilities, market-moving crypto crime stories, and geopolitical conflicts with cyber risk implications.

This Flask web app combines:
- Trusted sources like BleepingComputer, Dark Reading, The Hacker News, Bloomberg World, and various Crypto sections
- RSS feed aggregation using feedparser
- Direct web scraping for sites like Bloomberg (which killed off public RSS feeds for several key sections)
- Asynchronous feed fetching with Python’s ThreadPoolExecutor to pull multiple feeds and scrapes in parallel, without blocking the server
- Keyword-based filtering to surface only high-priority articles
- Caching with Flask-Caching to improve performance and avoid hammering the same endpoints every few minutes
- 
The result is a clean, lightweight web dashboard that shows me the latest threat intelligence and financial risk signals in near real-time — tailored specifically for the work I do.


📊 Why This Matters

In cybersecurity, timing is everything. Getting a zero-day disclosure, nation-state attribution, or critical infrastructure ransomware report even 30 minutes before your competitors can make all the difference in patching, escalation, or response prep. This tool helps me stay a step ahead without the noise.

Plus, integrating finance and world news lets me track how macro events might ripple into the cloud and enterprise tech spaces. A geopolitical conflict in a region hosting major data centers? A regulatory crackdown on a crypto exchange? This dashboard catches it.


🚀 What’s Next

Somewhere down the line I’m planning to enhance it with:
- A search and sort feature for articles by keyword or category
- Optional email or webhook alerts
- Dockerizing the app for cloud deployment
- Potentially building a simple mobile-friendly front end so I can check alerts on the go
  
It’s already become a core part of my workflow — and one of the most useful personal tools I’ve built so far.

Check it out for yourself below!

[View the source on GitHub](https://github.com/amtakeuchi/portfolio/tree/main/cyber_newsfeed_web)
