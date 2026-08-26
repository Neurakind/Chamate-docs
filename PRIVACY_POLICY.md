# Privacy Policy

**Last updated:** August 26, 2026

## Introduction

Chamate ("we", "our", or "us") respects your privacy and is committed to protecting your personal data. This privacy policy explains how we collect, use, and protect your information when you use our mobile application ("the App").

## Information We Collect

### Audio Data

Our app requests access to your device's microphone (`RECORD_AUDIO` permission) for the following purposes:

- **Voice Interaction:** To enable voice-based conversation features
- **Speech Recognition:** To convert your speech to text for better interaction
- **Audio Processing:** To provide personalized audio-based experiences
- **Voice Features:** To support voice-based functionality and features

### Other Data

- Device information (model, operating system version)
- User preferences and settings
- User activity and performance data

### Usage Analytics

We use Mixpanel, a third-party product analytics service, to understand how the App is used and to improve our features. Analytics does not block authentication, purchases, voice sessions, or navigation. If analytics is not configured for your build environment, tracking is safely skipped.

Before you sign in, analytics events are collected without linking to your account identity. After you sign in, we associate analytics with your account user ID and sync a limited profile (see below). When you sign out or delete your account, we reset the analytics identity on your device.

- **Device and session context:** platform (iOS or Android), country/region code, app environment (development or production), and a session identifier created each time you open the App
- **Voice session context:** when you start a conversation, a conversation identifier and mode (free talk or journey) may be attached to related events; we do not send audio recordings or transcript content to Mixpanel
- **Onboarding and settings:** steps completed, language and proficiency level selections, whether you submitted or skipped an optional phone number, and whether you enabled study reminders (not the phone number itself)
- **Authentication:** login success or failure with provider type (Google or Apple); we do not send passwords, OAuth tokens, or raw credentials
- **Engagement:** conversation and journey starts and completions, session duration, message/turn counts, character or topic selections, and technical error types when a session fails
- **Subscription and quota:** when usage limits are reached, paywall views and scroll engagement, purchase flow steps (plan selected, success or failure), and purchase amount/currency on successful in-app purchases; we do not send payment card or bank details
- **Error diagnostics:** error category and a sanitized error message; email addresses, phone numbers, JWTs, and bearer tokens are removed before transmission

When you are signed in, we may update your Mixpanel user profile with: premium status, subscription plan (if any), English proficiency level, native language, country/region, and total completed conversations. This helps us understand product usage; we do not sell this data or use Mixpanel for third-party advertising.

For how Mixpanel processes data, see Mixpanel's privacy policy at [https://mixpanel.com/legal/privacy-policy/](https://mixpanel.com/legal/privacy-policy/).

### Contact and Promotional Information

During the optional introduction steps when you first use the App, you may choose to provide:

- **Name:** Your display name or preferred name
- **Phone Number:** Your mobile phone number

Providing this information is **entirely optional**. You may skip these steps and continue using the App without limitation. If you choose to provide your name and phone number, we use this information solely to contact you about promotional programs, special offers, and benefits so you do not miss opportunities available to you.

We store this information on our own systems. **We do not sell, rent, or share your name or phone number with any third parties** for promotional or any other purposes.

### Subscription and Payment Data

- **Payment Processing:** All payment transactions are processed through the Apple App Store or Google Play Store. We do not directly collect, store, or process your payment card information
- **Subscription Status:** We receive information about your subscription status (active, expired, cancelled) from the app store platform
- **Purchase History:** We may receive anonymized transaction verification tokens to validate your subscription status
- **Billing Information:** Your payment method details and billing information are managed exclusively by Apple or Google and are not accessible to us

## How We Use Your Data

### Audio Data Processing

- **Local Processing:** Audio may be processed locally on your device for immediate feedback
- **Cloud Processing:** Some audio may be sent to secure cloud services for advanced speech recognition and AI processing
- **Temporary Storage:** Audio data is processed in real-time and temporarily cached only as needed for functionality

Chamate sends the user's voice recording to Chamate's backend for processing. The audio may then be processed using Google Cloud's Gemini Enterprise Agent Platform (formerly Vertex AI Platform) solely to convert the user's speech into text for the purpose of providing the speech and conversation functionality in Chamate.

Chamate uses Google Cloud's Gemini Enterprise Agent Platform for business as an enterprise AI service to process users' voice recordings solely for speech-to-text conversion. As an enterprise service, it is subject to Google Cloud's customer data privacy and security commitments, including that customer data is not used to train or fine-tune Google's AI/ML models without the customer's prior permission or instruction.

### Subscription Data Usage

We use subscription and payment-related information to:

- **Service Access:** Verify your subscription status and grant appropriate access to premium features
- **Account Management:** Manage your account and subscription lifecycle
- **Customer Support:** Provide support for subscription-related inquiries
- **Usage Analytics:** Understand subscription patterns to improve our service offerings (anonymized data only)
- **Fraud Prevention:** Detect and prevent fraudulent subscription activities

### Promotional Communications

If you voluntarily provide your name and phone number during onboarding, we use that information only to:

- **Program Consultation:** Inform you about promotional programs and eligible benefits
- **Offer Notifications:** Send you relevant updates about special offers when available
- **User Benefit:** Help ensure you do not miss promotional opportunities tied to your use of the App

We contact you only through channels we operate directly (for example, in-app messages, email, or phone/SMS initiated by our team). We do not use third-party marketing platforms to process or distribute your name or phone number.

You may decline to provide this information at any time during onboarding, and you may request that we stop promotional contact or delete your name and phone number at any time (see Your Rights and Choices and Account Deletion below).

### Analytics and Product Improvement

We use Mixpanel analytics data to:

- Measure app opens, onboarding completion, and activation into voice learning features
- Understand conversation and journey engagement, reliability, and common error patterns
- Analyze subscription funnels (quota limits, paywall views, and in-app purchases) to improve pricing and access
- Maintain and improve App performance and user experience
- Generate aggregated usage insights for internal product decisions, not for selling your data or serving third-party ads

Analytics events may be processed in the United States by Mixpanel. We configure analytics to avoid collecting unnecessary personal information and to sanitize error content before it is sent.

## Payment Data

We do not directly collect, store, or process your payment card information, bank account details, or transaction data.

For in-app purchases, payment information is collected and managed by the Apple App Store or Google Play Store under their respective policies. We only receive subscription status information from those platforms.

For payment procedures, subscription management, and related responsibilities, please see the Payments & Subscriptions section in our Terms of Service.

## Storage and Retention

- **No Permanent Storage:** We do not permanently store your audio recordings unless explicitly requested by you for specific features (e.g., saving voice notes)
- **Automatic Deletion:** Temporary audio data is automatically deleted after processing
- **User Control:** You can request deletion of any stored data at any time
- **Contact Information:** If you provided your name and phone number, we retain it only while needed for promotional communications or until you request deletion or opt out
- **Analytics Data:** Usage analytics stored by Mixpanel is retained according to Mixpanel's data retention settings and our project configuration; analytics identity on your device is reset when you sign out or delete your account

## Security

- **Encryption:** All audio data transmission is encrypted using industry-standard TLS/SSL protocols
- **Secure Servers:** Any cloud processing uses secure, SOC 2 compliant servers
- **Access Control:** Only authorized personnel have access to processing systems, and they are bound by strict confidentiality agreements

## Third-Party Services

Our app may use the following third-party services for enhanced functionality:

- **Speech Recognition APIs** (Google Cloud's Gemini Enterprise Agent Platform, formerly Vertex AI Platform)
- **Product Analytics** (Mixpanel)
- **Payment Processing** (Apple App Store, Google Play Store, RevenueCat)

**Mixpanel:** We send product usage events and limited profile fields to Mixpanel as described in Usage Analytics above. Mixpanel acts as a data processor/service provider for analytics. Its privacy policy is available at [https://mixpanel.com/legal/privacy-policy/](https://mixpanel.com/legal/privacy-policy/).

**Contact and promotional data:** Your name and phone number, if you choose to provide them, are **not** disclosed to these or any other third parties. They are used only by us for the promotional purposes described in this policy.

## Your Rights and Choices

You have the right to:

- **Deny Permission:** Deny microphone permission (though this may limit app functionality)
- **Revoke Access:** Revoke microphone permission at any time through your device settings
- **Data Deletion:** Request deletion of any stored personal data
- **Account Deletion:** Delete your account and associated personal data (see Account Deletion section below)
- **Data Export:** Request a copy of your data in a portable format
- **Opt-out:** Request limitation of analytics processing or deletion of analytics data associated with your account by contacting us (see Contact Us); signing out resets analytics identity on your device
- **Promotional Opt-out:** Decline to provide your name or phone number during onboarding, or request that we stop promotional contact and delete that information at any time by contacting us
- **Update Contact Information:** Request correction or update of your name or phone number on file
- **Subscription Management:** View, modify, or cancel your subscription at any time through your device's app store settings
- **Payment Information Access:** Access your payment history and billing information through your Apple or Google account
- **Subscription Data:** Request information about your subscription status and usage

## Account Deletion

When you delete your account, we take the following actions:

- **Personal Data Removal:** All personal data associated with your account will be permanently removed from our systems, including your name and phone number if you provided them for promotional communications
- **Analytics Identity:** We reset your Mixpanel analytics identity when you sign out; when you delete your account, we stop associating new activity with your user ID. You may also request deletion of analytics data linked to your account by contacting us
- **Promotional Communications:** We will stop all promotional contact using your name or phone number upon account deletion or upon your opt-out request
- **Abuse Prevention:** To prevent abuse of our free monthly quota system, we retain a non-identifiable hash of your email address for 30 days
- **Usage Tracking:** We also retain the number of tokens used during the current month for quota management purposes
- **Active Subscriptions:** Deleting your account does not automatically cancel your subscription. You must separately cancel your subscription through your device's app store settings to stop future billing. Subscription cancellation follows the terms outlined in our Terms of Service
- **Subscription History:** Anonymized subscription transaction records may be retained for legal, tax, and accounting purposes as required by law

This retention policy ensures fair usage of our free services while protecting your privacy through non-identifiable data storage.

## Children's Privacy

Our app may be used by children under 13. We comply with COPPA (Children's Online Privacy Protection Act):

- We do not knowingly collect personal information from children under 13 without verifiable parental consent
- Parents can review, delete, or request that we stop collecting their child's information
- We do not share children's personal information with third parties except as necessary for app functionality

## Data Security Measures

We implement comprehensive security measures including:

- **Encryption:** End-to-end encryption for data transmission
- **Access Controls:** Multi-factor authentication for system access
- **Regular Audits:** Security audits and vulnerability assessments
- **Incident Response:** Established procedures for data breach response
- **Staff Training:** Regular privacy and security training for all personnel

## International Data Transfers

If you are located outside the United States, please note that your information may be transferred to and processed in the United States, where our servers and service providers (including Mixpanel for product analytics) are located. We ensure appropriate safeguards are in place for such transfers in compliance with applicable laws.

## Changes to This Policy

We may update this privacy policy from time to time to reflect changes in our practices or applicable laws. We will:

- Post the updated policy in the app
- Notify users of material changes via app notification
- Update the "Last updated" date at the top of this policy

## Compliance

This privacy policy complies with:

- Google Play Store requirements for apps using microphone permissions
- Apple App Store privacy guidelines
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Children's Online Privacy Protection Act (COPPA)

## Contact Us

If you have any questions, concerns, or requests regarding this privacy policy or our data practices, please contact us:

**Email:** support@neurakind.com
**Response Time:** We aim to respond to privacy inquiries within 48 hours

---

_This privacy policy is effective as of the date listed above and applies to all users of the Chamate mobile application._
