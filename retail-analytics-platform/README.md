# 🛍️ Retail Analytics Platform

End-to-end Analytics Engineering project using Databricks, SQL, Python, Delta Lake, and Power BI.

## Project Overview

This project simulates a real retail analytics environment where raw business data is transformed into trusted, analytics-ready datasets and dashboards.

The goal is to build a modern analytics platform that supports sales, customer, product, marketing, and returns analysis.

## Business Problem

Retail teams often struggle with inconsistent reporting, duplicated metrics, messy raw data, and slow manual analysis.

This project solves that by creating a structured analytics workflow from raw data ingestion to clean business-ready reporting.

## Objectives

- Ingest raw retail data
- Build Bronze, Silver, and Gold data layers
- Create clean fact and dimension tables
- Define trusted business metrics
- Add data quality checks
- Build a Power BI dashboard
- Document the full analytics workflow

## Architecture

```text
Raw CSV Files
     ↓
Bronze Layer
     ↓
Silver Layer
     ↓
Gold Layer
     ↓
Power BI Dashboard