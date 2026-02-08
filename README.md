# n8n YouTube Uploader 🎥🚀

An automated workflow built with **n8n** to upload videos to **YouTube** with minimal manual effort.  
This project is designed to help creators and developers automate repetitive YouTube upload tasks using a self-hosted or Docker-based n8n setup.

<img width="1197" height="496" alt="Screenshot 2026-02-07 at 8 12 28 PM" src="https://github.com/user-attachments/assets/cb92e23d-26ca-4fab-a0c0-fca4d1e6f794" />


## ✨ What this project does

This project allows you to:

- Automatically upload videos to YouTube
- Use n8n workflows instead of manual uploads
- Manage credentials and automation in a clean, reproducible way
- Run everything locally using Docker
- Avoid committing large media files to GitHub

Typical use cases:
- Automating YouTube channels
- Scheduling uploads
- Integrating video uploads with other tools (Google Drive, S3, APIs, etc.)
- Learning n8n automation with a real-world project



## 🧠 High-level architecture

```text
Video Source (Local / Drive / API)
        ↓
       n8n
        ↓
YouTube Data API
        ↓
 Video Uploaded
```

## Prereqisites

Make sure you have the following installed:

- Docker
- Docker Compose
- Git
- A Google account with YouTube access
- Basic understanding of n8n

## Getting Started

1. Clone the Repository
2. Create environment file
3. Start n8n using Docker : http://localhost:5678
4. Import workflow into n8n

## YouTube API setup

To upload videos, you must configure the YouTube Data API:
1.	Create a project in Google Cloud Console
2.	Enable YouTube Data API v3
3.	Create OAuth credentials
4.	Add those credentials inside n8n


