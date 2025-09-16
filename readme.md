# Ryan Le AI Chatbot

Check it out:
https://n8n.ryanle.ca/webhook/b2901b84-89f4-44c1-8958-b3a8cb93855c/chat

An intelligent chatbot that answers questions about my professional background, projects, and technical experience.

## Overview

This AI assistant provides detailed information about:
- Technical skills and programming languages
- Professional experience at Government of Manitoba
- Award-winning projects (Folklorama Map, RampUp 2024)
- Homelab infrastructure and automation workflows
- Contact information and availability

## Tech Stack

- **Platform:** n8n workflow automation
- **AI Model:** Groq + Llama 3.1 (free tier)
- **Interface:** n8n Chat Trigger (web-based)
- **Deployment:** Self-hosted on homelab server

## Features

- 🤖 Professional AI responses about my work experience
- 💬 Interactive web chat interface
- 📱 Mobile-responsive design
- 🚀 Fast response times via Groq API
- 🔗 Direct links to projects and portfolio
- 📞 Contact information and availability status

## Chat Topics

Ask about:
- Programming languages and frameworks I use
- Government emergency management system projects
- Folklorama mapping application (500+ daily users)
- RampUp 2024 first place win ($10,000)
- Homelab infrastructure with Docker/n8n automation
- Academic background and current studies
- How to get in touch for opportunities

## Technical Implementation

**N8N Workflow:**
```
Chat Trigger → Groq AI Model → Chat Response
```

**Key Components:**
- Chat Trigger with starter prompts
- Groq Chat Model (llama3-8b-8192)
- Comprehensive system prompt with professional context
- Automated response formatting

## Usage

Visit the live chat interface: https://n8n.ryanle.ca/webhook/b2901b84-89f4-44c1-8958-b3a8cb93855c/chat

Or embed in websites using iframe:
```html
<iframe src="https://n8n.ryanle.ca/webhook/b2901b84-89f4-44c1-8958-b3a8cb93855c/chat" width="400" height="600"></iframe>
```

---

*This chatbot is part of my portfolio demonstrating n8n automation, AI integration, and conversational interface design.*