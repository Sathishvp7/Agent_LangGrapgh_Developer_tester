An autonomous Agentic AI system that simulates a real-world software development lifecycle using multiple intelligent agents. The system includes a Developer Agent, Tester Agent, and an automated Feedback Loop that continuously improves the generated software until it meets quality standards.

This project demonstrates the core principles of Agentic AI, including autonomous decision-making, iterative improvement, and multi-agent collaboration.

![Uploading image.png…]()


Features

👨‍💻 Developer Agent

Automatically writes software using Python

Generates functions based on task requirements

Improves code based on tester feedback

🧪 Tester Agent

Evaluates generated code

Runs test cases

Detects errors, bugs, and logical issues

Provides structured feedback

🔁 Autonomous Feedback Loop

Tester feedback is sent back to Developer Agent

Developer Agent fixes issues automatically

Process continues until code passes all tests

🧠 Agentic AI Architecture

Fully autonomous agent workflow

Simulates real-world software development lifecycle

          ┌────────────────────┐
          │    User Request    │
          └─────────┬──────────┘
                    │
                    ▼
          ┌────────────────────┐
          │   Developer Agent  │
          │  (Writes Code)     │
          └─────────┬──────────┘
                    │
                    ▼
          ┌────────────────────┐
          │    Tester Agent    │
          │  (Evaluates Code)  │
          └─────────┬──────────┘
                    │
           Pass     │      Fail
        ┌───────────┘────────────┐
        ▼                        ▼
  ┌──────────────┐       ┌──────────────┐
  │ Final Output │       │ Feedback to  │
  │              │       │ Developer    │
  └──────────────┘       └──────┬───────┘
                                │
                                └──── Loop until correct
