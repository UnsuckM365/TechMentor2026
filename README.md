# Microsoft 365 Admin Intelligence - TechMentor 2026

Resources, examples, and demos from my TechMentor 2026 session:

**TW18 - Stop Drowning in Updates: Build a System for Microsoft 365 Admin News and Roadmap Alerts**

[View the full repository](https://github.com/UnsuckM365/TechMentor2026)

The goal of this session was simple:

Microsoft gives us plenty of information about what is changing in Microsoft 365. The problem is figuring out what actually matters to our organization.

Instead of manually reading hundreds of updates, we can build systems that collect, filter, summarize, categorize, and route Microsoft 365 changes into the places where work already happens.

> We didn't rebuild Microsoft's roadmap. We built our organization's roadmap.

---

## What This Repository Contains

This repository contains examples used during the session to demonstrate different ways of consuming and processing Microsoft 365 Roadmap information.

---

## MCP

[Browse the MCP folder](https://github.com/UnsuckM365/TechMentor2026/tree/main/MCP)

Examples using Microsoft's Microsoft 365 Roadmap **Model Context Protocol (MCP) server**.

The MCP server allows AI tools and agents to query Microsoft 365 Roadmap information directly instead of manually browsing the public roadmap.

Examples include:

- [M365 Roadmap Report - August 2026](https://github.com/UnsuckM365/TechMentor2026/blob/main/MCP/M365_Roadmap_Report_August_2026.md)
- [Microsoft 365 Current Month Prompt / Template](https://github.com/UnsuckM365/TechMentor2026/blob/main/MCP/Microsoft365-CurrentMonth.md)
- Categorized roadmap results
- Prioritized or highlighted changes
- AI-generated summaries based on roadmap data

These examples demonstrate how tools that support MCP can turn roadmap data into useful reports with very little custom development.

### Microsoft Resources

- [Microsoft 365 Roadmap](https://www.microsoft.com/microsoft-365/roadmap)
- [Microsoft 365 Roadmap MCP](https://www.microsoft.com/releasecommunications/mcp)

---

## SharePoint Skills

[Browse the SharePoint folder](https://github.com/UnsuckM365/TechMentor2026/tree/main/SharePoint)

Examples showing how Microsoft 365 Roadmap intelligence can be packaged into reusable **SharePoint skills**.

### `m365-roadmap-list`

[View the skill](https://github.com/UnsuckM365/TechMentor2026/tree/main/SharePoint/m365-roadmap-list)

Designed to retrieve and organize Microsoft 365 Roadmap information into a structured list of relevant changes.

[View SKILL.md](https://github.com/UnsuckM365/TechMentor2026/blob/main/SharePoint/m365-roadmap-list/SKILL.md)

### `m365-roadmap-monthly-report`

[View the skill](https://github.com/UnsuckM365/TechMentor2026/tree/main/SharePoint/m365-roadmap-monthly-report)

Designed to generate a monthly Microsoft 365 Roadmap report containing selected updates, summaries, impact information, and recommended items to watch.

[View SKILL.md](https://github.com/UnsuckM365/TechMentor2026/blob/main/SharePoint/m365-roadmap-monthly-report/SKILL.md)

Example outputs:

- [M365 Roadmap Monthly Report - August 2026](https://github.com/UnsuckM365/TechMentor2026/blob/main/SharePoint/M365%20Roadmap%20Monthly%20Report%20-%20August%202026.md)
- [FAQ - M365 Roadmap Monthly Report - August 2026](https://github.com/UnsuckM365/TechMentor2026/blob/main/SharePoint/FAQ%20-%20M365%20Roadmap%20Monthly%20Report%20-%20August%202026.md)

For additional SharePoint skill examples:

[UnsuckM365 SharePoint AI Skills](https://github.com/UnsuckM365/sharepoint-ai-skills)

---

## The Bigger Idea

The Microsoft 365 Roadmap is only one source of change information.

During the session we looked at a progression like this:

```text
Microsoft 365 Roadmap
        |
        v
Microsoft 365 Message Center
        |
        v
Filtering and prioritization
        |
        v
Automation
        |
        v
Planner / SharePoint / Teams / Email
        |
        v
Your organization's Microsoft 365 roadmap
