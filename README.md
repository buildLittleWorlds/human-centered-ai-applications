# CAH 30503: Human-Centered AI Applications

**Lindenwood University — Curriculum for Applied Humanities**

An 8-week course where non-CS undergraduates go from a problem they care about to a live deployed AI application. Students direct AI to build, don't write code from scratch. The organizing framework is PDER (Plan, Direct, Examine, Record).

**Prerequisite**: CAH 20501 (Design Thinking)

---

## Weekly Schedule

| Week | Topic | Notebook | What Happens |
|------|-------|----------|-------------|
| 1 | **What Is an AI System?** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-01.ipynb) | Use Claude + Google AI Studio, explore HF Spaces, run first pipeline, create CLAUDE.md |
| 2 | **User Research and Problem Validation** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-02.ipynb) | CLEAR prompting framework, user interviews, assumptions vs. reality, select project problem |
| 3 | **Technical Prototype Strategy** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-03.ipynb) | Browse HF Hub, run pipelines, compare models, read model cards, define MVP, PDER named |
| 4 | **First Build** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-04.ipynb) | Direct Claude Code to build app, wrap in gr.Interface, first user test, 6-question examination |
| 5 | **Deploy** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-05.ipynb) | Upgrade to gr.Blocks, three-file pattern, deploy to HF Spaces, get a public URL |
| 6 | **Real Users and Domain Fit** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/buildLittleWorlds/human-centered-ai-applications/blob/main/week-06.ipynb) | User test protocol, accountability analysis, domain fit, prioritized fix list |
| 7 | **Responsible AI Hardening** | *Coming soon* | Failure catalog, Should-We-Build-This, safeguards, capability statement, deploy v2 |
| 8 | **Ship and Reflect** | *Coming soon* | Final polish, Product Brief, presentations, reflection |

---

## Tools

| Tool | Cost | Used In |
|------|------|---------|
| [Claude](https://claude.ai) | $20/month (Pro) | Weeks 1-8 |
| [Google AI Studio](https://aistudio.google.com) | Free | Weeks 1, 3 |
| [Hugging Face Spaces](https://huggingface.co/spaces) | Free | Weeks 5-8 |
| [Google Colab](https://colab.research.google.com) | Free | Weeks 1-6 (notebooks above) |

---

## The PDER Loop

Every week runs the same loop at increasing sophistication:

```
    PLAN → DIRECT → EXAMINE → RECORD
     ↑                          │
     └──────────────────────────┘
```

- **Plan**: Decide what to build, investigate, or test
- **Direct**: Hand the plan to AI and supervise execution
- **Examine**: Assess what was built (functional, usable, accountable)
- **Record**: Write down what you learned so the next cycle starts smarter

Students maintain a `CLAUDE.md` file from Week 1 — a running record of decisions, observations, and learning that compounds across the course.

---

## Distributed Cognitive Systems

Each week poses a DCS question that students answer in their CLAUDE.md:

1. What kind of system is this?
2. What cognitive work gets outsourced to AI in my proposed solution?
3. What knowledge is encoded in the models I chose?
4. Who directs this system, and what do they need to know?
5. What connects this system to its users?
6. Where does accountability live when this system is wrong?
7. What does responsible participation look like for this system?
8. What did I learn about being a responsible participant in cognitive systems?
