**AI Podcast Generator Web App**

**Introduction**

This project converts an AI Podcast Generator workflow built in n8n into a no-code web application.
The application allows users to generate podcasts through a simple interface without needing to access n8n directly.

Users can click a button, trigger the workflow, and receive a generated podcast audio automatically.

**Problem**

-n8n workflows are powerful but they are hidden inside the automation tool.

-Only the creator can access the workflow

-Others cannot use it like a normal application

-It requires manual execution inside n8n

**Solution**

-Create a frontend web application that connects to the n8n workflow.

-This allows anyone to use the podcast generator through a simple interface.

**Tools Used**

n8n – Workflow automation

Murf AI – Text to speech for podcast audio

No-Code AI Builders – For creating the frontend interface

API/Webhooks – To connect the frontend with the workflow

**Examples of no-code tools:**

-Replit

-Lovable

-Bolt

-V0 by Vercel

**How the System Works**

User clicks Generate Podcast

↓

Frontend sends request to n8n workflow

↓

n8n generates podcast content

↓

Murf AI converts text to audio

↓

Audio is sent back to the web app

↓

User can listen to the generated podcast

**Workflow Architecture**

User Interface

↓

Trigger n8n Workflow

↓

Generate Podcast Content

↓

Convert Text to Audio

↓

Return Audio to Web App

**Features**

-Simple and user-friendly interface

-Automated podcast generation

-AI-based content creation

-Text-to-speech podcast audio

-Shareable web application

**Before vs After**

**Before**

-Workflow only inside n8n

-Requires manual execution

-Not accessible to others

**After**

-Public web application

-Easy to use interface

-Anyone can generate podcasts

**Future Improvements**

-Add multiple podcast topics

-Allow podcast download option

-Add voice selection

-Integrate podcast publishing platforms
