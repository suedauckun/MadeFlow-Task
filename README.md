Workflow Overview

This n8n workflow automates the process of receiving, classifying, and summarizing incoming emails using AI.

 How It Works

Email Trigger → The workflow starts when a new email is received.

AI Text Classification → The email content is analyzed using OpenAI Text Classifier, and the message is categorized based on predefined labels (e.g., Support, Spam etc).

Store Results → The classification result and metadata are stored in the n8n Beta Database for tracking and analysis.

AI Summarization → The email body is summarized to create a concise overview of the content.

Forward Summary Email → The summary and classification label are automatically sent to a fixed recipient (e.g., a manager or support inbox).
