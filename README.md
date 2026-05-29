<div align="left">

#  PathForge AI

### Transforming Learning Roadmaps into Structured Learning Journeys

An AI-powered learning coach that converts static roadmaps into personalized study plans, schedules learning sessions, generates notes, conducts assessments, tracks progress, and keeps learners accountable.

<br>

![n8n](https://img.shields.io/badge/Built%20With-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![AI](https://img.shields.io/badge/AI-Powered-412991?style=for-the-badge)
![Google Workspace](https://img.shields.io/badge/Google-Workspace-4285F4?style=for-the-badge&logo=google)
![Status](https://img.shields.io/badge/Status-Active-2EA043?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## 🔹 Overview

Learning roadmaps are easy to collect but difficult to follow.

Most learners struggle with:

- Planning study schedules
- Staying consistent
- Tracking progress
- Creating notes
- Assessing knowledge
- Maintaining accountability

**PathForge AI** acts as a personal AI learning coach that transforms a roadmap into a structured execution plan and guides learners throughout their journey.

Instead of simply consuming content, learners receive:

- Personalized study schedules
- AI-generated notes
- Automated assessments
- Performance analysis
- Progress tracking
- Reminder notifications

---

## 🔹 Key Features

### Intelligent Roadmap Analysis

- Retrieve learning roadmap from Gmail
- Analyze phases and topics
- Identify dependencies
- Build structured learning paths

### Smart Study Scheduling

- Calendar-aware planning
- Availability checking
- Study session generation
- Event management and updates

### AI-Generated Notes

- Topic summaries
- Learning objectives
- Detailed explanations
- Practical examples
- Exercises and challenges
- Recommended resources

### Assessment Engine

- Automatic test generation
- MCQ questions
- Short-answer questions
- Scenario-based questions
- Knowledge validation

### Performance Tracking

- Automated grading
- Feedback generation
- Weak area detection
- Improvement recommendations
- Learning analytics

### Email Notifications

- Study reminders
- Session alerts
- Assessment reminders
- Progress notifications

---

## 🔹 Architecture

```text
                    ┌─────────────┐
                    │    User     │
                    └──────┬──────┘
                           │
                           ▼
                 ┌──────────────────┐
                 │  PathForge AI    │
                 │   Chat Agent     │
                 └───────┬──────────┘
                         │
         ┌───────────────┼───────────────┐
         │               │               │
         ▼               ▼               ▼

 ┌─────────────┐  ┌─────────────┐  ┌─────────────┐
 │    Gmail    │  │  Calendar   │  │ Google Docs │
 ├─────────────┤  ├─────────────┤  ├─────────────┤
 │ Roadmaps    │  │ Scheduling  │  │ Notes       │
 │ Reminders   │  │ Events      │  │ Tests       │
 └─────────────┘  └─────────────┘  │ Feedback    │
                                   └─────────────┘
                         │
                         ▼
              ┌────────────────────┐
              │ Learning Engine    │
              ├────────────────────┤
              │ Study Planning     │
              │ Note Generation    │
              │ Assessments        │
              │ Progress Tracking  │
              └────────────────────┘
```

---

## 🔹 Learning Workflow

### Step 1 - Roadmap Retrieval

```text
User Email
      │
      ▼
Retrieve Roadmap
      │
      ▼
Analyze Topics & Phases
```

### Step 2 - Planning

```text
Collect Preferences
      │
      ▼
Check Availability
      │
      ▼
Generate Study Plan
```

### Step 3 - Scheduling

```text
User Confirmation
      │
      ▼
Create Calendar Events
      │
      ▼
Generate Notes
```

### Step 4 - Learning

```text
Study Session
      │
      ▼
Notes & Exercises
      │
      ▼
Progress Tracking
```

### Step 5 - Assessment

```text
Generate Test
      │
      ▼
User Submission
      │
      ▼
AI Evaluation
      │
      ▼
Feedback & Recommendations
```

---

## 🔹 Technology Stack

| Layer | Technology |
|---------|------------|
| Workflow Automation | n8n |
| AI Models | OpenAI / Gemini / Groq |
| Email Integration | Gmail API |
| Scheduling | Google Calendar API |
| Documentation | Google Docs API |
| Notifications | Gmail API |
| Agent Memory | n8n Memory |
| Storage | Google Workspace |

---

## 🔹 Repository Structure

```text
PathForge-AI/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── workflows/
│   ├── pathforge-main-workflow.json
│   ├── gmail-tools.json
│   ├── calendar-tools.json
│   └── docs-tools.json
│
├── prompts/
│   ├── system-prompt.md
│   └── tool-routing-rules.md
│
├── docs/
│   ├── setup-guide.md
│   ├── architecture.png
│   ├── workflow-diagram.png
│   └── screenshots/
│
└── examples/
    ├── sample-roadmap.pdf
    ├── generated-notes.md
    └── generated-assessment.md

```

---

## 🔹 Example User Journey

```text
User Provides Email
          │
          ▼
Roadmap Retrieved
          │
          ▼
AI Analyzes Learning Path
          │
          ▼
Study Plan Generated
          │
          ▼
Calendar Sessions Created
          │
          ▼
Notes Generated
          │
          ▼
Assessments Generated
          │
          ▼
Performance Evaluated
          │
          ▼
Progress Continuously Tracked
```

---

## 🔹 Screenshots

### Chat Interface

> Add screenshot here

```text
docs/screenshots/chat-interface.png
```

### Study Schedule Generation

> Add screenshot here

```text
docs/screenshots/schedule-generation.png
```

### Notes Generation

> Add screenshot here

```text
docs/screenshots/notes-generation.png
```

### Assessment Creation

> Add screenshot here

```text
docs/screenshots/assessment-generation.png
```

---

## 🔹 Local Setup

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/PathForge-AI.git
```

### Navigate

```bash
cd PathForge-AI
```

### Import Workflow

1. Open n8n
2. Import workflow JSON
3. Configure credentials
4. Configure AI model
5. Activate workflow

---

## 🔹 Future Roadmap

### Phase 1

- Multi-user support
- Enhanced memory
- Better scheduling logic

### Phase 2

- User authentication
- Personal Google Calendar integration
- Learning analytics dashboard
- Progress visualization

### Phase 3

- Adaptive learning engine
- Spaced repetition system
- Knowledge graph generation
- Personalized learning recommendations

### Phase 4

- Mobile application
- LMS integrations
- Team learning support
- Enterprise deployment

---

## 🔹 Why PathForge AI?

Most AI learning tools stop after generating content.

PathForge AI focuses on the entire learning lifecycle:

- Planning
- Scheduling
- Learning
- Testing
- Evaluation
- Progress Tracking

This makes it closer to a true AI learning coach rather than a simple content generator.

---

## 🔹 Contributing

Contributions, feature suggestions, and workflow improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 🔹 Author

**Aryan**

Data Science • AI • Automation • Learning Systems

---

<div align="center">

### PathForge AI

Building disciplined learning systems powered by AI.

</div>
