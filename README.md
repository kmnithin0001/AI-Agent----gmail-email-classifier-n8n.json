
# AI Agent -- Gmail Email Classifier – n8n Workflow

This n8n workflow automatically classifies incoming Gmail emails into the following categories using AI (Google Gemini):

- ✅ High Priority  
- 💼 Customer Support  
- 🛍️ Promotions  
- 💰 Finance/Billing  

## 🚀 How it Works

1. **Trigger**: The workflow uses a Gmail Trigger to check for new emails every minute.
2. **AI Classification**: The content is passed to a `Text Classifier` node powered by Google Gemini.
3. **Labeling**: Based on classification, the email is automatically labeled using Gmail nodes.

## 🧠 Categories & Keywords

| Category         | Keywords                                                                 |
|------------------|--------------------------------------------------------------------------|
| High Priority    | urgent, ASAP, immediate, deadline, action required, high priority        |
| Customer Support | request, inquiry, support, question, follow-up, feedback                |
| Promotions       | offer, discount, newsletter, promotion, free, campaign, event           |
| Finance/Billing  | invoice, payment, receipt, refund, GST, transaction, credit, tax        |

## 📦 File Structure

