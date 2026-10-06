JeevSetu — 19.17 Vascular / Peripheral Circulation Examination
===============================================================

GitHub-ready standalone module.

Files:
- index.html — complete module; no external libraries or internet connection required.
- README.txt — this file.

Scope:
- Bilateral brachial, radial, femoral, popliteal, posterior tibial and dorsalis pedis pulses.
- Limb colour, pallor/cyanosis/dependent rubor, skin changes, hair loss, ulceration, gangrene,
  temperature difference and swelling.
- Varicose veins, pigmentation, venous eczema, chronic venous changes and venous ulcer.
- Vascular symptoms/history: claudication, rest pain, limb coldness, non-healing wound,
  previous vascular intervention and previous DVT.
- Bleeding history, kept separate from the Skin module.
- ABI and bilateral BP display for integration with the existing Vitals/ABI record.
- Clinical Note generated only when the examiner presses Generate Clinical Note.
- Print mode hides the form and prints only the Clinical Note.
- Browser-local storage is used for standalone testing.

Integration note:
The final JeevSetu integrated build should populate the ABI/BP fields from the authoritative
Vitals/ABI encounter record instead of creating a second ABI record. The section should be
placed as Section 19.17 and contribute its findings to the single final clinician note.

Important:
This is a standalone test build because the latest Genitourinary ZIP itself was not available
as a current attachment in this conversation. It does not overwrite or replace the working
Genitourinary module.
