---
layout: page
title: Privacy Policy (DRAFT)
permalink: /privacy/
---

# We + Care Privacy Policy — DRAFT

> **Internal draft only. Do not publish or submit as-is.** Bracketed items require the publisher’s confirmation. This draft is based on the current repository, not a verified production data-flow audit or legal review.

- **Effective date:** [DATE]
- **Operated by:** [PUBLISHER LEGAL NAME]
- **Contact:** [PRIVACY EMAIL / POSTAL ADDRESS]
- **Public URL:** [HTTPS PRIVACY POLICY URL]

## About this policy

We + Care helps adults support their wellbeing and stay connected with people they choose. This policy explains information the service may collect, how it is used, and choices available to you. The app’s current registration flow requires a name, date of birth, and verified phone number. The app currently enforces an age minimum of 18; confirm this remains the intended policy before publication.

## Information we handle

Depending on the features you use, We + Care may handle:

- **Account and contact details:** name, date of birth, phone number and verification status; connection names, relationship labels, and selected invite/contact details. Account creation uses phone verification. The connection model also has an optional invite-email field; confirm whether that flow is enabled before saying the app never handles email addresses.
- **Profile and health information you choose to provide:** height, weight, blood type, allergies or conditions, provider information, profile photo, and emergency-contact names, relationships, and phone numbers.
- **Content you create or receive:** Well Checks and replies, affirmations, shared wellness information, ordinary messages, community posts/messages, reactions, check-in plans, and related status/history.
- **Location and device information:** the app may request location access to choose a region for public-health information. It also uses notification/device tokens and technical details such as app version, device model, operating-system version, locale, time zone, network type, and diagnostic/error details. **Confirm whether precise coordinates ever leave the device and what location granularity is retained.**
- **Support and purchase information:** issue descriptions you submit, and transaction/entitlement details needed to process or verify Apple purchases and restore access.
- **Usage events:** the current telemetry model includes event and session identifiers, a hashed user-scope identifier, screen/flow/result, app/device context, and diagnostic properties. A hash may still be linkable to an account; do not describe this data as anonymous without verification.

## How we use information

We use information to create and secure accounts; connect people who choose to interact; deliver messages, Well Checks, shared content, and notifications; display profile information according to sharing controls; provide regional health information; process support requests; operate subscriptions; prevent misuse; maintain and troubleshoot the service; and comply with applicable requirements.

## Sharing and service providers

Content is delivered to the connection or community you select. Profile details are shared according to the profile-sharing choices you enable. The service uses Supabase for authentication, database, storage, backend functions, and telemetry. Phone verification uses the SMS provider configured for the production authentication service: **[PROVIDER NAME / DATA HANDLING TO CONFIRM]**. Apple provides StoreKit/App Store billing and Apple Push Notification service. The app also requests public health and research information from external sources; confirm which requests are made by the app versus the backend and what request metadata those sources receive.

We may disclose information when required by law or when needed to protect users, the service, or others. **[Publisher: confirm whether data is sold, used for advertising, or shared for any additional purpose; add accurate language here.]**

## Retention and deletion

We keep account/profile information while needed to provide the service. Messages and shared wellness information have expiry behavior in the code, and telemetry has a configured retention routine; the production schedules, exceptions, backup lifecycle, and support-record retention have not been verified for this draft. **Before publication, state the actual retention period for each data category and what remains in backups or legal records.**

You can initiate account deletion from the app’s account settings. Deletion should remove the account and associated personal data/content, subject to legally required retention. **[Confirm production deletion behavior, completion time, retained records, and backup removal.]** Deleting your app account does not cancel an Apple subscription; manage or cancel that through Apple’s subscription settings.

## Your choices

You can manage contact and location permissions in iOS Settings, change profile-sharing choices in the app, manage notification permissions in iOS, and request account deletion in the app. **[Add the confirmed process and supported territories for access, correction, export, objection, or other privacy requests.]**

## Health information and emergencies

Public-health information and social check-ins are for general wellbeing and connection. They are not medical advice, diagnosis, treatment, or emergency monitoring. For a medical emergency, contact local emergency services or a qualified health professional.

## Security, age, and changes

We use administrative, technical, and organizational safeguards intended to protect information. No method of storage or transmission can be guaranteed completely secure. The app is intended for people age 18 and older. We may update this policy; the published version will state its effective date and how material changes are communicated.

## Contact

- Questions or privacy requests: **[PRIVACY CONTACT]**
- Publisher: **[PUBLISHER LEGAL NAME]**
- Address, if required: **[PUBLISHER ADDRESS]**

---

### Publisher review checklist

- Confirm every field and data flow against the production build, Supabase project, SMS provider, APNs, StoreKit verification, feed requests, and telemetry.
- Confirm retention, deletion, backups, and legal exceptions from production configuration and provider contracts.
- Confirm sharing and community visibility language matches the controls users see.
- Replace every bracketed item, publish at a stable public HTTPS URL, and obtain privacy/legal review before release.
