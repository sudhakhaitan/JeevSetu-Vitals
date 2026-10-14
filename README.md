# JeevSetu — Skin & Dermatological Examination

GitHub Pages module for the JeevSetu Skin & Dermatological Examination.

## Contents

- `index.html` — complete standalone Skin examination form
- `README.md` — installation and testing instructions

## Main Features

### Skin History
Includes:
- New skin change
- Mole / old lesion change
- Non-healing wound
- Itching / rash
- Foot/sole wound, blister, colour change or slow-healing cut

### General Skin Examination
The following findings can be recorded individually:

- Pallor
- Jaundice
- Cyanosis
- Petechiae
- Purpura
- Ecchymosis / bruising
- Rash
- Pigmentation changes
- Ulcers
- Nodules / masses
- Other significant lesions

### Dropdown Behaviour

A field does **not** automatically imply that a finding is normal or absent.

The examiner can select:

**Not assessed / not recorded**

when the finding has not been assessed or no observation has been entered.

Other options are:

- Normal / absent
- Present

This is intended to prevent an unexamined finding from appearing as a confirmed normal finding in the clinical note.

## Petechiae / Bleeding Assessment

Additional fields include:

- Site / distribution
- Localized / generalized
- Extent
- Mucosal bleeding
- Fever / systemic symptoms
- Relevant medications
- Known blood disorders

## Mole / Pigmented Lesion

Records:

- Site
- Size
- Colour
- Shape
- Border
- Symmetry
- Surface
- Bleeding
- Ulceration
- Reported change

## Non-healing Wound

Records:

- Site
- Size
- Depth
- Edge
- Base
- Discharge
- Surrounding inflammation
- Duration

## Digital Skin Body Map

The body map is interactive.

- Tap the body to place a red mark.
- Tap an existing red mark to remove it.
- Use **Clear all marks** to remove all markings.
- The marked body map is reproduced at the **end of the Clinical Note**.

## Clinical Note

Press **Generate Clinical Note** to create the readable clinician-facing note.

The note contains:

1. Skin history
2. General skin examination
3. Petechiae / bleeding assessment
4. Mole / pigmented lesion assessment
5. Non-healing wound assessment
6. Digital Skin Body Map at the end

The form itself is hidden when printing so that only the Clinical Note is printed.

## GitHub Pages Installation

1. Extract this ZIP.
2. Upload `index.html` and `README.md` to the required GitHub repository.
3. Commit the files.
4. Enable GitHub Pages for the repository if it is not already enabled.
5. Open the GitHub Pages URL.
6. Test the form on the Samsung tablet/Chrome.

## Important Testing Point

Before clinical use, test every dropdown and the body-map marking function on the actual GitHub Pages deployment.

This module is a prototype examination-recording interface and does not itself make a medical diagnosis.
