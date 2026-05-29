# AI Tips & Tricks for Climate Science — Workshop Bundle

**LEAP Climate Data Science Bootcamp · Summer 2026 - Ayon Roy**
*Presented by Ayon Roy*

This bundle contains everything you need for the four hands-on exercises in the workshop.

---

## What's in the bundle

| File | Used in | Purpose |
|---|---|---|
| `prompts_to_makeover.md` | **Exercise A** — Prompt Makeover | Six weak prompts to rebuild with R-C-T-F |
| `exercise_B_debug.ipynb` | **Exercise B** — Debug a Climate Script | Jupyter notebook with 3 intentional bugs in an ERA5 analysis |
| `sample_era5.nc` | Exercise B | Small synthetic ERA5-like NetCDF for offline debugging |
| `ENSO_abstracts.md` | **Exercise C** — Literature Synthesis | Two abstracts on ENSO teleconnections, plus fact-check checklist |
| `exercise_D_pipeline.ipynb` | **Exercise D** — Build a Data Pipeline | Starter CMIP6 pipeline with TODO cells |
| `requirements.txt` | B + D | Pinned Python dependencies |
| `AI_Tips_Tricks_AyonRoy.pptx` | All | The session slide deck |


---

## Which AI tool to use

Any of these work:

- **Claude** (claude.ai) — strong on coding, long context for pasting whole notebooks
- **ChatGPT** (chat.openai.com) — strong all-rounder, GPT-4o handles file uploads
- **NotebookLM** (notebooklm.google.com) — best for Exercise C (multi-document grounding)
- **Gemini** (gemini.google.com) — strong on Google Drive integration

Pick the one you already use. The exercises are tool-agnostic; what matters is the **prompt**, not the brand.

---

## Troubleshooting

**"xesmf won't install."** Use conda (`conda install -c conda-forge xesmf`) instead of pip. On Colab, the install cell uses pip with `--no-deps` flags that usually work.

**"Pangeo CMIP6 catalog returns nothing."** The catalog occasionally drops models or rebuilds its index. Exercise D includes a `sample_era5.nc`-style fallback so you can still complete the analysis offline.

**"My AI tool refuses to give me code."** Try a different framing. Instead of *"Write me a script,"* try *"Here's the data I have, here's what I want to compute — what's the cleanest xarray approach?"* Models respond better to specific contexts than to abstract requests.

**"The AI's code uses a function that doesn't exist."** That's hallucination. Paste the traceback back into the same chat and ask *"that function doesn't exist in xarray 2024 — what's the right one?"* The model usually corrects itself.

---

Have fun. Verify everything. 🌍
Reach out to me at ayon.roy@columbia.edu
