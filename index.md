# Privacy Policy for Snoop

**Effective Date:** July 1, 2026
**Last Updated:** July 1, 2026

## 1. Introduction

Snoop ("we," "our," or "us") is an intelligent product matching and price comparison application. This Privacy Policy explains how we collect, use, disclose, and protect your personal information when you use the Snoop mobile application ("App").

By using Snoop, you agree to the collection and use of information in accordance with this policy.

## 2. Information We Collect

### 2.1 Information You Provide

- **Account Information:** When you register, we collect your email address and a password (stored as a secure hash — we never store plaintext passwords).
- **Search Queries:** Text descriptions you type into the search bar.
- **Uploaded Images:** Images you upload to perform image-based product searches. These images are processed to generate an embedding vector and are not stored permanently.

### 2.2 Information Collected Automatically

- **Search History:** A record of your past text search queries, stored to power the "recent searches" and autocomplete features in the search bar.
- **Product Interactions:** When you tap on a product, we record which product was clicked, the timestamp, and (if you are signed in) your account identifier. This data is used solely to calculate trending products shown on the home screen.
- **Favourites:** The list of products you save to your favourites, associated with your account.
- **IP Address:** Your IP address is used for rate limiting on the search endpoint to ensure fair access for all users. It is not stored in a user profile or linked to your account.

### 2.3 Information We Do NOT Collect

- We do not collect payment or billing information. All purchases are completed on the vendor's own website.
- We do not collect your device's precise GPS location.
- We do not collect contacts, photos from your photo library, or any data unrelated to product search.
- We do not use any third-party advertising SDKs.
- We do not track you across other apps or websites.

## 3. How We Use Your Information

| Purpose | Data Used |
|---|---|
| Authenticate your account and secure sessions | Email address, hashed password, JWT tokens |
| Perform product search | Search query text or uploaded image (image not retained after embedding) |
| Display recent searches and autocomplete suggestions | Search history |
| Display trending products on the home screen | Anonymised product click events |
| Save and retrieve your favourite products | Favourites list, account ID |
| Prevent abuse of the search service | IP address (rate limiting only) |

We do not sell, rent, or trade your personal information to any third party.

## 4. Data Sharing and Disclosure

We do not share your personal information with third parties except in the following limited circumstances:

- **Cloud Infrastructure:** Product and user data is stored on Microsoft Azure (Azure Database for PostgreSQL). Azure acts as a data processor and is contractually bound to protect your data.
- **CLIP Inference Service:** When you perform a search, your query text or image is forwarded to our Python CLIP microservice hosted on Azure App Service solely to generate an embedding vector. No query data is logged or retained by this service.
- **Legal Requirements:** We may disclose information if required to do so by law or in response to a valid legal process (e.g., a court order or government request).
- **Business Transfers:** In the event of a merger, acquisition, or sale of assets, user data may be transferred as part of that transaction. We will notify you before your data is subject to a different privacy policy.

## 5. Data Retention

- **Account data** is retained for as long as your account is active. You may request deletion of your account at any time (see Section 8).
- **Search history** is retained for up to 12 months and is capped at 50 entries per user.
- **Product click events** (trending data) are retained for up to 12 months to allow all trending time windows (daily, weekly, monthly, all-time) to be computed accurately.
- **Uploaded images** are not stored. They are processed in memory to produce an embedding vector and immediately discarded.

## 6. Data Security

We implement industry-standard security measures to protect your information:

- Passwords are never stored in plaintext. Authentication is handled by SuperTokens, which applies secure hashing.
- All API communication is encrypted in transit using HTTPS/TLS.
- Access tokens are short-lived JWTs signed with asymmetric keys. The signing keys are managed internally and are not exposed.
- Database access is restricted to authorised backend services and is not publicly accessible.

Despite these measures, no method of transmission over the internet or method of electronic storage is 100% secure. We cannot guarantee absolute security.

## 7. Children's Privacy

Snoop is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe we have inadvertently collected information from a child, please contact us and we will delete it promptly.

## 8. Your Rights and Choices

Depending on your location, you may have the following rights regarding your personal data:

- **Access:** Request a copy of the personal data we hold about you.
- **Correction:** Request that we correct inaccurate data.
- **Deletion:** Request that we delete your account and associated personal data.
- **Export:** Request your search history and favourites in a portable format.
- **Opt-Out of History:** You may clear your search history at any time from within the App.

To exercise any of these rights, contact us at the email address in Section 10.

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this page. If the changes are material, we will notify you through the App or via email. Your continued use of the App after any changes constitutes your acceptance of the new policy.

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Email:** mazennazeih124@gmail.com

---

*This privacy policy was prepared to comply with Apple App Store Review Guidelines and applicable data protection laws.*
