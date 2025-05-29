# 🛰️ AI-Powered Drone Shot List Generator

This is an automated solution I built in 2 days that generates **custom drone shot lists** for drone pilots and construction developers based on project details submitted through a form.

It's designed to **save time, improve client communication**, and help drone pilots deliver faster and more professionally.

---

## 🧠 What It Does

1. User submits project details on the embedded form (via Carrd + Tally).
2. Zapier sends that data to OpenAI to generate a unique drone shot list.
3. The generated list is emailed back to the user automatically.

---

## 🔗 Tools Used

- **Tally** – Smart form embedded in the landing page
- **Carrd** – Clean, responsive landing page
- **Zapier** – Connects Tally to OpenAI and Email
- **OpenAI API** – Generates the drone shot list
- **Loom** – Recorded a walkthrough of the entire solution

---

## 🚀 Try It Live

- 👉 [Landing Page with Embedded Form (Carrd)](https://smoovevisuals.carrd.co/)  
  Submit a project to instantly receive a custom drone shot list via email.

- 🎥 [Watch the Full Workflow Demo (Loom)](https://tinyurl.com/4zzthmne)

---

## 🧾 Prompt Template

This is the exact prompt used inside the Zapier → OpenAI step:

> Based on the following details, create a detailed drone shot list for a drone pilot to follow. Include a variety of angles, movement styles, and recommendations.  
>  
> **Project Type:** {{Project Type}}  
> **Style/Aesthetic:** {{Style}}  
> **Location Type:** {{Location}}  
> **Goal of the Video:** {{Goal}}  
> **Timeline:** {{Timeline}}

---

## 🖼️ Screenshots

| Tally Form Embedded | Zapier Automation | Email Result | Landing Page |
|---------------------|-------------------|--------------|--------------|
| ![Tally Form](!
 | ![Zapier Workflow](./screenshots/zapier-workflow.png) | ![Email](./screenshots/shotlist-email.png) | ![Carrd Site](./screenshots/carrd-site.png) |

---

## 📁 Repo Contents

- `README.md` – This file
- `prompt-template.txt` – Prompt used in OpenAI
- `zapier-workflow.md` – Step-by-step instructions
- `screenshots/` – Images of the workflow and output

---

## 🎯 Why I Built This

I noticed a major pain point for drone pilots: **they waste time figuring out what shots to take** or trying to guess what their clients want.

So I built a solution that:
- Speeds up pre-production
- Helps pilots look more professional
- Is easy for clients to use
- Can be customized, scaled, and monetized

I’m focused on creating practical, AI-powered tools that solve real business problems — fast.

---

## 👋 About Me

Hi! I’m Parker Wilson — an AI solutions builder, drone consultant, and creative problem-solver. I’m currently seeking opportunities at forward-thinking companies where I can use my AI, automation, and product mindset to build tools that improve workflows and customer experiences.

Connect with me on [LinkedIn](https://www.linkedin.com/in/parkerdwilson/)



