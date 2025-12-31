# Google Ads Weekly Reporting & Insights Engine

An automated system that converts raw Google Ads data into a client-ready weekly PDF report with performance summaries, alerts, and campaign-level prioritization — with zero manual reporting work.

---

## Problem

Small and mid-sized agencies spend significant time every week:
- exporting Google Ads data
- reconciling week-over-week metrics
- writing performance summaries manually
- deciding which campaigns need attention

This process is repetitive, error-prone, and does not scale well as client count grows.

---

## Solution Overview

This project is a rule-driven reporting and insight engine that:
- ingests Google Ads performance data
- calculates standardized week-over-week KPIs
- detects performance risks and declines
- ranks campaigns by relative impact
- generates a structured, client-ready PDF report automatically

The focus is clarity and decision support — not dashboards.

---

## Output

The system generates a weekly, read-only PDF report that includes:

- Executive performance summary (week-over-week)
- KPI movements with directional indicators
- Automated alerts for critical changes
- Campaign-level impact ranking (top & bottom performers)
- Performance trend visuals
- Narrative summaries explaining what changed and where to focus


---

## Key Design Decisions

- Weekly cadence aligned to agency reporting workflows
- Relative scoring instead of fixed benchmarks to adapt to different accounts
- Clear separation between calculation logic and narrative generation
- Summaries designed to explain context, not just numbers
- PDF-first delivery to match real client reporting formats

---

## Core Capabilities

- Week-over-week performance normalization
- Campaign-level impact scoring
- Automated risk and warning alerts
- Context-aware performance summaries
- Identification of budget pressure and inefficiencies
- Zero manual intervention once data is connected

---

## Skills & Tools Demonstrated

- Data modeling and transformation
- DAX-based KPI logic and normalization
- Power Query / ETL workflows
- Rule-based insight generation
- Decision-focused report design
- Automation-first problem solving

---

## Scope & Limitations

This project is:
- an internal reporting and insight engine
- designed for weekly Google Ads analysis
- focused on prioritization and clarity

This project is not:
- a live dashboarding product
- an AI optimization system
- an auto-budget execution tool

---

## Project Status

Current stage: Private beta

The system is being shared with a small number of agencies to validate:
