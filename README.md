DABA Day 5 – Clause Retrieval and Compliance Analysis
Activity

Design prompts for clause retrieval and compliance analysis

Overview

This Day 5 activity focuses on designing prompts that can identify relevant clauses from procurement contracts and analyze whether a shipment situation complies with those clauses.

The workflow connects shipment issues with contract requirements and produces a structured compliance analysis.

Objective

The main objectives of this activity are:

Retrieve the most relevant contract clause for a shipment issue.
Identify the category of the contract clause.
Analyze shipment compliance with the retrieved clause.
Identify possible contract violations.
Determine the associated compliance risk.
Generate a recommendation for further action.
Workflow
Shipment Issue
      ↓
Contract Clause Knowledge Base
      ↓
Clause Retrieval Prompt
      ↓
Relevant Contract Clause
      ↓
Compliance Analysis Prompt
      ↓
Compliance Status
      ↓
Violation Detection
      ↓
Risk Level
      ↓
Recommendation
Clause Knowledge Base

The clause knowledge base contains example procurement contract requirements related to:

Delivery
Delay Notification
Insurance
Payment
Termination
Example
Delivery Clause:
Supplier must deliver goods within 7 business days.

Delay Notification Clause:
Supplier must notify the buyer within 24 hours
of any delivery delay.
Clause Retrieval Prompt

The clause retrieval prompt is designed to identify the contract clause that is most relevant to a given shipment issue.

The prompt considers:

Contract clauses
Shipment issue
Clause category
Relevant clause
Reason for selecting the clause
Output
Clause Category:
Relevant Clause:
Reason:
Compliance Analysis Prompt

The compliance analysis prompt compares the shipment information with the relevant contract clause.

It identifies:

Compliance status
Contract violation
Risk level
Reason
Recommended action
Output
Compliance Status:
Violation:
Risk Level:
Reason:
Recommendation:
Example Scenario
Shipment Issue
The shipment was delivered 3 days later than the planned
delivery date. The vendor did not notify the buyer about
the delay within 24 hours.
Retrieved Clauses
Delivery:
Supplier must deliver goods within 7 business days.

Delay Notification:
Supplier must notify the buyer within 24 hours
of any delivery delay.
Compliance Analysis
Compliance Status: Non-Compliant

Violation:
Delivery exceeded the contractual delivery period
and the required delay notification was not provided.

Risk Level: High

Recommendation:
Review vendor performance and check the contract's
delay procedure.
Technologies Used
Python
Google Colab
Pandas
Project Components
DABA-Day5-Clause-Compliance/
│
├── README.md
│
├── DABA_Day5_Clause_Compliance.ipynb
│
├── data/
│   └── contract_clauses.csv
│
└── screenshots/
    ├── clause_knowledge_base.png
    ├── clause_retrieval.png
    └── compliance_analysis.png
Key Outcome

The activity successfully demonstrates how structured prompts can be designed for:

Contract Clause Retrieval → Compliance Analysis → Risk Identification → Recommendation

This workflow can be further extended using NLP or Large Language Models for semantic contract analysis and automated compliance monitoring.
