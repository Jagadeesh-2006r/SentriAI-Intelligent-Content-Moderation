# Demo Proof

## What to Show in the Hackathon Demo

1. Open the UiPath Maestro Case project.
2. Show the SentriAI content moderation workflow.
3. Open the UiPath Orchestrator and select the **SentriAI Agent**.
4. Start the Agent job with sample content (text, image, or video).
5. Show the AI moderation result returned by the agent.
6. Demonstrate the moderation decision:

   * **Safe** → Content is published.
   * **Flagged** → Case is sent to UiPath Action Center for human review.
   * **Blocked** → Content is rejected automatically.
7. Show the Orchestrator job history and audit logs.

---

## Verified Orchestrator Job

* **Workspace:** SentriAI Workspace
* **Process:** SentriAI Agent
* **Status:** Successful
* **Trigger:** Manual
* **Type:** Agent
* **Source:** UiPath Orchestrator
* **Result:** Content Moderation Completed

---

## Sample Agent Output

```json
{
  "classification": "Flagged",
  "decision": "human_review",
  "confidence": 94.8,
  "reason": "Potential hate speech detected"
}
```

---

## Demo Outcome

The demo shows how SentriAI uses **UiPath Maestro Case**, **Agent Builder**, **Orchestrator**, and **Action Center** to automate content moderation while ensuring human oversight for uncertain cases. This provides a secure, transparent, and enterprise-ready moderation workflow.
