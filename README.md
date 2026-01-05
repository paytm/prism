# Prism Swarm 🔮

**SPIDER 2.0 (SNOW ) Submission**

---

## Team

**Anshul Chauhan** · **Soham Acharya**  
Paytm 

---

## What is Prism?

Prism is an **autonomous multi-agent system** that thinks like a team.

Give it a question. It assembles the right agents. They debate. They disagree. They reach consensus. They deliver one answer.

---

## The Challenge

SQL generation isn't a prompt engineering problem.  
It's a **reasoning problem**.

Real-world queries demand:
- Understanding business context, not just table names
- Navigating complex schemas with 100+ tables
- Reasoning through temporal logic, aggregations, and edge cases
- Making decisions when the path forward isn't clear


## How Prism Works

### Multi-Agent Architecture
Specialized agents with distinct expertise:

### Autonomous Consensus
When agents disagree, they negotiate.  
When the path is uncertain, they explore.  
When mistakes happen, they learn.

**The system decides. Not the engineer.**

### One Question, One Answer  
The agents reach consensus on a single solution—or they iterate until they do.

---

## Why It Matters

Most "agentic" systems are still just LLMs with function calls.

Prism is different:
- **Agents have goals**, not just instructions
- **Conflicts are resolved through reasoning**, not heuristics
- **The system adapts**, without retraining
---

## Results

We submitted Prism to SPIDER 2.0 (SNOW Track):
- **Claude Sonnet 4.5** as the reasoning substrate
- **Zero manual intervention** – agents decide, humans observe
- **Complete decision traces** – every negotiation, every conflict, every resolution

Every query answered through agent consensus, not engineering hacks.

## Score

Evaluated against the Spider 2.0 benchmark: https://spider2-sql.github.io/

<img width="789" height="742" alt="Screenshot 2026-01-05 at 2 26 24 PM" src="https://github.com/user-attachments/assets/546dacc8-28fe-43ed-9d2e-b00121b2a6dc" />

---

## What's Next

Prism treats query generation as a **multi-player game** where agents cooperate toward a shared objective, not a state machine where transitions are hardcoded.

**Coming soon.**

The code stays proprietary. The ideas don't.

---

## Technical Details

### Model
- **Claude Sonnet 4.5** (Anthropic)
- Temperature: 0.0 (deterministic)
- Context: 200K tokens



---
## The Evolution of Agentic Systems

Most research optimizes **individual agent capability**.

We optimized **multi-agent coordination**.

It's not about building a better player. It's about building a better game—where cooperation yields better outcomes than competition, and consensus emerges through incentive alignment, not voting.


---

## Contact

**Anshul Chauhan** · anshul1.chauhan@paytm.com  
**Soham Acharya** · soham.acharya@paytm.com

Paytm 

---

*Paper coming soon.*

# prism
Agent Swarm for Automated SQL Generation
