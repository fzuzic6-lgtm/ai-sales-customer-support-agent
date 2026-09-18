# AI Sales & Customer Support Agent

An AI-powered sales and customer support agent built with n8n, Claude, and Google Sheets.

The agent can answer customer questions about products, search a product database, check prices and stock availability, and automatically collect potential customer leads.
## Workflow Overview

![AI Sales & Customer Support Agent Workflow](Snimka%20zaslona%202026-09-18%20141457.png)

## Features

- AI-powered customer conversations
- Product search using Google Sheets
- Price and stock availability lookup
- Product recommendations
- Conversation memory
- Automatic lead capture
- Saves customer name, email, product interest, message, and lead status to Google Sheets

## Workflow

1. Customer sends a message through the n8n chat.
2. Claude understands the customer's request.
3. The AI agent searches the connected Google Sheets product database when product information is needed.
4. The agent responds with relevant product information.
5. If the customer shows purchase interest, the agent asks for their name and email.
6. The lead is automatically saved to a separate Leads sheet.

## Technologies

- n8n
- Claude / Anthropic
- Google Sheets
- AI Agent
- Workflow Automation
- API / OAuth integrations

## Example

Customer:
> Do you have a gaming laptop?

AI Agent:
> Yes! We have the Gaming Pro G5 for $1,599. It is a high-performance gaming laptop with dedicated graphics and is currently in stock.

When the customer decides they are interested, the workflow collects their contact information and automatically creates a new lead.

## Project Purpose

This project demonstrates how AI agents can be connected with business data and automation tools to create a practical sales and customer support system.

It was built as a personal portfolio project to demonstrate hands-on experience with n8n workflow automation, AI integrations, Google Sheets, and automated lead management.
