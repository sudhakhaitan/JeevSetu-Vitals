JeevSetu AI — Integrated Physical Examination — Consolidated Note Fix 6

Changes:
- Updated final-note collection to prefer the fullest concise-note container per completed system instead of the shortest matching element.
- Keeps the final note limited to module note/summary containers; does not intentionally include examination forms.
- Includes all configured systems except Mental Examination.

Test:
1. Extract the ZIP and open index.html in Chrome.
2. Enter patient details once.
3. Complete and generate concise notes for Vitals, General Examination, Lymph Nodes, CVS and any other completed systems.
4. Tap Generate Final Clinical Note and verify all completed systems appear.
5. Print / Save PDF and verify only the consolidated note prints.

Important: verify in the browser with real completed module data before treating this build as validated.
