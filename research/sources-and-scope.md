# Sources and Scope

## 1. Purpose

This document records the sources, assumptions, limitations, and research boundaries for the OpenMRS Healthcare Documentation Portfolio.

It establishes how information will be collected and verified before it is used in the portfolio's user guides and reference documentation.

The portfolio is an independent educational project. It is not produced, approved, or maintained by the OpenMRS project or the Therapeutic Goods Administration (TGA).

## 2. Project Scope

### In scope

This project will produce:

- A patient registration guide for a clearly identified OpenMRS platform.
- A troubleshooting guide based on documented behaviours and clearly labelled examples.
- An overview of privacy and access-control concepts relevant to healthcare software.
- A glossary of healthcare and software terminology.
- A record of research sources, assumptions, and limitations.

### Out of scope

This project will not:

- Provide clinical advice or instructions for diagnosing or treating patients.
- Use real patient information or confidential medical records.
- Claim that OpenMRS complies with a particular law, regulation, or certification without sufficient evidence.
- Present this portfolio as official OpenMRS documentation.
- Treat the web application and Android client as if they have identical interfaces or workflows.
- Replace an organisation's approved clinical, privacy, security, or operational procedures.

## 3. Source Register

The following sources provide the foundation for this project.

### Source 1: OpenMRS Web App — Registering Patients

**Link:** https://guide.openmrs.org/collecting-data/registering-patients/

**Source type:** Product user guide.

**Purpose:** Provides reference information about patient registration in the OpenMRS web application.

**Information to verify:**

- The intended user and prerequisites.
- The steps for creating a patient record.
- Required fields and identifiers.
- The expected outcome after saving a record.
- The relationship between registration and the Patient Dashboard.

**Limitations:** The guide may describe an older interface or version. Its instructions must not automatically be treated as accurate for every OpenMRS installation.

### Source 2: OpenMRS Android Client User Guide

**Link:** https://github.com/openmrs/openmrs-android-client-user-guide

**Relevant pages:**
- Patient registration: https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/patient-registration.md
- Troubleshooting: https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/troubleshooting.md
- Glossary: https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/glossary.md
- Getting started: https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/getting-started.md

**Source type:** Product user guide maintained in a public source repository.

**Purpose:** Provides examples of task-oriented documentation for the OpenMRS Android client, including registration, getting started, and troubleshooting.

**Information to verify:**

- The sequence of registration actions.
- Required patient information.
- Messages shown when information is missing.
- Offline registration and synchronisation behaviour.
- Troubleshooting structure and terminology.

**Limitations:** This guide documents the Android client. Its buttons, screens, fields, and behaviours must not be presented as web application instructions. The repository may also describe an older version, so version-specific claims require verification.

### Source 3: Australian Therapeutic Goods Administration — Understanding How We Regulate Software-Based Medical Devices

**Link:** https://www.tga.gov.au/resources/guidance/understanding-how-we-regulate-software-based-medical-devices

**Source type:** Australian government regulatory guidance.

**Purpose:** Provides context for understanding how intended purpose affects the regulatory status of software-based medical devices in Australia.

**Information to research:**

- The meaning of intended purpose.
- The distinction between general software and software that meets the definition of a medical device.
- The role of the Australian Register of Therapeutic Goods (ARTG).
- The importance of checking the applicable requirements before making regulatory claims.

**Limitations:** This source provides regulatory context. It does not establish that OpenMRS, any particular installation, or this portfolio is a regulated medical device or complies with specific regulatory requirements.

The guidance may change. Its current content and revision information should be checked when the document is reviewed.

## 4. Platform and Version Boundaries

The portfolio distinguishes between the following:

| Documentation area | Reference platform | Rule |
|---|---|---|
| Patient registration | OpenMRS web application | Use web application sources and verify the relevant version. |
| Android registration | OpenMRS Android client | Use Android-specific instructions and identify them as such. |
| Troubleshooting | Platform-specific | State which platform the problem applies to. |
| Privacy and access control | General concepts supported by authoritative sources | Separate general principles from verified product behaviour. |
| Regulatory context | Australian TGA guidance | Do not infer product compliance from general regulatory guidance. |

If the exact software version cannot be confirmed, the documentation will state this limitation rather than imply that the instructions apply to every release.

## 5. Research and Verification Method

Before adding a technical claim to a guide, the following process will be used:

1. Identify the relevant feature, workflow, or concept.
2. Locate the official product documentation or an authoritative primary source.
3. Confirm which product, platform, and version the source describes, where this information is available.
4. Record the source URL and the date it was accessed.
5. Compare relevant sources when they describe similar features or potentially different behaviour.
6. Separate directly documented facts from assumptions and recommendations.
7. Test a workflow in an authorised, non-production environment when access is available and testing is appropriate.
8. Revise or qualify any statement that cannot be verified.
9. Review links and source material before publishing updates.

Screenshots, if added later, will be captured from an authorised test environment and will not contain real patient information.

## 6. Handling Uncertainty

The following rules will be used throughout the portfolio:

- **Verified:** Supported directly by an authoritative source or an appropriately documented test.
- **Version-dependent:** May vary between product versions, installations, or configurations.
- **Assumption:** A working interpretation that has not yet been verified.
- **Recommendation:** Suggested documentation or usability practice, not necessarily existing product behaviour.
- **Out of scope:** A claim or topic that this portfolio is not intended to establish.

If sources conflict, the conflict will be documented and investigated rather than silently resolved through guesswork.

## 7. Privacy and Safety Considerations

Healthcare documentation can influence how users handle sensitive information. Therefore:

- No real patient names, identifiers, photographs, or medical records will be included.
- Any example patient information will be fictional.
- Instructions will not encourage users to bypass authentication or access restrictions.
- Access-control behaviour will not be claimed unless supported by relevant evidence.
- Security weaknesses or uncertain behaviours will be described cautiously and responsibly.
- Regulatory or legal statements will be linked to relevant authoritative sources and will not be presented as legal advice.

## 8. Citation and Attribution

Information taken from external sources will be attributed using links in the relevant document.

Where practical, documentation will identify the source page and the date it was accessed. Direct quotations will be limited and clearly attributed. The portfolio will primarily use original explanations rather than copying existing guides.

The source register will be updated when sources change, new references are introduced, or a claim needs additional verification.

## 9. Known Limitations

At the beginning of this project:

- No claim is made that the documentation has been tested against a live clinical deployment.
- Product behaviour may differ by version, configuration, permissions, or deployment.
- Regulatory context is introductory and does not replace a detailed assessment of applicable requirements.
- The portfolio is a learning project and has not undergone formal clinical, legal, security, or regulatory review.

These limitations will be revised if further evidence or testing becomes available.

## 10. Review Record

| Field | Value |
|---|---|
| Document | Sources and Scope |
| Project | OpenMRS Healthcare Documentation Portfolio |
| Status | Initial draft |
| Last reviewed | 26 October 2026 |
| Next review | Before publication of the patient registration guide |

## 11. References

1. OpenMRS. *Registering Patients.* https://guide.openmrs.org/collecting-data/registering-patients/
2. OpenMRS. *OpenMRS Android Client User Guide.* https://github.com/openmrs/openmrs-android-client-user-guide
3. OpenMRS. *Patient Registration — Android Client.* https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/patient-registration.md
4. OpenMRS. *Troubleshooting — Android Client.* https://github.com/openmrs/openmrs-android-client-user-guide/blob/master/troubleshooting.md
5. Therapeutic Goods Administration. *Understanding How We Regulate Software-Based Medical Devices.* https://www.tga.gov.au/resources/guidance/understanding-how-we-regulate-software-based-medical-devices
