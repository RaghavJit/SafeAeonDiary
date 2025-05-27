# Week 4 – January 25, 2025
### Introduction to SIEM and Rapid7 InsightIDR

In week four, we transitioned into one of the most critical components of enterprise security infrastructure: the Security Information and Event Management (SIEM) system. Specifically, we began working with Rapid7 InsightIDR, a cloud-native SIEM that helps detect, investigate, and respond to threats using log data.

We started by understanding the role of SIEM in a Security Operations Center. Unlike EDR or email security platforms that focus on specific vectors, SIEMs aggregate logs from various sources—firewalls, endpoints, applications, servers, and cloud services—giving analysts a comprehensive, centralized view of their environment.

We learned how Rapid7 collects logs, from agents deployed on endpoints to syslog servers and integrations with cloud applications. Then we explored how these logs are parsed, normalized, and enriched with context before being made searchable. The platform’s ability to generate actionable alerts from seemingly disparate log events was particularly impressive.

Hands-on sessions included learning log searching using Rapid7’s query interface, which allowed us to filter and pinpoint security-relevant events based on custom queries. This was my first exposure to log analysis at scale, and I began to see how every action taken on a system leaves behind a trace—something that SIEMs are designed to catch.

We were introduced to Rapid7’s query language, which is straightforward yet powerful. It allowed us to write flexible searches to find failed login attempts, lateral movement, use of malicious scripts, or access from suspicious locations.

This week solidified my understanding of how SIEMs serve as the investigative core of a SOC and how tools like InsightIDR support real-time visibility and automated detection.