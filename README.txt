JeevSetu Integrated Physical Examination — CONSOLIDATED NOTE FIX7

Correction: the consolidation routine previously rejected every note element nested inside a form. This caused valid module notes (including Vitals) to be discarded, while an external CVS note could still be selected. The routine now permits note containers inside forms while still excluding containers that contain interactive inputs/buttons.

Test: enter patient details, complete Vitals only, then select Generate Final Clinical Note. Confirm that a Vitals section appears. Then test General Examination, Lymph Nodes and CVS, and confirm all completed systems are included. CVS murmur behavior is intentionally unchanged and remains for the final pass.

Open index.html in Chrome. This is a standalone HTML package; no installation is required.
