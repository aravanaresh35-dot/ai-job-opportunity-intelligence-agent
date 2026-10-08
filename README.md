# AI Job Opportunity Intelligence Agent

An AI-powered job analysis and matching workflow built using n8n.

## Overview

This project analyzes a job opportunity and compares its required skills with a candidate's skill profile.

The workflow generates:
- Match Score
- Matched Skills
- Missing Skills
- Application Priority
- Short Reason for the Match

## Workflow

Webhook
→ Edit Fields
→ AI Agent
→ IF (Match Score >= 70)
→ Google Sheets
→ Gmail

## Technologies

- n8n
- AI / LLM
- OpenAI
- REST API / Webhooks
- JSON
- JavaScript Expressions
- Google Sheets
- Gmail

## Key Features

- Job opportunity analysis
- AI-based skill matching
- Match score generation
- Skill gap identification
- Application priority
- Google Sheets tracking
- Automated email notification

## Example

Input:

Job Title: AI Automation Intern

Required Skills:
n8n, REST APIs, Webhooks, JSON, JavaScript, AI Agents

Output:

Match Score: 100/100
Priority: High

## Project Purpose

The goal of this project is to automate the initial analysis of job opportunities and help candidates prioritize relevant opportunities.

## Disclaimer

This project is for educational and portfolio purposes.
