# SkyPulse
**BlueSky Sentiment Pipeline**  
BlueSky social posts → cleaned → AI-classified → visualized

## Overview
SkyPulse is a data pipeline that collects posts from BlueSky, cleans and transforms the data, classifies sentiment using Gemini, and visualizes key trends and engagement patterns.

This project is designed to turn raw BlueSky post data into structured sentiment insights through a simple multi-stage workflow.

## Pipeline Stages

### 1. Install
One-time dependency setup for the environment and required libraries.

### 2. Extract
Authenticated BlueSky API pull to collect relevant social posts.

### 3. Transform
Data preprocessing steps including:
- removing duplicates
- filtering irrelevant content
- cleaning text
- standardizing timestamps

### 4. Load
Batch sentiment classification using Gemini AI.

### 5. Visualize
Generate analytics and charts for:
- sentiment distribution
- daily sentiment trends
- engagement by sentiment

## Features
- End-to-end sentiment analysis pipeline
- BlueSky API integration
- Data cleaning and preprocessing
- AI-powered sentiment classification with Gemini
- Visual reporting for trends and engagement
- Modular workflow that is easy to extend

## Project Flow
```text
BlueSky Posts
   ↓
Extract
   ↓
Transform
   ↓
Gemini Sentiment Classification
   ↓
Visualizations and Insights
