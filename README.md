# bubble-chat-messenger-app
A real-time messaging application built on Bubble.io with 1-on-1 conversations, group chats, file attachments, and user-level privacy controls

---

## Core Features

| Feature                     | Description |
|-----------------------------|-------------|
| 🧑‍💻 **User Profile Setup**   | Upload photo, set bio, edit name and email |
| 🔐 **Secure Login**         | Bubble’s built-in user authentication |
| 💬 **1-on-1 Messaging**     | Start private conversations with other users |
| 👥 **Group Chats**          | Create groups, send messages, view participants, remove participants, delete groups |
| 📎 **File Sharing**         | Attach and send files in any conversation or group |

---

## Product Link

🔗 [Click to view demo app](https://relayhub.bubbleapps.io/version-test/signup_login?debug_mode=true&View=Signup)

Create an account or use this test account to explore the demo:

- Email: olivia.hart@skyline.net
- Password: G7r!Kzq2L#t5

⚠️ *Data may reset periodically.*

---

## Project Features

**User Authentication & Profile Setup**
- Signup/Login page with built-in Bubble authentication
- Redirects new users to profile creation page after signup
- Test users land on pre-filled profile page (can still edit details)
- Editable fields: Profile picture, name, email address and bio
<br>

**Conversation Functionality**
- Users can start direct conversations with other registered users
- Each conversation is private and only visible to the two participants
- Chat includes messages, timestamp, and file attachments
- Conversations auto-update via Bubble workflows
<br>

**Group Chat Functionality**
- Users can create custom groups and name them
- Only the group creator can add/remove members from the Participants Tab or delete the group 
- Group chat is accessible only to current participants
- All participants can send messages and files within the group
<br>

**Privacy & Access Rules**
- Users can only view conversations or groups that they are a part of
- Participants of groups other than group creator can only view other participants but cannot add/delete them

---

## 📸 Screenshots 

- `login-page.png` – Login interface  
- `profile-page.png` – Profile setup/edit page  
- `chat-section.png` – 1-on-1 and group chat interface  
- `participants-tab.png` – Group participants view  

---

## 🧰 Tech Stack

- **Frontend/Backend:** [Bubble.io](https://bubble.io)
- **Database:** Bubble built-in relational data model
- **File Uploads:** Bubble FileUploader
- **Privacy Controls:** Bubble’s privacy rule engine with condition-based access

---

## 📂 Repository Structure

bubble-chat-app-user-journey-access-control/
│
├── README.md
├── assets/
│ ├── login-page.png
│ ├── profile-page.png
│ ├── chat-section.png
│ └── participants-tab.png
├── workflows/
│ ├── new-user-journey.md
│ ├── test-user-journey.md
│ ├── group-management-flow.md
│ └── privacy-rules-breakdown.md
└── LICENSE (optional)

yaml
Copy
Edit

---

## 📌 Notes

- This project is part of a curated **Bubble Developer Portfolio** built for showcasing real-world product features with clean UI, workflow management, and scalable logic.
- Designed to help recruiters and clients quickly assess app-building and access-control skills in the no-code environment.

---

## 🧠 Creator

**Nachiket Karhade**  
No-Code Developer | Bubble Expert | Automation Specialist  
🔗 [GitHub](https://github.com/NachiketK43) · 💼 [LinkedIn](https://linkedin.com/in/nachiket-karhade) · 📬 [Contact](mailto:your-email@example.com)

---
