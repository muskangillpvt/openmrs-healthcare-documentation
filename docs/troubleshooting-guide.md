# Troubleshooting Guide — OpenMRS Web Application

## 1. Overview

This guide helps users investigate common difficulties they may encounter while working with the OpenMRS web application, particularly during patient registration.

It provides a structured approach to identifying symptoms, checking possible causes, and determining when to contact a system administrator or support team.

This is an independent technical-writing portfolio document. It is not official OpenMRS support documentation.

**Platform:** OpenMRS web application  
**Intended audience:** Authorised registration clerks, data-entry staff, and application users  
**Status:** Initial draft — requires verification against the applicable software version

> **Important:** The problems and possible causes in this guide are general troubleshooting scenarios unless explicitly supported by a cited source or verified through testing. Error messages and interface behaviour may differ between OpenMRS versions and installations.

## 2. Before Troubleshooting

Before attempting to resolve a problem:

1. Identify the action you were trying to complete.
2. Record what happened and any error message displayed.
3. Check whether the issue is reproducible.
4. Confirm which OpenMRS environment and version you are using, if known.
5. Follow your organisation's privacy and security procedures.
6. Avoid repeating actions that could create duplicate records or change patient information.

When reporting an issue, include the relevant steps, approximate time, browser information if appropriate, and the exact error message.

Do not include real patient names, medical information, passwords, session tokens, or other sensitive information in screenshots, tickets, or portfolio examples.

## 3. Troubleshooting Patient Registration

### Issue 1: The patient registration option is missing

**Symptom**

You cannot find the patient registration option or the option to find or create a patient.

**Possible causes**

- Your account may not have the required permissions.
- The application navigation may differ from the instructions you are following.
- Your organisation may have configured the application differently.
- The relevant page may not have loaded correctly.

**Recommended steps**

1. Confirm that you are signed in to the correct OpenMRS environment.
2. Review the available navigation options.
3. Check the user guide for the version used by your organisation.
4. If the option remains unavailable, contact the system administrator and explain which page or menu you can access.

**Expected outcome**

You identify whether the issue relates to navigation, account permissions, or a configuration that requires further investigation.

**Escalate when**

The registration function remains unavailable despite following the approved access procedure.

### Issue 2: An existing patient cannot be found

**Symptom**

A search does not return the patient record you expected to find.

**Possible causes**

- The search terms may contain a spelling error.
- The patient may be recorded under a different name or identifier.
- The search criteria may be too restrictive.
- The record may not exist in the current system or environment.

**Recommended steps**

1. Check the spelling of the search terms.
2. Verify the identifier and other details against an approved source.
3. Try another permitted search method if the application supports it.
4. Confirm that you are searching in the correct environment.
5. If the record remains unavailable, follow your organisation's process for investigating missing records.

**Expected outcome**

You determine whether the record can be located or whether further investigation is required.

**Important**

A search returning no results does not prove that a patient has never been registered. Do not create a new record until the organisation's duplicate-record checks have been completed.

### Issue 3: A possible duplicate patient record is found

**Symptom**

The search results contain a record that may belong to the same patient you are attempting to register.

**Possible causes**

- The patient may already have an active record.
- Similar names may belong to different people.
- Identifying information may have changed or been entered inconsistently.
- A previous registration may have created a duplicate.

**Recommended steps**

1. Stop the new registration process.
2. Review the available identifying information in accordance with your permissions.
3. Follow the organisation's identity-verification procedure.
4. Ask an authorised supervisor or administrator to investigate if the identity remains uncertain.
5. Follow the approved process for handling duplicate records.

**Expected outcome**

The existing record is verified, or the case is referred for authorised investigation.

**Do not**

Do not merge, delete, or alter patient records unless you are authorised and following the organisation's approved procedure.

### Issue 4: The registration form reports missing information

**Symptom**

The application indicates that required information is missing or prevents the form from being submitted.

**Possible causes**

- A required field has been left blank.
- A value has not been entered in the expected format.
- The information does not satisfy a field validation rule.
- The installed version has different requirements from the guide being followed.

**Recommended steps**

1. Read the displayed validation message.
2. Identify the field or information that requires attention.
3. Check the relevant instructions for the installed version.
4. Enter or correct the information using a verified source.
5. Review the form and try submitting it again.

**Expected outcome**

The validation issue is resolved, or you have enough information to report the problem to support.

**Important**

Never invent patient information to satisfy a required field. Follow organisational procedures when information is unavailable or uncertain.

### Issue 5: Saving the patient record appears to fail

**Symptom**

You submit the registration form but do not see the expected confirmation or patient record view.

**Possible causes**

- A validation error prevented submission.
- The network connection was interrupted.
- The application encountered an unexpected error.
- The session expired or permissions prevented the action.
- The record may have been saved even though the expected page did not appear.

**Recommended steps**

1. Check the page for an error or validation message.
2. Determine whether the application is still responding.
3. Before submitting the form again, search for the patient using the approved lookup procedure.
4. If the record exists, verify that it is the correct record before continuing.
5. If the outcome remains unclear, contact the system administrator with the steps you followed and the error details.

**Expected outcome**

You establish whether the registration completed or whether the issue needs further investigation.

**Important**

Do not repeatedly submit the registration form without checking whether the record was already created.

### Issue 6: The Patient Dashboard does not appear

**Symptom**

After saving a patient record, the expected Patient Dashboard is not displayed.

**Possible causes**

- The registration workflow may not have completed successfully.
- The application may have encountered an error.
- The browser session may have been interrupted.
- The installed version may behave differently from the reference guide.

**Recommended steps**

1. Check whether the application displays an error message.
2. Confirm whether the patient record was created by using the approved search workflow.
3. If the record exists, open it only after verifying its identity.
4. If the record cannot be found or the outcome remains unclear, report the issue to support.
5. Avoid creating another record until the registration outcome is known.

**Expected outcome**

You determine whether the record exists and whether further technical investigation is necessary.

### Issue 7: The application becomes unresponsive

**Symptom**

The page stops responding, actions take unusually long, or the expected screen does not load.

**Possible causes**

- A temporary network interruption.
- A browser or application problem.
- A server-side issue.
- A session or authentication problem.

**Recommended steps**

1. Wait briefly to determine whether the current action completes.
2. Check whether other authorised pages are responding.
3. Record any visible error message.
4. Avoid refreshing or repeating a submission if doing so could duplicate an action.
5. If the issue persists, follow your organisation's support procedure.

**Expected outcome**

You determine whether the problem is temporary or requires administrator investigation.

**Escalate when**

The application remains unavailable, multiple users experience the same problem, or patient registration cannot be completed safely.

## 4. General Troubleshooting Decision Process

Use the following sequence when a problem is not covered above.

1. **Identify:** What action were you performing?
2. **Observe:** What happened instead of the expected result?
3. **Check:** Is there a message, missing field, or other visible clue?
4. **Verify:** Could the action already have completed?
5. **Resolve:** Follow the relevant approved procedure.
6. **Escalate:** Contact support if the issue remains unresolved or requires additional permissions.

Do not bypass access controls or make unauthorised changes to patient records as a troubleshooting shortcut.

## 5. Reporting an Issue

When contacting the support team, provide the following information where appropriate.

| Information | What to provide |
|---|---|
| Issue summary | A short description of the problem. |
| Steps to reproduce | The actions taken before the issue occurred. |
| Expected result | What you expected the application to do. |
| Actual result | What happened instead. |
| Error message | The exact message, excluding sensitive information. |
| Environment | The application version and environment, if known. |
| Browser | Browser name and version, if relevant and permitted. |
| Frequency | Whether the problem occurred once or repeatedly. |
| Impact | Which task is blocked or affected. |

Do not attach real patient records or sensitive screenshots unless an authorised organisational process explicitly requires them and the appropriate protections are in place.

## 6. When to Escalate

Contact the appropriate support team when:

- You cannot access a function that your role requires.
- You cannot determine whether a patient record was saved.
- A possible duplicate or incorrect patient record requires investigation.
- The application repeatedly fails during registration.
- The issue appears to affect multiple users.
- You suspect unauthorised access or exposure of patient information.

For suspected security incidents or privacy breaches, follow the organisation's incident-reporting procedure promptly. Do not investigate beyond your authorised role.

## 7. Privacy and Security Considerations

Troubleshooting must not compromise patient privacy or system security.

- Use only authorised accounts and environments.
- Do not share passwords or authentication tokens.
- Do not include identifiable patient information in public bug reports.
- Do not attempt to bypass permissions.
- Do not delete, merge, or modify patient records without appropriate authorisation.
- Follow local retention, incident-reporting, and support procedures.

These are general good-practice recommendations, not a statement that a specific installation complies with any particular legal or regulatory requirement.

## 8. Known Limitations

This guide provides general troubleshooting scenarios focused on patient registration.

The causes and actions described here have not all been tested against a live OpenMRS deployment. They should not be interpreted as a verified list of OpenMRS defects, error messages, or product-specific diagnostic procedures.

Before operational use:

- Confirm the applicable OpenMRS version.
- Compare the guidance with official documentation.
- Test procedures in an authorised, non-production environment where possible.
- Replace generic causes with verified product-specific information.
- Have the guide reviewed by an appropriate technical or operational reviewer.

## 9. References

1. OpenMRS, *Registering Patients — Web App Guide*: https://guide.openmrs.org/collecting-data/registering-patients/
2. OpenMRS, *Patient Dashboard — Web App Guide*: https://guide.openmrs.org/using-the-system/patient-dashboard/
3. OpenMRS, *Android Client User Guide — Troubleshooting*: https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/troubleshooting.md

The web application guides provide context for the registration workflow. The Android troubleshooting guide is included as a separate reference and should not be assumed to describe web application behaviour.

## 10. Review Record

| Field | Value |
|---|---|
| Document | Troubleshooting Guide |
| Project | OpenMRS Healthcare Documentation Portfolio |
| Platform | OpenMRS web application |
| Status | Initial draft — requires verification |
| Last drafted | 26 October 2026 |
| Next review | After checking the applicable version and testing the procedures |

## 11. Future Improvements

The next revision should:

- Add verified, version-specific error messages and solutions.
- Record the source supporting each product-specific troubleshooting procedure.
- Test the instructions in a safe environment.
- Add sanitised screenshots where they improve clarity.
- Include a consistent escalation path once an appropriate support process is established.
- Review the guide for accessibility, plain language, and consistency with the patient registration guide.
