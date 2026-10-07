# Business Impact Analysis (BIA) | ShopSphere Pvt. Ltd.

## Project Overview

This project presents a practical **Business Impact Analysis (BIA)** for a fictional e-commerce organization, **ShopSphere Pvt. Ltd.**

The objective of the BIA is to identify critical business processes, understand the potential impact of disruptions, and define appropriate recovery targets using **MTD, RTO, and RPO**.

## Company & Scenario

**Company:** ShopSphere Pvt. Ltd.  
**Industry:** E-commerce  
**Assessment Type:** Business Impact Analysis  
**Project Type:** Cyber GRC Portfolio Case Study

ShopSphere operates an online e-commerce platform where website availability, payment processing, order fulfillment, inventory management, and customer support are important to business operations.

## Objective

The objective of this assessment is to:

- Identify critical business processes
- Understand the impact of process disruption
- Prioritize recovery requirements
- Define MTD, RTO, and RPO targets
- Provide a structured starting point for business continuity planning

## Scope

The assessment covers five key business processes:

- E-commerce Website & Ordering
- Payment Processing
- Order Fulfillment
- Inventory Management
- Customer Support

## BIA Approach

Each business process was assessed based on:

1. Impact of disruption
2. Maximum Tolerable Downtime (MTD)
3. Recovery Time Objective (RTO)
4. Recovery Point Objective (RPO)
5. Business rationale
6. Process ownership

The assessment uses realistic assumptions for a fictional e-commerce organization.

## Key BIA Concepts

### MTD
**Maximum Tolerable Downtime** is the maximum period a business process can remain unavailable before the resulting impact becomes unacceptable.

### RTO
**Recovery Time Objective** is the target time within which a business process should be restored after a disruption.

### RPO
**Recovery Point Objective** is the maximum acceptable amount of data loss measured in time.

## Assessment Summary

| Business Process | Impact | MTD | RTO | RPO |
|---|---|---|---|---|
| E-commerce Website & Ordering | High | 2 hours | 1 hour | 15 minutes |
| Payment Processing | High | 1 hour | 30 minutes | 15 minutes |
| Order Fulfillment | High | 8 hours | 4 hours | 1 hour |
| Inventory Management | High | 8 hours | 4 hours | 1 hour |
| Customer Support | Medium | 24 hours | 8 hours | 4 hours |

## Key Findings

- Website and payment processing require the fastest recovery because disruption directly affects sales and customer transactions.
- Order fulfillment and inventory management can tolerate a longer disruption but may create operational backlogs if unavailable for an extended period.
- Customer support has a comparatively longer recovery window because a short disruption does not immediately stop core sales.
- Recovery targets should be validated with business owners and relevant technical teams before being used in a real environment.

## Deliverables

### 1. BIA Analysis
`ShopSphere_BIA_Analysis.xlsx`

Contains the detailed BIA assessment, including business processes, impact, MTD, RTO, RPO, rationale, and process ownership.

### 2. BIA Report
`ShopSphere_BIA_Report.pdf`

Provides a concise summary of the assessment, key concepts, findings, and conclusions.

## GRC Concepts Demonstrated

- Business Impact Analysis
- Business Continuity
- Recovery Planning
- MTD
- RTO
- RPO
- Business Process Prioritization
- Risk and Impact Assessment
- Process Ownership

## Disclaimer

This is a fictional portfolio case study created for learning and demonstration purposes. The organization, processes, and recovery targets are hypothetical and should not be treated as requirements for a real organization.
