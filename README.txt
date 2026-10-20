JeevSetu Master Integration V2-5-127 — Fresh working build
Based on the tested V2-5-126 history + physical examination package.
Changes in this build:
1. Patient ID saved to shared browser storage after Section 1 and transferred into matching Patient ID fields in physical modules.
2. Examiner name required before generating a clinical note; a required examiner field is added to modules that lacked one.
3. Automatic reuse of patient name/ID in matching fields; other repeated clinical values are not overwritten where mapping cannot be safely inferred.
4. Combined Note now includes the Hindi Master History-Taking Clinical Note and English physical-examination module notes in one combined record.
5. Clear save-each-module instructions are shown in the physical examination area and individual modules.
Important: Open the ZIP's index.html using the same browser/device for both history and physical examination. Complete Section 21 and generate/save the Hindi Master Clinical Note; save each physical module; then open Combined Note and press Refresh Notes. Please field-test on the target Android tablet before clinical use.
