# WhatsApp AI Agent Automation Workflow

This project demonstrates an AI-powered WhatsApp automation workflow using OpenAI Chat Models and WhatsApp Business Cloud. The workflow is designed to process incoming WhatsApp messages, apply conditional logic, and generate intelligent responses using AI.

## 📊 Workflow Overview

**Tools Used:**

- **WhatsApp Trigger:** Listens for incoming WhatsApp messages.
- **Conditional Block (If):** Determines the next step based on message content or logic.
- **AI Agent:** Processes the message with AI capabilities using OpenAI's Chat Model and Simple Memory.
- **WhatsApp Business Cloud:** Sends automated responses to users on WhatsApp.

---

## ⚙️ Workflow Breakdown


WhatsApp Trigger → If Condition:
                   ├─ true → AI Agent → WhatsApp Business Cloud (Send Message)
                   └─ false → (Can be expanded for alternative logic)

---
## Components

*   **WhatsApp Trigger**: Initiates the workflow when a new message is received via WhatsApp.
*   **If Block**: Checks message content or other logic to decide the flow.
*   **AI Agent**:
    *   Uses OpenAI Chat Model to generate intelligent responses.
    *   Simple Memory stores context or user-specific data.
*   **WhatsApp Business Cloud**: Sends the AI-generated response back to the user.

## 💡 Key Features

*   AI-driven WhatsApp response system.
*   OpenAI's Chat Model integration for smart replies.
*   Simple Memory for session-based context.
*   Expandable conditional logic based on requirements.

## 🚀 How to Execute

1.  Deploy the workflow in your automation platform.
2.  Configure your WhatsApp Business Cloud credentials.
3.  Integrate your OpenAI API key for AI model access.
4.  Start the workflow and test by sending a message to your WhatsApp Business number.
5.  Click `Execute Workflow` to activate automation.

## 🛠️ Requirements

*   WhatsApp Business API access.
*   OpenAI API Key.
*   Automation Platform supporting visual workflows (as shown in the image).

## 📷 Screenshot
![Workflow Screenshot](./path/to/Screenshot.png)
