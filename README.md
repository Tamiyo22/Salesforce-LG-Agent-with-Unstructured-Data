# Salesforce-LG-Agent-with-Unstructured-Data

📝 Description

Built an end-to-end Salesforce Data Cloud solution that ingests unstructured data from AWS S3, transforms it into usable insights through Data Lake Objects (DLOs) and Data Model Objects (DMOs), and powers a dynamic AgentForce AI agent deployed on a Salesforce Experience Site for interactive user access.

This is a basic Salesforce Agent prototype I created out of curiosity, to experiment with building a data lake connection between AWS S3 and Salesforce Data Cloud, and to explore how unstructured data can be leveraged and structured while training intelligent agents.


<img width="1908" height="908" alt="AgentBasic" src="https://github.com/user-attachments/assets/7a0a5329-ae73-4ca3-8c14-93fdad6b3ccf" />

<img width="348" height="547" alt="14day" src="https://github.com/user-attachments/assets/77288589-03ae-4854-afbe-6913016f228d" />


https://www.loom.com/share/973add1ae3b142a4b4b0c870a45de8e2?sid=66ef7f84-c212-4f92-b92e-60b6052b8f20



🚀 Overview

This project demonstrates how to integrate AWS S3 with Salesforce Data Cloud to process unstructured data and use it to fuel an intelligent AgentForce agent.
The solution connects external data to Salesforce, enabling real-time insights, dynamic conversation, and workflow automation powered by Prompt Builder.

🎯 Objectives

✅ Connect AWS S3 as an external data source for Salesforce Data Cloud.

✅ Ingest and transform unstructured data into DLOs and DMOs for structured analysis.

✅ Build a dynamic AI agent using AgentForce that leverages Data Cloud insights.

✅ Expose the agent through a Salesforce Experience Site for user access.

✅ Use Prompt Builder to enhance response quality and automate workflows.


🧩 Architecture Overview


         ┌──────────────────────────┐
         │        AWS S3            │
         │ (PDFs, images, text)     │
         └───────────┬──────────────┘
                     │
          Data ingestion connector/
                     │
         ┌───────────▼──────────────┐
         │ Salesforce Data Cloud     │
         │ DLOs + DMOs (Transformation)│
         └───────────┬──────────────┘
                     │
         Context + Prompt Builder + AgentForce
                     │
         ┌───────────▼──────────────┐
         │   AgentForce AI Agent    │
         │ (Dynamic responses)      │
         └───────────┬──────────────┘
                     │
         Exposed via Experience Cloud
                     │
         ┌───────────▼──────────────┐
         │     User Interface       │
         └──────────────────────────┘


 🛠️ Tools & Technologies
 
 
| Category            | Tools / Services                                    |
| ------------------- | --------------------------------------------------- |
| **Data Source**     | AWS S3                                              |
| **CRM Platform**    | Salesforce Data Cloud                               |
| **Data Objects**    | Data Lake Objects (DLOs), Data Model Objects (DMOs) |
| **AI & Automation** | AgentForce, Prompt Builder                          |
| **UI Layer**        | Salesforce Experience Cloud                         |
| **Deployment**      | Salesforce CLI (SFDX), Metadata API                 |


⚙️ Setup & Configuration

1️⃣ Connect AWS S3 to Salesforce Data Cloud

Configure AWS S3 connector credentials.

Map unstructured data (text, images, PDFs) to DLOs.

Validate ingestion and confirm DLO population.

2️⃣ Transform Data into DMOs

Map DLO attributes to DMOs for structured representation.

Enable unified profiles and relationships for queryable insights.

3️⃣ Build the AgentForce AI Agent

Create a new Agent in AgentForce Studio.

Configure context to pull knowledge from DMOs.

Define intents, logic, and actions using Prompt Builder.

4️⃣ Deploy Agent to Experience Cloud

Add the “AgentForce Chat” component to an Experience Site page.

Publish and test user interactions through the site.



Key Features

🔄 Automated ingestion of unstructured AWS S3 data into Salesforce Data Cloud.

🗂 Transformation using DLOs and DMOs for structured analytics.

🤖 Dynamic AgentForce AI agent using Prompt Builder logic.

🌐 Deployment through Salesforce Experience Cloud for external access.

⚡ End-to-end automation for intelligent data-driven workflows.





