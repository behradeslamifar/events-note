# AgentCon Utrecht - Jun 25th
- [globalai.community: AgentCon Utrecht](https://globalai.community/e/l9bfp20y)
- [📍 Theater Maitland - Landgoed de Horst](https://maps.app.goo.gl/bMXKmPAGMiUvUitK9)

## Agenda

#### Part 1
- The Evaluation of Agents at Microsoft and Everywhere - Marco Casalaina
- Cascading Failures in Multi-Agent Systems: Tracing and Evaluating Multi-Agent Deployments - Olecsandra Bovkun
- Codidng smarter with Github Copilt - Brabara Forbes
- Agent Framework v1 and what's next!

#### Workshops
- Building the 80%: Architecting Agentic AI with Event-Driven Desing and Solace Agent - Hari Rangarajan
- Building Multi-Agent Systems with Microsoft Agent Framework: Lost in Driebergen - Stuart van der Lee

#### Part 2
- Agentics DevOps for Real World - Olaf Molenveld
- GPT-NL: Lessons learned from training the first lawful Dutch LLM from scratch - Claartje Barkhof, Alexandru Turcu
- Bringing 750 years of Amsterdam history to life - Douwe van de Ruit
- Context is all you need: building reliable long-running agents - Jesse Wellenberg
- Software engineering in the age of AI agents: who’s in control? - Bert Jan Schrijver
- 🤖 Copilot Cowork: Work Together with AI, Get Things Done - Daniel Laskewitz, Albert-Jan Schot

## Note
Four dimention of Governance
- Operational Health
- Cost Management
- Compliance and Audit
- Quality and Value

If you want to increase innovation,
you have to lower the cost of failure
- Joi Ito, Director MIT Labs


The Great Asymmetry
20 years of human-scale balance

```text
     Idea          Code         Review        Test        Deploy      Release

  +----------+  +----------+  +----------+  +----------+  +----------+  +----------+
  |          |  |          |  |          |  |          |  |          |  |          |
  |          |  |          |  |          |  |          |  |          |  |          |
  |          |  |          |  |          |  |          |  |          |  |          |
  |          |  |          |  |          |  |          |  |          |  |          |
  |          |  |          |  |          |  |          |  |          |  |          |
  |==========|  |==========|  |==========|  |==========|  |==========|  |==========|
  +----------+  +----------+  +----------+  +----------+  +----------+  +----------+
       1x           1x            1x           1x            1x            1x
```

We engineered the SDLC for symmetry.
Each stage calibrated to what humans could absorb.


The Great Asymmetry
AI shattered the equilibrium

```text
      Idea            Code            Review           Test          Deploy         Release

   +-----------+   +-----------+   +-----------+   +-----------+   +-----------+   +-----------+
   |           |   |===========|   |           |   |           |   |           |   |           |
   |           |   |===========|   |           |   |           |   |           |   |           |
   |           |   |===========|   |           |   |           |   |           |   |           |
   |           |   |===========|   |     ⚠     |   |     ⚠     |   |     ⚠     |   |     ⚠     |
   |           |   |===========|   |           |   |           |   |           |   |           |
   |===========|   |===========|   |===========|   |===========|   |===========|   |===========|
   +-----------+   +-----------+   +-----------+   +-----------+   +-----------+   +-----------+
        1x             10x              1x             1x             1x             1x
```

AI 10x'd code generation overnight.
Everything downstream is drowning in information it can't process.


Introducing Autonomous Validation
- Self-Verify: Automated verification of functional rquirements and performance baselines.
- Self-Correct: AI-driven loops to fix detected issues before human intervention is required.
- Self-Deploy: Safe, policy-driven deployment using real-time feedback signals.
Evolving from "Follow these 10 steps" to "Evaluate these 10 signals."


The Five Pillars of Autonomous Validation
- Pillar 1 Contextual Understanding
```text
Context is the Engine
Agents shouldn't fly blind. By feeding Git
history, CI/CD metadata, and historical
failures into the validation prompt, we provide
the AI with ancestry.
Historical Git Context
Failure Pattern Analysis
Metadata-driven Inference
```

- Pillar 2 Smart Testin 
```text
Stop Testing Everything
                        +------------------------------------+
Legacy scripted testing | ===============100 %============== |
                        +------------------------------------+

                        +------------------------------------+
Smart adaptive testing  | ==20%==                            |
                        +------------------------------------+
```
Goal: Fail fast in 2 minutes, not 20. Run only the tests that matter.

- Pillar 3 Agentic Remediation
```text
Let the AI Fix Itself
The Sandbox: An isolated inner loop for
"safe failure."
AI shouldn't just "suggest" a fix; it should
prove a fix in a sandbox before a human
ever sees the PR.
```

- Pillar 4 Continuous Learning & Progressive Delivery
```text
The Outer Loop: Validating in the Wild
The real test is always in production.
Automating canary releases and rollbacks based on SLO deviations.
```

- Pillar 5 Natural Language Interaction
```text
Engineer Prompt:
"Why did the auth-service fail in the sandbox?
Can you provide a fix that respects our legacy
Can you provide a fix that respects our legacy
```

```text
Autonomous Output:
"The failure was due to a version mismatch in
lib-v1.2.0. I have hypothesized a patch, verified
it in Sandbox-A, and created PR #402."
```
Moving from YAML debugging to conversational diagnostics.


Chunk for inner loop validation - https://chunk.ai/

In the AI Era, Code is a Commodity—
but Validation is your Competitive
Advantage.
