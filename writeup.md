# Week 1 - Setup Writeup

**Which coding agent you set up and the version:**
I set up Google Antigravity (backed by the free Gemini student plan) to utilize its full agentic capabilities.

**A screenshot of your agent completing a task:**
<img width="1917" height="1137" alt="image" src="https://github.com/user-attachments/assets/87ce1475-f9f3-4b06-998e-dd4696c4e018" />

<img width="1077" height="971" alt="image" src="https://github.com/user-attachments/assets/0e2de070-e204-4d77-a95a-edf8f8cedd54" />

<img width="1472" height="818" alt="image" src="https://github.com/user-attachments/assets/768b5fa1-cd18-476e-8810-1efdbb8e102d" />

**The exact prompt(s) you gave it, and any corrections you had to make by hand:**
*Prompt:* "Create an interactive Python CLI program in `agent_scaffold.py`. It should use the built-in `input()` function to interactively prompt the user for an Agent Name, Role, Goal, and Backstory. Then, it should generate a properly formatted Python file containing a CrewAI-style agent setup using those inputs. Include basic error handling for empty inputs."

**Corrections:**
The agent's core logic worked perfectly on the first try. My only manual corrections were minor cleanups: I removed the sys module dependency by replacing sys.exit() with Python's built-in raise SystemExit(), and I tweaked some of the print() statements (adding a few \n characters) to make the terminal output look cleaner and easier to read.

**What you learned:**
What surprised me most about working through an agent was how it completely eliminated the friction of writing boilerplate code.Instead of manually typing out file creation logic and string formatting for every new agent's role and backstory,I could just describe the system's goal.It fundamentally shifts the developer's mindset from typing lines of syntax to directing system behavior and architecture.
