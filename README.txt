JeevSetu — Combined Physical Examination All Modules
Formatting correction v4 (based on uploaded formatted corrected v3)

Fix in this build:
- The Vitals → Musculoskeletal module now saves the complete rendered clinical-note HTML as well as the legacy text note.
- The Combined Clinical Note loads that HTML, preserving respiratory anterior/posterior chest-map images and the abdominal digital map instead of flattening the note to plain text.
- Added combined-report print styling for the respiratory and abdominal maps.

How to test:
1. Open index.html in the same browser/device used for the previous tests.
2. Open Vitals → Musculoskeletal and load/re-enter the findings as needed.
3. Select Generate Compact Clinical Note / Generate Consolidated Clinical Note so the new HTML is saved.
4. Return to Combined Note and select Refresh Notes.
5. Check Respiratory chest maps and Abdominal digital map on screen and in Print / Save Combined PDF.

Important: older saved localStorage data is text-only. Regenerate the Vitals → Musculoskeletal clinical note once with this build before refreshing Combined Note, so the HTML version including drawings is saved.
