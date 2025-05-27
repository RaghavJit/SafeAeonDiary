# Week 18 – May 3, 2025
### Server Inactivity Alert Workflow – Reducing False Positives by 98%

This week I worked on my first real automation task in Tines—optimizing the Server Inactivity Alert process.

Previously, any server flagged as inactive would generate a Jira ticket, but most of these were false positives—caused by temporary disconnections, maintenance, or power issues. These tickets were causing noise, wasting time for SOC analysts.

I collaborated with the team to design a Tines workflow that:

Validated the server inactivity status by checking it across a defined timeframe.

Only escalated alerts if inactivity persisted beyond the threshold.

Skipped known test devices or maintenance schedules.

Created Jira tickets only for actionable alerts.

The result? The volume of tickets related to server inactivity dropped by 98%, without compromising coverage. This was a huge win in improving signal-to-noise ratio in alert management.