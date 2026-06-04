# Historical Content Publisher

## Overview

This workflow automatically generates a LinkedIn post about a historical event that happened on the current date. It uses Google Gemini to write an engaging “On This Day in History” style post and publishes it directly to LinkedIn.

---

## Problem Statement

Creating consistent content for LinkedIn every day takes time. Writers often need to find a topic, research it, write a post, and then publish it manually.

This workflow automates that entire process.

---

## Solution

The workflow:

1. Runs on a schedule.
2. Uses the current date as input.
3. Asks Gemini to generate a historical event post.
4. Formats the content as a professional LinkedIn post.
5. Publishes the post directly on LinkedIn.

---

## Workflow Architecture

Schedule Trigger  
↓  
History Generator  
↓  
Google Gemini  
↓  
LinkedIn Post Creation

---

## Technologies Used

- n8n
- Google Gemini
- LinkedIn API
- Scheduled automation

---

## How It Works

### Step 1: Scheduled Trigger
The workflow runs at a fixed time every day.

### Step 2: Topic Selection
It uses the current date to find a relevant historical event.

### Step 3: AI Post Generation
Gemini writes a professional post that includes:
- a strong hook
- the historical event
- its importance
- a discussion question
- hashtags

### Step 4: LinkedIn Publishing
The final text is posted automatically to LinkedIn.

---

## Output

A ready-to-publish LinkedIn history post.

---

## Setup Instructions

1. Import the workflow into n8n.
2. Connect Google Gemini credentials.
3. Connect LinkedIn credentials.
4. Verify the schedule time.
5. Test the workflow in manual mode before enabling it.

---

## Future Improvements

- Add source verification
- Add image generation
- Add auto-scheduling across multiple platforms
- Add post approval before publishing

---

## Author

Pranav Mahesh Palled
