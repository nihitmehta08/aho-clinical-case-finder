aHO Case Finder

A single-file, medication-neutral MVP for clinical case-finding of acquired hypothalamic obesity (aHO) and generation of a clinician-ready HPI draft.

Suggested repository name

aho-clinical-case-finder

What it does

The tool asks a patient-friendly series of questions about:

A known or plausible acquired hypothalamic injury

Rapid weight gain beginning after the injury or treatment

Persistent weight gain

Hunger, satiety, and food-seeking changes

Fatigue, activity, sleep, temperature regulation, and behavior

Pituitary hormone conditions

Prior MRI or clinician documentation of hypothalamic involvement

It then produces:

A non-diagnostic case-finding category

A count of core and supportive features

A structured HPI draft that can be reviewed and edited by a clinician

Important clinical limitation

This tool is not a validated diagnostic instrument or risk calculator.

It does not:

Diagnose acquired hypothalamic obesity

Generate a disease probability

Determine eligibility for setmelanotide or any other treatment

Replace clinician review of BMI or BMI-SDS trajectory, imaging, operative history, endocrine status, comorbidities, or competing diagnoses

The labels are intentionally framed as:

Features not currently suggestive

Possible aHO pattern

High clinical suspicion

These are case-finding outputs, not diagnoses.

Privacy

The current MVP:

Runs entirely in the browser

Does not use a backend

Does not save responses

Does not transmit patient information

Does not use cookies or browser storage

Do not enter identifiable patient information into a publicly hosted demo.

Run locally

No installation is required.

Download or clone the repository.

Open index.html in a modern web browser.

Publish with GitHub Pages

Create a public or private GitHub repository named aho-clinical-case-finder.

Upload index.html and README.md.

Open the repository's Settings.

Select Pages.

Under Build and deployment, choose Deploy from a branch.

Select the main branch and /root.

Save.

GitHub will provide a Pages URL after deployment.

Proposed clinical workflow

Patient completes the screen before an obesity medicine or endocrinology visit.

The tool identifies whether the history contains a plausible aHO pattern.

The clinician reviews the generated HPI.

The clinician verifies:

The hypothalamic injury or lesion

Temporal relationship between injury and weight gain

Serial BMI or BMI-SDS trajectory

Hunger and satiety symptoms

Pituitary hormone status

Relevant MRI, operative, oncology, or radiation records

Alternative causes of weight gain

The result is used only to support a clinical assessment.

Recommended next steps before clinical use

Review every question and output with obesity medicine, endocrinology, neurosurgery, and pediatric specialists as appropriate.

Obtain institutional approval before integration into a clinical workflow.

Decide whether the project qualifies as quality improvement, research, or both.

Perform cognitive interviews with patients to confirm readability.

Pilot the tool against expert clinician assessment.

Measure sensitivity, specificity, agreement, completion time, and false-alert burden.

Revise the logic before making any diagnostic or predictive claims.

Design choices

The tool deliberately avoids:

Brand names

Medication recommendations

Arbitrary numerical probabilities

Claims of validation

Storage of patient data

The scoring logic uses three core case-finding elements:

Plausible acquired hypothalamic injury

Rapid weight gain beginning within approximately 12 months

Persistent or difficult-to-reverse weight gain

Documented hypothalamic involvement and hyperphagia increase concern but do not independently establish the diagnosis.

File structure

aho-clinical-case-finder/
├── index.html
└── README.md

License

For internal educational and clinical-development discussion. Add a formal open-source license only after your team agrees on ownership, institutional policy, and intended use.
