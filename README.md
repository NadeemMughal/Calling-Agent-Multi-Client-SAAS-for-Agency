# Calling-Agent-Multi-Client-SAAS-for-Agency

## Overview
Scalable SaaS voice agent serving multiple clients (e.g., barbers, salons). Uses client ID routing, knowledge base, and supports multiple CRMs. Demonstrated with barber booking (Fade Masters). Workflows powered by **n8n**.

## Features
- Client-specific routing and branding
- Knowledge base driven responses (no hard-coded prompts)
- Service pricing and duration info
- Availability checks across staff
- Works with Google Calendar and others

## Tech Stack
- **Voice Agent**: Retell AI
- **Routing & Workflows**: n8n + Supabase
- **CRM**: Google Calendar (expandable)

## Setup Instructions
1. Add clients to Supabase with credentials.
2. Configure Retell AI agent with knowledge base.
3. Set client ID routing in n8n.

## Usage
- One agent handles many businesses intelligently

## Demo
Refer to the attached `project_demo.pdf` for multi-client routing, barber booking flow, n8n nodes, and Supabase setup.

## License
MIT
