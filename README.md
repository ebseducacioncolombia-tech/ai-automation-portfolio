# AI Automation Portfolio — Carlos Restrepo

Production-grade AI automation workflows built using n8n, OpenAI, PostgreSQL, Twilio WhatsApp API, Google Vision OCR, and Google Sheets.

This portfolio demonstrates real-world AI automation systems deployed in production environments, including conversational AI agents and intelligent document processing pipelines.

---

# Project 1 — WhatsApp AI Assistant with Persistent Memory

## Overview

An AI-powered WhatsApp assistant capable of maintaining persistent memory, understanding user intent, and responding contextually using LLMs and PostgreSQL.

This system is fully automated and deployed using Twilio webhooks and n8n workflow orchestration.

## Architecture

WhatsApp → Twilio → n8n → AI Agent → PostgreSQL Memory → WhatsApp Response

## Capabilities

• Persistent conversation memory using PostgreSQL  
• Context-aware AI responses using LLM  
• Automated WhatsApp message handling  
• Production webhook architecture  
• Scalable workflow orchestration using n8n  

## Workflow File

`whatsapp-ai-assistant-sanitized.json`

---

# Project 2 — Automated Invoice Processing System (OCR + AI)

## Overview

Fully automated system that extracts structured financial data from invoice images received via Gmail.

Uses Google Vision OCR combined with LLM extraction to convert unstructured invoice images into structured data stored in Google Sheets and delivered via Telegram.

## Architecture

Gmail → Google Vision OCR → LLM extraction → Data normalization → Google Sheets → Telegram notification

## Capabilities

• OCR extraction from invoice images  
• Structured JSON generation using LLM  
• Automated financial data normalization  
• Google Sheets integration  
• Telegram notifications  
• Fully automated email-triggered pipeline  

## Workflow File

`factura-telegram-gmail-v5-sanitized.json`

---

# Technical Stack

• n8n — workflow orchestration  
• OpenAI / LLM — natural language processing  
• PostgreSQL — persistent memory database  
• Twilio WhatsApp API — messaging integration  
• Google Vision OCR — document data extraction  
• Google Sheets API — structured data storage  
• Telegram API — automated notifications  
• Docker / VPS — production deployment  

---

# Author

Carlos Restrepo  
AI Automation Engineer  

Specializing in:

• LLM automation systems  
• Conversational AI agents  
• Intelligent document processing  
• Workflow orchestration using n8n  

GitHub: https://github.com/ebseducacioncolombia-tech
