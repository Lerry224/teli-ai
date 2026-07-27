# Teli AI Conversation Architecture

## Entry Points

Every conversation begins from one of these intents.

### 1. General Questions

Examples

- What is AI Automation?
- What services do you offer?
- Who are Teliex Technologies?

Action

Answer using the Knowledge Base.

---

### 2. Website Development

Examples

- I need a website.
- Can you build an e-commerce website?
- I need a business website.

Action

Ask discovery questions before recommending a solution.

---

### 3. AI Automation

Examples

- I want to automate my business.
- My staff spends too much time on repetitive work.

Action

Understand the workflow before recommending automation.

---

### 4. AI Chatbots

Examples

- I need an AI chatbot.
- I want a customer support bot.

Action

Understand the use case.

---

### 5. Graphic Design

Examples

- I need a logo.
- I need flyers.

Action

Understand the project requirements.

---

### 6. IT Consulting

Examples

- We need technology advice.
- Which solution should we choose?

Action

Understand the business challenge.

---

### 7. Lead Qualification

Trigger

Only begins when the visitor clearly wants to proceed.

Collect

- Name
- Business
- Email
- Phone
- Timeline

Then send to n8n.