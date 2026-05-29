# Exercise A — Prompt Makeover Challenge

## Goal
Take each of the weak prompts below, paste it into your favorite AI chat tool, observe the (likely vague or generic) response, and then rebuild the same intent using the **R-C-T-F framework**:

- **R**ole — who should the AI be? *("Act as a climate data scientist familiar with CMIP6 reanalysis...")*
- **C**ontext — what is the situation, dataset, scale, time window? *("I have ERA5 daily 2m temperature, 1979–2023, 0.25° grid, Amazon basin")*
- **T**ask — one verb, one deliverable. *("Compute the linear trend in JJA mean")*
- **F**ormat — exactly how should the output look? *("Return a pandas DataFrame; explain the code in 2 sentences after the block")*

Pick at least **two** of the weak prompts below to rebuild. Compare outputs with a partner.

---

## The six starter prompts (pick any two)

### 1. "Help me with my climate data."
*What's missing?* Everything. The model has no idea what dataset, what task, or what "help" means.

### 2. "Make a map of ocean temperatures."
*What's missing?* Which ocean? Which period? Anomalies or absolute values? Cartopy or matplotlib? Annual mean or a specific month?

### 3. "Summarize this paper."
*What's missing?* Audience (peer? undergrad?), length, what to focus on (methods? findings? limitations?), output format (bullets? paragraph?).

### 4. "Why is my code broken?"
*What's missing?* The actual code. The actual traceback. The expected behavior. The environment.

### 5. "Tell me about climate change."
*What's missing?* Scope (global? regional? a single mechanism?), audience, length, what aspect (mitigation? attribution? impacts?), and what claim format you want (with citations? without?).

### 6. "Write a Python script for some analysis."
*What's missing?* What analysis. On what data. With what libraries. Producing what output.

---

## Submission

For each prompt you rebuild, paste into your notebook or worksheet:

1. The **original weak prompt** and a 1-sentence note on what was missing.
2. Your **rebuilt R-C-T-F prompt**.
3. A 1-sentence note: *did the rebuilt version actually produce a better answer?* (Sometimes the model surprises you.)

---

## Discussion (10 min)

- Which of R / C / T / F changed the output most for your prompt?
- Did adding constraints **help** the output or did it make it overly rigid?
- Did your partner's rebuild of the same starter find a detail you missed?
