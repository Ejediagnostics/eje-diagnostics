# Eje Diagnostics

> AI-powered fleet audit that turns ignored TMS data into 
> actionable decisions in 48 hours.

## What it does

Eje Diagnostics processes CSV exports from existing Transport 
Management Systems and delivers three findings and three 
executable actions to fleet operators — without installing 
new software or hiring consultants.

## How it works

Two sequential AI agents running on Gemini 2.5 Pro:

**Agent 1 — TecOps Diagnostics**
Processes route/order CSVs and telematics data across four 
diagnostic layers: validation, technical, operational, and 
route/time. Outputs structured findings with evidence and 
a machine-readable HANDOFF block.

**Agent 2 — ROI Calculator**
Receives the HANDOFF and quantifies each finding in USD. 
Calculates frequency from actual data per vehicle. Applies 
statistical confidence levels based on dataset size. 
Separates verified data from assumptions in every output.

## Stack

- Gemini 2.5 Pro (Gemini API)
- Google AI Studio
- Google Forms (client intake)
- Google Drive (CSV storage)

## Business model

Free 48-hour audit → Monthly monitoring subscription  
USD 200–800/month depending on fleet size.

## Category

Small Business Services — XPRIZE x Google Hackathon 2026

## Author

Federico — Logistics Planning Student + 15 years refrigeration 
technical experience. Universidad Nacional de Lanús, Argentina.
