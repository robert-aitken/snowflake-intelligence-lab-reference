# Snowflake Intelligence Lab Reference

Personal lab reference for a Snowflake Intelligence workshop covering Cortex AI, Cortex Analyst, Cortex Search, AI agents and governed analytical AI application patterns.

This repository is a personal follow-along reference based on the Snowflake guide for getting started with Snowflake Intelligence. It is kept as a learning-history reference rather than as an active production project.

The original repository used for this fork was:

https://github.com/Snowflake-Labs/sfguide-getting-started-with-snowflake-intelligence

The step-by-step guide followed was:

https://www.snowflake.com/en/developers/guides/getting-started-with-snowflake-intelligence/

## Workshop Details

| Field | Details |
|---|---|
| Workshop | Building Intelligent Applications with Snowflake |
| Provider | Snowflake |
| Speaker | Dash Desai |
| Format | Virtual Workshop |
| Date Completed | 13/05/2026 |
| Duration | 2 Hours |
| Badge Awarded | Yes |
| Credential URL | https://developerbadges.snowflake.com/f826b319-0297-4381-86b6-93b3795a24bd |

## Repository Contents

This repository contains SQL setup scripts and supporting files used to follow along with the Snowflake Intelligence lab.

| File | Purpose |
|---|---|
| setup.sql | Creates the Snowflake database, schema, tables and supporting objects needed for the lab. |
| marketing_campaigns.yaml | Semantic model file used by Cortex Analyst to map business concepts to underlying Snowflake data. |

## Lab Order Followed

I followed the lab in this order:

1. Forked the Snowflake Labs repository.
2. Opened the Snowflake guide for getting started with Snowflake Intelligence.
3. Ran setup.sql in a Snowsight SQL worksheet.
4. Switched to the SNOWFLAKE_INTELLIGENCE_ADMIN role.
5. Uploaded the marketing_campaigns.yaml semantic model for Cortex Analyst.
6. Created a Cortex Search service over support case transcript data.
7. Created a Snowflake Intelligence agent called Sales_AI.
8. Added Cortex Analyst, Cortex Search and a custom email tool to the agent.
9. Tested the agent using natural language questions about sales trends, product issues and support cases.

## What Gets Created

The lab creates a Snowflake environment for exploring Snowflake Intelligence.

The setup includes:

- Database and schema objects for the lab.
- Retail-style sample data.
- Structured marketing and sales data.
- Unstructured support case transcript data.
- A semantic model for Cortex Analyst.
- A Cortex Search service for retrieval over support cases.
- A Snowflake Intelligence agent for natural language analysis.

## High-Level Topics Covered

The lab covered:

- Snowflake Intelligence
- Cortex Analyst
- Cortex Search
- Cortex AI
- Semantic models
- AI agents
- Retrieval Augmented Generation
- Structured data analysis
- Unstructured text search
- Natural language querying
- Agent tools
- Custom tool configuration
- AI-assisted analytical workflows
- Governed enterprise AI patterns

## Personal Takeaways

My main takeaway was that Snowflake Intelligence provides an agent-based interface for asking natural language questions across both structured and unstructured data.

I learnt that Cortex Analyst is used for structured data analysis. It uses a semantic model to help map business terms, such as sales, product category and campaign performance, to the underlying database tables and columns.

I also learnt that Cortex Search is used for unstructured text data, such as support case transcripts. This allows an agent to search relevant text chunks and use retrieval-style patterns to answer questions.

The lab showed how an agent can combine multiple tools. In this example, the Sales_AI agent used:

- Cortex Analyst for structured sales and marketing data.
- Cortex Search for customer support case transcripts.
- A custom email tool for sending a summary email.

A key practical learning point was that Snowflake Intelligence is not just a chatbot over one table. It is an agent pattern where structured data, unstructured text, semantic models, search services and custom actions can be combined inside Snowflake's governed environment.

The lab also helped me understand how business users could ask questions such as:

- Show me the trend of sales by product category between June and August.
- What issues are reported with jackets recently in customer support tickets?
- Why did sales of Fitness Wear grow so much in July?
- Which product categories perform best on social media?
- What is the relationship between social media mentions and sales?

## How This Relates To My Work

This lab is relevant to governed AI, analytical agents, self-service analytics, semantic modelling and natural language interfaces over enterprise data.

It is useful background for comparing Snowflake Intelligence with other AI-assisted data workflows, including Azure-based AI services, semantic layers, chatbot-style analytics and traditional BI reporting.

It also connects to wider data engineering topics such as data modelling, data governance, structured data pipelines, unstructured data processing and analytical application design.

## Private Notes

I kept private notes while following the lab, including screenshots, account details, workspace references and personal observations.

Those notes are not included in this repository because they may contain private account details, workspace URLs, screenshots or environment-specific information.

This README only contains a rewritten summary of my own learning.

## What Is Not Included

This repository does not include:

- Passwords
- Trial account details
- Work email addresses
- Workspace URLs
- Private screenshots
- Private Word notes
- Copied workshop slide screenshots
- Private course or event material

## Notes On This Fork

This fork is retained as a personal archival reference for learning history only.

It should not be treated as a production-ready Snowflake project.

The original upstream history and commit metadata have been preserved by GitHub through the fork relationship.

The original guide notes that the content is provided as is and may become out of date with current Snowflake instances.

## License

See LICENSE for details.
