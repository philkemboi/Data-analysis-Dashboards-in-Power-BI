📊 Power BI Dashboard — Pharmaceutical Sales Analytics
This repository contains the Power BI portion of the Afyanalytics Case Study, built on a cleaned, long-format sales dataset. The goal was to transform raw transactional data into an interactive, decision-ready reporting layer.

What's Inside
Data Model

Star schema built from the cleaned dataset: Fact_Sales + dim_product, dim_state, dim_trade_channel, and a dedicated Date table

Proper relationships, marked date table, and optimized for time intelligence

Key Features

🔄 Dynamic metric toggle — switch between CU, Units, and USD Value across all visuals

📅 36-month trend analysis with proper date hierarchy

🎛️ Configurable ranking attribute for Top-N visuals (swap between States, Manufacturers, Products)

🍩 Diabetes portfolio filter for focused therapeutic-area analysis

Report Pages
1. Executive Overview

KPI cards for CU, Units, and USD Value

36-month trend line

Top 5 Manufacturers and Top 5 States

3–5 written executive insights

2. Top 10s & Drivers

Top 10 States, Manufacturers, and Products

Pareto / % share contribution visuals

Toggle to change the ranking metric on the fly

3. Segment & Diabetes Deep-Dive

Filtered view for diabetes-related products

Combined dimensional views (State × Trade Channel, Manufacturer × State)

Price-per-Unit trend analysis

Written commentary on diabetes portfolio performance

Files
Afyanalytics_Dashboards.pbix — main Power BI file

/screenshots — page previews and model view

/docs — supporting notes and insight write-ups

Notes
All visuals use only the cleaned dataset produced by the Python quality gate

Model view screenshot included to demonstrate star schema design

