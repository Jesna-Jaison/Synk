#Synk 🎯

#Basic Details

##Team Name: Team Synksters

##Team Members:

Member 1: Jesna Jaison –Vidya Academy of Science and Technology

Member 2:Paviya T V – Vidya Academy of Science and Technology

#Hosted Project Link: https://synk-project.com

#Project Description

Synk is a social learning platform that connects students with similar skills, interests, and goals. It allows users to discover study partners, join groups, participate in hackathons, and collaborate on projects seamlessly.

#Problem Statement

Students often struggle to find compatible study partners or peers who share similar skills and learning goals, which affects collaboration, learning efficiency, and engagement.

#Solution

Synk solves this by providing an intelligent matchmaking system that pairs students based on skills, interests, and learning goals. Users can swipe to discover matches, chat, and join collaborative groups or projects to enhance learning and productivity.

#Technical Details
##Technologies/Components Used

For Software:

Languages used: JavaScript, HTML, CSS

Frameworks used: React.js

Libraries used: Firebase(backend)

Tools used: VS Code, Git

For Hardware:

Not applicable (web-based project)

#Features

Feature 1: Swipe-based discovery to find compatible study partners.

Feature 2: Join and create study groups, hackathons, and collaborative projects.

Feature 3: Real-time chat and notifications for matches and group updates.

Feature 4: Personalized dashboard showing your matches, groups, and activities.

#Implementation

##For Software:

##Installation
git clone https://github.com/yourrepo/synk.git
cd synk
npm install
##Run
npm start

#Project Documentation

##Screenshots

Home Page: Clean hero section, swipe feature, and dashboard links.

Swipe Page: Discover matches and view compatibility tags.

Dashboard: Profile, groups, and project actions.

(You can add actual screenshots when available.)

##Diagrams

-System Architecture

Components: Frontend (React), Backend (Firebase Auth & Firestore), Matchmaking Engine, Notifications System.
Data Flow:

User interacts with frontend → API requests → Backend handles auth, data, and matchmaking → Updates shown in frontend → Notifications sent as needed.

-Application Workflow

Sign up / login

Complete profile

Swipe to find matches

Start chat & connect

Join groups & projects

(Use diagrams generated from previous AI image for visual representation.)

#Additional Documentation

API Documentation (Web Backend)

Base URL: https://api.synk-project.com

GET /matches

Description: Get list of compatible matches

Parameters: userId (string)

Response:

{
  "status": "success",
  "matches": []
}

POST /chat

Description: Send message to a matched user

Request Body:

{
  "from": "userId",
  "to": "matchId",
  "message": "Hello!"
}

Response:

{
  "status": "success",
  "message": "Message sent"
}
AI Tools Used (Optional)

Tool: ChatGPT

Purpose: Generate project documentation, workflow diagrams, and code snippets

Key Prompts: “Generate project documentation for Synk app”, “Explain swipe-based matching system”

Human Contributions: UI design, backend development, testing, deployment

Team Contributions

Paviya: Frontend development, UI/UX design, documentation

Partner Name: Backend development, Firebase integration, testing

License

This project is licensed under the MIT License – permissive, widely used.
