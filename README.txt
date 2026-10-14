JeevSetu integrated build — Musculoskeletal + Endocrine / Metabolic.
Order: existing Vitals, General Examination, Lymph Nodes, CVS, Respiratory, Abdominal, Neurological, readable Musculoskeletal section, then Endocrine / Metabolic.
Fixes: YES follow-up details are explicitly initialized and toggled for hypothyroidism, hyperthyroid pattern, Cushing syndrome, acromegaly, and adrenal/pigmentation screen. Generate Clinical Summary builds the endocrine findings; Print / Save PDF prints the Musculoskeletal clinical note first (when available), followed by the Endocrine summary. Endocrine note remains separate from diabetic-foot findings/drawings.
Open index.html in a browser. Test print/PDF in the target browser before clinical use.

Print override v2: final high-priority print CSS limits endocrine print mode to the consolidated prior-system note, musculoskeletal note, and endocrine summary; prevents legacy rules from exposing the full endocrine form.

Print fix v3: rebuilds the base note at print time and adds separate Respiratory, Abdominal, Neurological, Musculoskeletal, and Endocrine notes in order, without printing the endocrine examination form.
