# fedex-care-automation
End-to-end case assignment, SLA monitoring, and escalation system built using n8n, Google Sheets, and email automation.
# FedEx CARE Automation System

An automation system to manage overdue cases, assign DCAs intelligently, track SLA breaches, and automate reminders and escalations.

## 🔧 Tech Stack
- n8n (Workflow Automation)
- Google Sheets (Operational Database)
- Gmail API (Email Notifications)

## 🧠 System Architecture
1. Overdue case detection via scheduled trigger
2. Intelligent DCA assignment using Python scoring
3. Human-in-the-loop updates via form
4. SLA monitoring and escalation engine

## 📂 Workflows
- WF1: Overdue Detection & Manager Reminder
- WF2: DCA Update via Form 
- WF3: Intelligent Case Assignment Engine
- WF4: SLA Monitoring & Escalation

## 🚀 How to Run
1. Import n8n workflows from `/n8n-workflows`
2. Configure Google Sheets credentials
3. Run Python decision engine
4. Trigger workflows via Cron or Manual execution

## 📌 Author
Kaustubh Kishor Nikam
