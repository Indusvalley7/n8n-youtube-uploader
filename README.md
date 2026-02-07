# n8n: Google Drive Inbox → Random Upload to YouTube (No Repeats)

This project is a self-hosted n8n workflow that:
- Lists MP4 files in a Google Drive Inbox folder
- Picks one file at random
- Downloads it as binary
- Uploads it to YouTube
- Moves the file to an Uploaded folder so it won’t repeat

## Run locally

### 1) Create env file
Copy the example env file:
```bash
cp .env.example .env