# Week 6 – February 8, 2025
### Understanding SafeAeon’s Internal SOC Processes and Automation

In Week 6 of my internship at SafeAeon, we took a step back from tools and technology to understand how the internal operations of the SOC (Security Operations Center) function—especially in a multi-tenant environment where dozens of clients are being monitored simultaneously.

We were introduced to SafeAeon's internal workflows, and how they manage multiple consoles for various clients efficiently. One of the key platforms used in this process is Jira, which is central to their ticketing and communication system. Every alert detected across different security tools and platforms—be it SentinelOne, Avanan, Rapid7, or others—eventually translates into a ticket for SOC analysts to review.

What stood out was SafeAeon's automation setup. They have a dedicated automation team that has built systems to auto-generate tickets in Jira the moment an alert is triggered on any security console. This eliminates manual reporting and speeds up the triage process. Once a ticket is created, a SOC analyst picks it up, investigates, and creates a client-facing ticket with detailed observations and a recommendation. The client then reviews this ticket and provides a verdict—usually marking it as a true or false positive.

This system ensures seamless coordination between automation, SOC analysts, and clients, maintaining both speed and accountability in incident response.

