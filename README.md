# 🏋️‍♂️ FitCoach AI

- **FitCoach AI** is an intelligent automation system that delivers personalized 7-day fitness and meal plans directly to users’ inboxes, powered by AI and driven by user inputs collected through an interactive form.  
- It seamlessly connects a Tally quiz, AI prompt generation, and email automation to provide users with tailored fitness coaching without any manual effort.  
- Perfect for fitness creators, personal trainers, or startups looking to automate user onboarding and plan delivery.

---

## 🚀 Workflow Overview

Carrd → Tally Form → Webhook (n8n) → ConvertKit Email

---

## ✨ Features

- 🧠 AI-generated fitness & meal plans based on user goals, experience, and equipment.
- 📩 Seamless delivery of the plan to the user's inbox using ConvertKit.
- 📝 Custom form embedded in a Carrd landing page via Tally.
- 🔗 No-code automation built with n8n.
- 📊 Lead capture and email list integration for future campaigns.

---

## ⚙️ Tech Stack

| Tool         | Description                                |
|--------------|--------------------------------------------|
| **Carrd**    | Landing page with embedded quiz form       |
| **Tally.so** | Form builder for collecting user input     |
| **n8n**      | Automation tool for handling workflow logic|
| **Groq**     | LLM used to generate plans       |
| **ConvertKit** | Sends plans and stores leads             |
| **Ngrok**    | Tunnels localhost to a public webhook URL  |

---

## 📄 How It Works

1. **User visits the Carrd landing page** and fills out a Tally form.
2. **Form submission triggers a webhook in n8n**, passing the input data.
3. **LangChain uses the AI model** to generate a 7-day workout and meal plan.
4. **ConvertKit sends an email** to the user with their customized plan and adds them to a mailing list.
5. All steps run automatically in real time — no manual intervention required.

---

## 🧪 Local Setup
- Clone the repository:
- git clone https://github.com/yourusername/fitcoach-ai.git
- cd fitcoach-ai
- Start n8n (locally or in Docker)
- Create and embed your Tally form into a Carrd page
- Configure ConvertKit API key and Form ID inside your n8n workflow

---

## 📧 Lead Collection
- Each form submitter is added to your ConvertKit list.
- Collected leads include name and email (useful for campaigns, upselling, etc.)
- Can be managed from ConvertKit dashboard.

---

⭐️ Show Your Support
If you found this helpful or inspiring, please consider giving it a star ⭐ on GitHub!

