The expanded workshop bundle is ready. Here's what's in it:

Exercise A

prompts_to_makeover.md

six weak starter prompts matching slide 14, with R-C-T-F rebuilding instructions and discussion questions.

Exercise B

exercise_B_debug.ipynb + sample_era5.nc

a 20-cell Jupyter notebook with three intentional, realistic bugs in an ERA5 analysis: .mean() without dim= (collapses time), a "WMO climatology" labeled as 1991–2020 but actually using the whole record, and a K→°C conversion applied to an anomaly. The synthetic NetCDF (191 KB, 1979–2023 monthly over a small Amazon-basin grid) lets students run the notebook offline. I tested that all three bugs reproduce and that the fixes produce physically sensible numbers.

Exercise C

ENSO_abstracts.md

two fictional-but-realistic ENSO teleconnection abstracts (one on North Atlantic NAO response, one on South Asian monsoon coupling in CMIP6), plus a fact-check checklist that flags the specific kinds of hallucinations students should look for (wrong numbers, swapped methods, invented citations).

Exercise D

exercise_D_pipeline.ipynb - a 17-cell CMIP6 starter with pre-configured imports, a Pangeo cloud-catalog query stub, a synthetic offline-fallback dataset (so the notebook works without internet), and TODO cells for the four pipeline stages (Acquire / Process / Analyze / Visualize). Each stage includes the exact prompt template students should paste into their AI tool.

Workshop support

requirements.txt + README.md - pinned dependencies and step-by-step Colab + local-Jupyter setup matching slide 18, plus troubleshooting notes for common xesmf and Pangeo issues.