# Automated Bug Report Generator (n8n)

## Project Overview
This workflow automatically generates structured bug reports from error logs using Groq LLM.

## Workflow Steps
1. Error Log Input (Chat Trigger)
2. Groq LLM (llama-3.3-70b-versatile)
3. Structured Bug Report Parser
4. Send Bug Report Output

## Features
- Uses AI to convert raw logs into structured bug reports
- Anti-hallucination constraint: Uses only provided log data
- Outputs structured JSON format
- Severity classification

## Sample Output Format
{
  "title": "",
  "severity": "",
  "steps_to_reproduce": "",
  "expectedresult": "",
  "actualresult": "",
  "additionalnotes": ""
}

## How to Import
1. Download the JSON workflow file
2. Open n8n
3. Click Import Workflow
4. Upload the JSON file
