# JeevSetu Vitals — Stage A — One-page Clinician Printout

This package is the revised Stage A prototype based on the uploaded 3-page Vitals assessment.

## Changes implemented
- Cuff size, device and measurement position are dropdown menus.
- Orthostatic BP: supine, standing at 1 minute, and standing at 3 minutes.
- ABI calculated automatically for BOTH right and left legs.
- Highest brachial systolic pressure is calculated automatically from the two arm readings.
- The repeated manually-entered brachial systolic field has been removed.
- BMI calculated automatically.
- Hip-to-waist ratio calculated automatically.
- Nurse/ANM entry screen remains structured for data entry.
- Clinician printout is formatted as a single A4 page.
- Stage A does not generate diagnosis or clinical interpretation.
- Save locally uses the browser's local storage.

## ABI calculation used in this prototype
Right ABI = right ankle systolic / highest brachial systolic.
Left ABI = left ankle systolic / highest brachial systolic.

## Use
Open `index.html` in a browser. It can be uploaded to a GitHub Pages repository as the repository's `index.html`.

## Important
This is a prototype for workflow/testing. Final clinical thresholds, alerts and centre protocol should be confirmed before clinical deployment.
