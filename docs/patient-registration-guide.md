# Patient Registration Guide — OpenMRS Web Application

## 1. Overview

This guide explains the patient registration workflow documented for the OpenMRS web application. It is intended to help authorised users understand how a patient record is created and what to check before saving it.

Accurate registration is important because patient records are used to organise and retrieve information within an electronic medical record system.

**Documentation status:** Initial draft  
**Platform:** OpenMRS web application  
**Audience:** Authorised registration clerks and other users responsible for creating patient records  
**Reference:** OpenMRS Web App Guide — Registering Patients

> **Important:** This guide is based on publicly available OpenMRS documentation. The exact interface and required fields may vary between versions and installations. Confirm the instructions against the version used by your organisation before following them in a live environment.

## 2. Intended Audience

This guide is intended for:

- Registration clerks who create patient records.
- Data-entry staff responsible for entering patient information.
- Authorised healthcare software users who need to understand the registration process.

Readers should have access to an authorised OpenMRS account and permission to register patients.

This guide does not explain clinical assessment, diagnosis, treatment, or the management of patient care.

## 3. Prerequisites

Before beginning registration, ensure that:

- You can access the appropriate OpenMRS web application.
- You are signed in with an account authorised to register patients.
- You have the information required by your organisation's registration procedure.
- You understand the organisation's process for checking whether a patient already has a record.
- You are working in the correct environment, such as a training environment or an authorised production installation.

Do not use real patient information in demonstrations, screenshots, or portfolio testing.

## 4. Before You Register a Patient

Before creating a new record, determine whether the patient already exists in the system.

Duplicate patient records can make it harder for users to locate the correct information and may result in information being distributed across multiple records.

Use the patient search or lookup functionality available in your installation. Follow your organisation's identity-verification and duplicate-record procedures.

If you find a possible existing record, do not create another one simply because some details differ. Follow the organisation's process for verifying the patient's identity and resolving potential duplicates.

## 5. Register a New Patient

The following procedure reflects the general workflow described in the OpenMRS web registration guide. Confirm the screen labels and field requirements against the installed version before using this guide operationally.

### Step 1: Open the patient registration workflow

1. Sign in to the OpenMRS web application.
2. Navigate to the patient search or registration area.
3. Select **Find/Create Patient**, or the equivalent option available in your version.

**Expected result:** The system opens the patient lookup or creation workflow.

**If the option is unavailable:** Check whether your account has the required permissions. Menu names and navigation may differ by version or configuration.

### Step 2: Check for an existing patient

1. Search using the identifying information available to you.
2. Review the results carefully.
3. Determine whether a matching patient record already exists.

**Expected result:** You can identify an existing record or establish that further registration steps may be needed.

**Important:** A failed search does not always prove that the patient has never been registered. Check spelling, identifiers, and your organisation's duplicate-record procedure before proceeding.

### Step 3: Enter patient information

If a new record is required, open the patient creation form.

Enter the information requested by the form and your organisation's registration procedure. The referenced OpenMRS web guide identifies the following fields as required:

- **Family Name:** The patient's family name.
- **ID Number:** The identifier entered for the patient.
- **Identifier Type:** The type associated with that identifier.

Other fields may be available or required depending on the installation.

**Before continuing:**

- Check spelling and data entry for errors.
- Confirm that the identifier is appropriate for the patient and identifier type.
- Follow the organisation's process for handling missing or uncertain information.
- Do not invent patient information to satisfy a required field.

### Step 4: Review the information

Before saving, review the information you entered.

Confirm that:

- The patient identity has been checked according to local procedures.
- The family name is entered correctly.
- The identifier and identifier type are appropriate.
- Required fields have been completed.
- You have not unintentionally created a duplicate record.

If information is incorrect, correct it before submitting the form.

### Step 5: Save the patient record

1. Select **Save**, or the equivalent submission control shown by your installation.
2. Wait for the system to finish processing the request.
3. Check the result displayed by the application.

**Expected result:** In the workflow described by the referenced web guide, saving the patient record takes the user to the Patient Dashboard.

If the application displays a validation error, review the message and correct the relevant information before trying again. Do not repeatedly submit the form without checking whether a record was already created.

### Step 6: Confirm the registration outcome

After saving:

1. Check whether the Patient Dashboard or equivalent patient record view is displayed.
2. Verify the patient details and identifier shown.
3. Confirm that the correct record has been opened.
4. Follow your organisation's procedure if the result is unclear or the record cannot be located.

A successful screen transition is useful evidence that the workflow completed, but users should follow local procedures for confirming the record was saved correctly.

## 6. Troubleshooting

| Problem | Possible explanation | Recommended action |
|---|---|---|
| Registration option is missing | The account may not have the required permission, or the interface may differ by version. | Check the available navigation and contact the system administrator if necessary. |
| Patient cannot be found | The search details may be incorrect, or the patient may be recorded under different identifying information. | Check the search terms and follow the organisation's identity-verification procedure. |
| A possible duplicate is found | The patient may already have a record. | Do not create another record until the existing record has been checked according to local procedures. |
| A required field is missing | The form may be incomplete or a required value may not have been entered. | Review the validation message and complete the required information using verified details. |
| The record does not appear to save | Validation, connectivity, permissions, or another system issue may be involved. | Check for an error message and confirm whether the record was created before attempting another submission. |
| The Patient Dashboard does not appear | The workflow may have failed, the interface may behave differently, or the session may have been interrupted. | Check the application response and follow the local support process. Avoid creating a second record until the outcome is clear. |

These are general troubleshooting recommendations, not a verified list of OpenMRS error messages. The actual cause should be established from the system's response and the applicable product documentation.

## 7. Privacy and Security Considerations

Patient registration involves information that must be handled responsibly.

Users should:

- Access patient information only when authorised.
- Follow the organisation's identity-verification and privacy procedures.
- Enter accurate information from approved sources.
- Avoid sharing patient identifiers or screenshots through unauthorised channels.
- Sign out or secure their session according to organisational policy.
- Report suspected duplicate records, incorrect information, or access problems through the appropriate support process.

This section provides general good-practice guidance. It does not establish the legal or regulatory compliance of a particular OpenMRS installation.

## 8. Frequently Asked Questions

### Why should I search before registering a patient?

Searching first helps identify existing records and reduces the risk of creating duplicate patient records.

### What should I do if I am unsure whether a record belongs to the patient?

Do not guess. Follow the organisation's identity-verification procedure or seek assistance from an authorised staff member.

### Are the same registration steps used in the OpenMRS Android client?

Not necessarily. The Android client has separate documentation and may use different screens, fields, and actions. Refer to the documentation for the specific platform you are using.

### Does reaching the Patient Dashboard prove every detail is correct?

No. The dashboard is the expected destination described by the referenced web guide, but users should still verify the displayed record and follow local registration procedures.

## 9. Source References

1. OpenMRS, *Registering Patients — Web App Guide*: https://guide.openmrs.org/collecting-data/registering-patients/
2. OpenMRS, *Patient Dashboard — Web App Guide*: https://guide.openmrs.org/using-the-system/patient-dashboard/
3. OpenMRS, *Android Client User Guide*: https://github.com/openmrs/openmrs-android-client-user-guide

The web application guide is the primary reference for the procedure in this document. The Android client guide is included only to distinguish the platforms; its registration steps have not been used as web application instructions.

## 10. Review Record

| Field | Value |
|---|---|
| Document | Patient Registration Guide |
| Project | OpenMRS Healthcare Documentation Portfolio |
| Status | Initial draft — requires source and version verification |
| Intended platform | OpenMRS web application |
| Last drafted | 26 October 2026 |
| Next review | Before publication or operational use |

## 11. Future Improvements

Before treating this guide as a finished portfolio sample:

- Confirm the current web guide's content and available revision information.
- Identify the OpenMRS version or installation to which the procedure applies.
- Verify the field names and navigation against that version.
- Add appropriately sourced screenshots from an authorised test environment, if available.
- Test the troubleshooting guidance and revise it based on observed behaviour.
- Ask a reviewer to assess clarity, completeness, and consistency.