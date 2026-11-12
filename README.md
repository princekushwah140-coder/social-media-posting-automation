# 🚀 Social Media Posting Automation | n8n

An AI-powered social media workflow automation project built using **n8n, Google Gemini, Google Sheets, Facebook Graph API, and YouTube integration**.

This project explores how AI and workflow automation can simplify repetitive social media publishing operations through scheduled execution, API integrations, video processing, and automated data management.

## 📌 Project Overview

Managing social media content across multiple platforms involves repetitive tasks such as retrieving content, processing publishing information, uploading videos, and maintaining publishing records.

This project aims to streamline these operations through an automated n8n workflow.

The workflow connects multiple services into a single automation pipeline, reducing manual intervention and demonstrating practical API integration.

## ⚙️ Workflow Architecture

The workflow follows this sequence:

1. **Schedule Trigger**
   - Starts the automation at a predefined time.

2. **Google Sheets Integration**
   - Retrieves content and publishing information from Google Sheets.

3. **AI Agent**
   - Uses Google Gemini for AI-powered processing and workflow assistance.

4. **Facebook Graph API**
   - Handles configured social media publishing operations.

5. **Wait Node**
   - Controls the timing between workflow operations.

6. **Video Download**
   - Retrieves video content for the subsequent publishing process.

7. **YouTube Upload**
   - Uploads video content through the YouTube integration.

8. **Google Sheets Update**
   - Updates spreadsheet records to maintain publishing information and workflow status.

## 🏗️ Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow orchestration |
| Google Gemini | AI-powered processing |
| Google Sheets | Content and data management |
| Facebook Graph API | Social media integration |
| YouTube API | Video publishing |
| HTTP Requests | API communication |

## 📸 Workflow Screenshots

Add your actual screenshots inside the `screenshots` folder.

### Complete Workflow

![Complete n8n Workflow](screenshots/workflow-overview.png)

### AI Agent Integration

![AI Agent](screenshots/ai-agent.png)

### Google Sheets Integration

![Google Sheets](screenshots/google-sheets.png)

### YouTube Integration

![YouTube Upload](screenshots/youtube-upload.png)

### Workflow Execution

![Workflow Execution](screenshots/execution.png)

## 📂 Project Structure

```text
social-media-posting-automation/
│
├── README.md
│
├── workflow/
│   └── social-media-posting-automation.json
│
└── screenshots/
    ├── workflow-overview.png
    ├── ai-agent.png
    ├── google-sheets.png
    ├── youtube-upload.png
    └── execution.png
```

## 🛠️ Setup and Installation

### Prerequisites

- An installed n8n instance (self-hosted or cloud).
- Google account.
- Google Gemini API access.
- Configured Google Sheets integration.
- Facebook Developer application and appropriate Graph API permissions.
- Configured YouTube API integration.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/social-media-posting-automation.git
```

### Step 2: Open n8n

Open your local or cloud n8n instance.

### Step 3: Import the Workflow

1. Open n8n.
2. Navigate to Workflows.
3. Select Import from File.
4. Choose the workflow JSON file.

### Step 4: Configure Credentials

Configure the required credentials in n8n:

- Google Sheets OAuth2.
- Google Gemini API.
- Facebook Graph API.
- YouTube OAuth2.

### Step 5: Configure Workflow Settings

Update the workflow with your own:

- Google Spreadsheet ID.
- Sheet name and column structure.
- Publishing schedule.
- API credentials and permissions.
- Video source and publishing settings.

### Step 6: Test and Activate

Execute the workflow manually to verify each integration.

Once tested, configure the schedule and activate the workflow.

## 🔐 Security

- Never upload API keys or access tokens.
- Do not commit OAuth credentials.
- Keep private spreadsheet information out of screenshots.
- Use n8n's credential management system.
- Review exported workflow JSON files before publishing.

## 🎯 Key Learning Outcomes

Through this project, I explored:

- Multi-step workflow automation.
- AI Agent integration with Google Gemini.
- REST API integration.
- OAuth authentication and API credentials.
- Scheduled workflow execution.
- Conditional workflow sequencing.
- Video processing and publishing integrations.
- Automated spreadsheet updates.

## 🚀 Future Improvements

- Add more social media platform integrations.
- Improve automated publishing status tracking.
- Implement error handling and retry mechanisms.
- Add analytics and performance reporting.
- Build a centralized content management system.
- Improve AI-driven content processing.

## 👨‍💻 About the Developer

**Prince Kushwaha**

B.Tech Electronics and Communication Engineering Student | Aspiring Software & Backend Developer | AI Automation Enthusiast

Interested in building practical solutions using software development, APIs, AI, and workflow automation.

- GitHub: https://github.com/princekushwah140-coder
- LinkedIn: https://www.linkedin.com/in/prince-kushwaha-02ab1a392/

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with n8n, AI, and a passion for automation.**
