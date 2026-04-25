# Teaching Prompts Repository

A free, open library of **1,980 ready-to-use AI prompts** for school education across **four major boards** (Cambridge, ICSE, CBSE, Telangana State) and **all 12 grades**. Paste any prompt into a free AI chatbot (ChatGPT, Claude, Gemini, etc.) and instantly turn it into a subject-specific tutor, trainer, quiz designer, or writing coach.

---

## What's Inside

The repository contains **five different kinds of prompts** for every board and grade. Each one is built for a different person and a different purpose:

| Prompt Type | Who It's For | What It Does |
|---|---|---|
| **Teacher Training** | School teachers | Trains the teacher on *how* to teach a subject — lesson planning, classroom strategies, handling mixed-ability students, assessment design. |
| **Parent Training** | Parents / guardians | Helps parents support their child's learning at home with age-appropriate explanations, activity ideas, and common-mistake guidance. |
| **Student Simulation** | Teachers & parents (practice tool) | The AI *acts like* a real student of that grade — including realistic misconceptions — so adults can rehearse explanations and test teaching approaches. |
| **Diagnostic Quiz Generator** | Teachers & parents | Generates diagnostic quizzes that reveal what a student actually knows, understands, or struggles with — designed to guide learning, not to grade. |
| **Writing Mentor** | Students (with adult oversight) | A patient writing coach that gives guided feedback and practice — it will *never* write the essay for the student. |

### Coverage at a Glance

| Board | Grades | Subjects per grade | Boards-specific framework |
|---|---|---|---|
| **Cambridge** | Grades 1–12 | Cambridge Primary, Lower Secondary, IGCSE, AS & A Level subjects |
| **ICSE** | Classes 1–12 | CISCE / ICSE / ISC subjects |
| **CBSE** | Classes 1–12 | CBSE / NCF-aligned subjects |
| **Telangana State** | Classes 1–12 | SCERT / SSC / TSBIE subjects |

**Total: 1,980 prompts** = 4 boards × 12 grades × (Teacher Training + Parent Training + Student Simulation + Diagnostic Quiz, one per subject) + Writing Mentor (one per grade per board).

---

## Folder Structure

Each board folder contains 12 class/grade folders. Each class/grade folder contains 5 sub-folders — one per prompt type — and each sub-folder holds one `.md` file per subject.

```
teaching-prompts/
├── Cambridge/
│   ├── Grade 1/
│   │   ├── Teacher Training/
│   │   │   ├── English - Grade 1 - Teacher Training Prompt.md
│   │   │   ├── Mathematics - Grade 1 - Teacher Training Prompt.md
│   │   │   └── ...
│   │   ├── Parent Training/
│   │   ├── Student Simulation/
│   │   ├── Diagnostic Quiz Generator/
│   │   └── Writing Mentor/
│   │       └── Writing Mentor - Grade 1 Prompt.md
│   ├── Grade 2/
│   └── ... (up to Grade 12)
├── ICSE/      (Class 1 – Class 12, same structure)
├── CBSE/      (Class 1 – Class 12, same structure)
└── Telangana State/  (Class 1 – Class 12, same structure)
```

> **Note:** Writing Mentor is *cross-curricular* — there is one prompt per grade (not one per subject), since writing skills cut across all subjects.

---

## How to Use a Prompt (3 Steps)

### Step 1 — Pick the right file
1. Open the folder for your **board** (Cambridge / ICSE / CBSE / Telangana State).
2. Open the folder for your **class or grade**.
3. Open the folder for the **prompt type** you want (Teacher Training, Parent Training, etc.).
4. Open the `.md` file for the **subject** you want.

### Step 2 — Copy the entire file
Select all the text in the `.md` file and copy it.

### Step 3 — Paste it into an AI chatbot
Open a free AI tool (see list below), start a new conversation, and paste the entire prompt as your **first message**. The AI will switch into the role described in the prompt and start asking you questions.

That's it — no setup, no installation, no payment.

---

## Free AI Tools That Work With These Prompts

All prompts are designed in plain text and work with any modern chatbot. The free options below all work well:

### 1. ChatGPT — [chat.openai.com](https://chat.openai.com)
Free tier with GPT-4o (limited usage). Sign up with Google/email → New Chat → paste prompt.
**Tip:** For repeat use, save the prompt under *Custom Instructions* (profile menu) so every new chat keeps the trainer persona.

### 2. Claude — [claude.ai](https://claude.ai)
Free tier with Claude Sonnet. Sign up → Start new chat → paste.
**Tip:** Create a *Project*, paste the prompt into Project Instructions, and every chat in that project automatically uses the persona.

### 3. Google Gemini — [gemini.google.com](https://gemini.google.com)
Free with any Google account. Best for follow-ups like "make a worksheet" or "draft a quiz."

### 4. Microsoft Copilot — [copilot.microsoft.com](https://copilot.microsoft.com)
Free with a Microsoft account. Built into Microsoft Edge as a sidebar.

### 5. Perplexity AI — [perplexity.ai](https://www.perplexity.ai)
Free tier, no sign-up needed for basic use. Useful when you want the AI to also pull syllabus updates from the web.

### 6. HuggingChat — [huggingface.co/chat](https://huggingface.co/chat)
Completely free and open-source. A reliable fallback when other services are busy.

### 7. Poe — [poe.com](https://poe.com)
Free tier that lets you try the *same prompt* across ChatGPT, Claude, Gemini side-by-side.

---

## Picking the Right Prompt for Your Goal

| If you want to… | Use this prompt type |
|---|---|
| Learn how to teach a topic better | **Teacher Training** |
| Help your child with homework or revision at home | **Parent Training** |
| Rehearse an explanation or anticipate student questions | **Student Simulation** |
| Find out what a student actually knows or struggles with | **Diagnostic Quiz Generator** |
| Help a student improve their writing without writing it for them | **Writing Mentor** |

---

## Tips for Teachers

- **Be specific when the AI asks about your context** — your experience level, class size, and student range. The more detail, the better the advice.
- **Ask for differentiated versions:** *"Give me three versions of this activity — easy, medium, and hard."*
- **Request ready-made resources:** lesson plans, rubrics, warm-ups, exit tickets, exam papers with marking schemes.
- **Loop back:** after trying a strategy in class, tell the AI what worked and what didn't, and it will adjust.

## Tips for Parents

- **Start with one subject** your child finds difficult.
- **Ask in your own language:** *"Please explain in Telugu / Hindi / simple English."* Most chatbots are multilingual.
- **Ask for activities, not lectures:** *"Give me a 15-minute fun activity to teach fractions to my Class 4 child."*
- **Use the Diagnostic Quiz prompt first** to see where your child stands before deciding what to focus on.

---

## Frequently Asked Questions

**Q: Do I need to pay anything?**
No. The prompts are free, and every AI tool listed above has a free tier that works.

**Q: Can I use these on my phone?**
Yes. ChatGPT, Claude, Gemini, and Copilot all have Android and iOS apps. The web versions also work in any mobile browser.

**Q: The AI's response got cut off — what now?**
Just type **"please continue"** and it will pick up where it left off.

**Q: Can I edit the prompts?**
Yes — they're starting templates. Add your own context (school name, syllabus chapter, language preference) at the top before pasting.

**Q: Which AI tool is best?**
ChatGPT and Claude tend to give the most detailed pedagogical responses. Gemini is great if you're already in the Google ecosystem. Try a couple and stick with what feels right.

**Q: I teach multiple subjects — should I combine prompts?**
No. Start a *separate chat* for each subject/grade combination. Mixing prompts confuses the AI and dilutes accuracy.

**Q: Can the Student Simulation actually tell me what my students will get wrong?**
The simulated student is built to display realistic, age-appropriate misconceptions for the board and grade — so yes, it's a good rehearsal tool, but real students will always surprise you in their own way.

**Q: Will the Writing Mentor write my child's essay for them?**
No — it is explicitly designed to refuse and to coach instead. That's the point.

---

## Quick Start (60 Seconds)

1. Go to [chat.openai.com](https://chat.openai.com) or [claude.ai](https://claude.ai).
2. Open the right `.md` file, e.g.
   `CBSE/Class 5/Teacher Training/Mathematics - Class 5 - Teacher Training Prompt.md`
3. Copy everything inside it.
4. Paste into the chatbot and press Send.
5. Answer the AI's intro questions.
6. Start your session.

---

*Built to empower teachers, parents, and students across Cambridge, ICSE, CBSE, and Telangana State curricula. Prompts are free to use, share, and adapt.*
