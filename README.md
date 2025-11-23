
---

### C. `custommade-gpts/README.md` – AI & GPT Portfolio Hub

This is my **star repo** for AI assistants. :contentReference[oaicite:5]{index=5}  

```markdown
# custommade-gpts

Config, tooling, and validation for my custom ChatGPT agents:

- **PhotoPoet Storyteller**
- **Service Desk Content Coach**

This repository showcases how I think about **AI assistants**, **prompt design**, and **config-driven tooling**.

---

## 🤖 Agents

### 1. PhotoPoet Storyteller

An AI assistant that:

- Takes a photo description as input
- Produces poetry, micro-stories, or reflective captions
- Can be used for chapbooks, social posts, or creative journaling

**Focus areas:**

- Visual-to-text imagination
- Tone control (soft, poetic, social-commentary)
- Multi-output modes (poem, short story, caption)

---

### 2. Service Desk Content Coach

An AI assistant that:

- Helps IT support & service-desk agents write clear, professional replies
- Suggests empathetic language and structured responses
- Encourages best practices (acknowledge, clarify, resolve, recap)

**Focus areas:**

- Customer service tone
- Support ticket scenarios
- Template-like response structures

---

## 📁 Repository Layout (Planned Structure)

> You can create folders/files to match this structure as your next step.

- `photopoet-storyteller/`
  - `config.json` – core instructions & behavior
  - `examples/` – sample inputs and outputs
- `service-desk-content-coach/`
  - `config.json` – core instructions & behavior
  - `examples/` – real-world style ticket examples
- `tools/`
  - `validate_configs.py` – small script to ensure each config has required keys

---

## 🧪 Validation Script (Concept)

The `validate_configs.py` script is intended to:

- Load each `config.json`
- Confirm required keys like:
  - `name`
  - `description`
  - `instructions`
  - `capabilities` / `tools` (if used)
- Print a simple pass/fail report

This shows how I think about **quality gates** and **consistency** when working with AI configs.

---

## 🌟 Skills Demonstrated

- Prompt design & instruction writing
- JSON-based configuration
- Thinking in “agent architectures” instead of only single prompts
- Light Python scripting for validation and tooling
- Clear documentation & examples

---

## 📬 Contact

If you’d like to collaborate on GPT agents or AI-powered tools:

- GitHub: [@GrandMaTech76](https://github.com/GrandMaTech76)
- LinkedIn: [mmartin2025](https://www.linkedin.com/in/mmartin2025/)
