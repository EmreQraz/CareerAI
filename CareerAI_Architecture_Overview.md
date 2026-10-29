# CareerAI - System Architecture & Product Strategy Documentation

## 1. Executive Summary
CareerAI is conceptualized as an end-to-end SaaS platform that leverages Large Language Models (LLMs) to enhance professional profiles and simulate recruitment interviews. This document outlines the system architecture, database flow, and strategic market positioning.

## 2. Technical Requirements & System Architecture
* **Frontend Layer:** Responsive web application interface optimized for fast resume uploads and real-time interactive chat simulations.
* **Backend Services:** RESTful API architecture designed to handle secure authentication, document parsing (PDF/DOCX extraction), and asynchronous LLM queue management.
* **AI Processing Pipeline:** 
  1. Text Extraction & Sanitization
  2. NLP Parsing against target Job Descriptions (JD)
  3. Scoring Engine (ATS Compatibility Metric)
  4. Vector Embedding database storage for contextual interview question generation.

## 3. Database Schema Concept (ER Model Design)
* **Users Table:** Stores account credentials, subscription levels, and timestamps.
* **Resumes Table:** Links users to their uploaded CV texts, parsed JSON structures, and version histories.
* **Interviews Table:** Tracks mock interview sessions, question-answer logs, and performance analytics scores.

## 4. Business Model & Market Strategy
* **Target Audience:** Recent graduates, software engineering candidates, and professionals looking to transition careers.
* **Revenue Streams:** Freemium tier (limited basic scans) + Premium monthly subscription (unlimited AI optimizations and deep mock interview simulations).