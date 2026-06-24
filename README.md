# IT Help Desk Ticketing & SLA Dashboard

## Project Overview
This project simulates an IT help desk ticketing environment and analyzes support performance using Excel and Power BI. The dashboard tracks ticket volume, issue categories, priority levels, SLA performance, escalation trends, and average resolution time.

## Business Problem
IT support teams need visibility into recurring issues, SLA misses, ticket volume, and escalations so they can improve response time and reduce repeated support requests.

## Tools Used
- Excel
- Power BI
- DAX
- Data cleaning
- SLA analysis
- Dashboard reporting

## Dataset
The dataset contains simulated IT support tickets with fields including:
- Ticket ID
- Date Created
- Requester Department
- Issue Category
- Issue Type
- Priority
- Status
- Assigned Team
- Resolution Hours
- SLA Target Hours
- SLA Status
- Escalation Status

## Dashboard Features
The Power BI dashboard includes:
- Total Tickets
- SLA Met Percentage
- Average Resolution Hours
- Escalated Tickets
- Tickets by Issue Category
- Tickets by Priority
- SLA Met vs Missed
- Ticket Volume Over Time
- Ticket Details Table

## Key Insights
1. Password reset and access request tickets made up a large portion of total support volume.
2. High and Critical priority tickets had a higher chance of missing SLA targets.
3. Escalated tickets were more common for Security and Network/VPN issues.

## Recommendations
- Create self-service password reset documentation to reduce repetitive tickets.
- Escalate High and Critical tickets faster to improve SLA performance.
- Review recurring Network/VPN issues and create troubleshooting guides for Tier 1 support.

## Project Files
- `help_desk_tickets.xlsx` - Simulated ticket dataset
- `help_desk_dashboard.pbix` - Power BI dashboard file
- `screenshots/` - Dashboard images

## Dashboard Preview
![Dashboard Overview](screenshots/dashboard_overview.png)
