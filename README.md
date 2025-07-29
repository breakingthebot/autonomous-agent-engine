

# Protocol v12: An Autonomous AI Orchestration Engine

![Project Status](https://img.shields.io/badge/status-showcase-green)
![License](https://img.shields.io/github/license/breakingthebot/autonomous-agent-engine)

A demonstration of a multi-agent AI system that can autonomously decompose a complex goal and delegate tasks to a team of specialized AI agents.

---

## How It Works: An AI's Self-Explanation

The following 6-part explanation was generated entirely by the Protocol v12 system itself. It was given a single prompt: "Create a 6-turn explanation of Protocol v12... for a casual GitHub user." The screenshots below show the instructions given to each AI agent and its intelligent output.

### Turn 1: The AI Team Captain

> Imagine you have a big, complex project. Instead of one person trying to do everything, you assemble a team of specialists... **Protocol v12 is the 'Team Captain' or 'Project Manager' for a team of AIs.**

![Turn 1 Context](images/protocol-v12-explainer/Turn%2001a%20-%20Bootstrap%20AI%20.png)
![Turn 1 Output](images/protocol-v12-explainer/Turn%2001b%20-%20Bootstrap%20AI%20-%20Content.png)

### Turn 2: The Team & The Whiteboard

> Every AI in Protocol v12 has a specific role... They use a shared 'whiteboard' called the `global_context`... This keeps the entire AI team aligned and focused.

![Turn 2 Context](images/protocol-v12-explainer/Turn%2002a%20-%20Protcol_Explainer_AI.png)
![Turn 2 Output](images/protocol-v12-explainer/Turn%2002b%20-%20Protcol_Explainer_AI%20-%20content.png)

### Turn 3: The AI Specialist's Notebook

> After an AI finishes its assigned task, it fills out its 'notebook'—the `content` section... It’s all about transparency, letting us see not just *what* the AI did, but *how* it thought about it.

![Turn 3 Context](images/protocol-v12-explainer/Turn%2003a%20-%20Content_Synthesizer_AI.png)
![Turn 3 Text Output](images/protocol-v12-explainer/Turn%2003b%20-%20Content_Synthesizer_AI%20-%20content.png)
![Turn 3 JSON Output](images/protocol-v12-explainer/Turn%2003c%20-%20Content_Synthesizer_AI%20-%20json%20snippet.png)

### Turn 4: Passing the Baton

> The `continuation` block is the protocol's "Passing the Baton" moment. It names the next AI for the job and gives it a clear, precise instruction.

![Turn 4 Context](images/protocol-v12-explainer/Turn%2004a%20-%20Workflow_Architect_AI.png)
![Turn 4 Text Output](images/protocol-v12-explainer/Turn%2004b%20-%20Workflow_Architect_AI%20-%20Content.png)
![Turn 4 JSON Output](images/protocol-v12-explainer/Turn%2004c%20-%20Workflow_Architect_AI%20-%20json%20snippet.png)

### Turn 5: A Look Inside the AI's Brain

> The protocol tracks cognitive data... a transparent look into each AI's 'brain', recording its confidence, its reasoning process, and even its 'curiosity'.

![Turn 5 Context](images/protocol-v12-explainer/Turn%2005a%20-%20Cognitive_Psychologist_AI.png)
![Turn 5 Text Output](images/protocol-v12-explainer/Turn%2005b%20-%20Cognitive_Psychologist_AI%20-%20content.png)
![Turn 5 JSON Output](images/protocol-v12-explainer/Turn%2005c%20-%20Cognitive_Psychologist_AI%20-%20json%20snippet.png)

### Turn 6: The Final Report

> Once the main goal is achieved... the AI issues a `TERMINATE` command. This is the 'mic drop'—it tells the entire system that the project is successfully finished.

![Turn 6 Context](images/protocol-v12-explainer/Turn%2006a%20-%20Final_Report_Generator_AI.png)
![Turn 6 Text Output](images/protocol-v12-explainer/Turn%2006b%20-%20Final_Report_Generator_AI%20-%20Content.png)
![Turn 6 JSON Output](images/protocol-v12-explainer/Turn%2006c%20-%20Final_Report_Generator_AI%20-%20json%20snippet.png)

---

## Core Architecture

This showcase demonstrates a system built on these key principles:
* **Autonomous Agent Orchestration:** A single prompt initiates a workflow where AI agents create, assign, and complete tasks without human intervention.
* **Dynamic Role Delegation:** The system assigns specialist AI roles (e.g., `Protocol_Explainer_AI`, `Content_Synthesizer_AI`) based on the immediate needs of the task.
* **Transparent Cognition:** The process provides insight into each AI's reasoning, confidence, and internal state, making the entire workflow auditable and understandable.

## Tech Stack

| Frontend | Backend | AI Platform |
| :---: | :---: | :---: |
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) |
| | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) | *Gemini 1.5 Pro via Vertex AI* |
