# PRIVACY POLICY FOR COSTINGPRO

**Effective Date:** 7 October 2026
**Last Updated:** 7 October 2026
**Publisher:** Pareshkumar Panchal

---

## 1. Introduction

This Privacy Policy explains how **CostingPro** ("the Application"), developed and published by **Pareshkumar Panchal** ("we", "us", or "our"), handles information when you install and use the Application on Android devices.

CostingPro is an on-device manufacturing cost engineering, quotation preparation, and estimation tool designed for industrial manufacturers, machine shops, and fabrication businesses.

If you have questions regarding this Privacy Policy or data handling, you may contact our Privacy Representative at **pareshkumar.b.panchal@gmail.com**.

---

## 2. Information Stored in CostingPro

CostingPro is designed as a standalone, device-local productivity application. When you use the Application, you may voluntarily input and store commercial and manufacturing information, including:

- **Company Profile Data:** Company name, business tagline, Goods and Services Tax Identification Number (GSTIN), contact person name, telephone number, email address, physical factory/office address, and state/state code.
- **Customer & Transaction Data:** Customer name, customer state/union territory, and customer GSTIN.
- **Product & Technical Specifications:** Part numbers, product names, drawing numbers, and revision numbers.
- **Cost Engineering Parameters:** Raw material quantities, unit prices, scrap percentages, scrap recovery rates, machine operations, cycle times, setup durations, hourly machine and labour rates, factory overhead rates, administrative overhead rates, packing costs, and transport costs.
- **Pricing & Tax Calculations:** Profit margins, markup selections, computed ex-factory selling prices, GST percentages (Intra-State CGST/SGST or Inter-State IGST), and final prices.
- **Revision History & Notes:** Historical costing records, revision deltas, status classifications (Draft or Approved), and user-authored engineering notes.

**Storage Location:** All of the above information is stored locally within the Application's private internal storage sandbox on your Android device, utilizing an on-device Room SQLite database.

---

## 3. How CostingPro Uses Information

Information entered into CostingPro is processed locally on your device to provide the Application's core functionality, specifically:

- Calculating gross/net material costs, scrap deductions, process costs, labour costs, and machine operating costs.
- Computing prime manufacturing costs, factory/administrative overheads, profit margins, and ex-factory selling prices.
- Calculating applicable Goods and Services Tax (GST) breakdowns (CGST, SGST, IGST).
- Maintaining and comparing historical cost revisions.
- Generating multi-page manufacturing cost estimation and quotation documents in PDF format.
- Managing local catalogs of reusable materials and machine processes.

CostingPro does not use the information for:

- Advertising
- Analytics
- Behavioral tracking
- Credit scoring
- Algorithmic profiling
- AI training

---

## 4. Data Transmission

- **No Developer Server:** We do not operate, host, or maintain any remote backend server, cloud database, or application programming interface (API) that collects or receives data entered into CostingPro.
- **No Transmission to Publisher:** Stored costing records, customer details, financial margins, and company profiles are not transmitted to Pareshkumar Panchal.
- **No Tracking SDKs:** CostingPro does not contain any third-party analytics, telemetry, crash-reporting, or advertising software development kits (SDKs).
- **Local Owner Access Protection:** CostingPro uses a local, on-device Owner PIN to protect access to information stored on the device. No cloud account, remote login, or server-side credentials are created or transmitted.

Stored information remains on your device unless you choose to export and share documents externally as described in Section 5.

---

## 5. Document Export and Sharing (PDF Generation)

- **Local PDF Rendering:** When you create a Cost Sheet PDF, the document is generated locally on your device by the Android operating system's native graphics and PDF engine.
- **Temporary Cache Storage:** Generated PDF files are temporarily stored in the Application's private internal cache directory.
- **User-Initiated Sharing:** If you choose to share a cost sheet, CostingPro dispatches the document using Android's system share sheet (`Intent.ACTION_SEND`). This operation uses Android's FileProvider mechanism with scoped, temporary read-only permissions (`FLAG_GRANT_READ_URI_PERMISSION`).
- **Third-Party Handling:** Once you select a recipient application or service, such as an email client, messaging app, cloud storage drive, or printer, the transmission and handling of that document fall under the privacy practices and terms of service of that respective third-party application. CostingPro does not control the privacy practices of third-party recipient applications.

---

## 6. Backup and Device Migration

CostingPro adheres to a controlled Android backup policy to protect proprietary commercial pricing and customer data:

- **Exclusion from Cloud Backup:** The CostingPro Room database and its internal SQLite storage files are explicitly excluded from standard Android cloud backup services, such as Google Drive or Google One automated device backups, via Android data extraction configuration rules.
- **Device-to-Device Migration:** The database is configured to permit transfer during supported direct Android device-to-device migrations, such as cable connection or Wi-Fi Direct transfers initiated during a new device setup. Device migration is managed directly by the Android operating system and supported device-transfer mechanisms.
- **No Developer Cloud Sync:** CostingPro does not maintain its own cloud backup, synchronization, or remote restoration service.

---

## 7. Data Retention and Deletion

- **Local Retention:** All data entered into CostingPro is retained on your device for as long as you maintain the Application on your device, unless you choose to delete it.
- **In-App Deletion:** You can delete individual costing records, raw materials, or machine processes directly through the Application's user interface.
- **Complete Deletion:** You may permanently erase all data stored in CostingPro at any time by:
  1. Opening your device **Settings → Apps → CostingPro → Storage → Clear Data / Clear Storage**, or
  2. Uninstalling CostingPro from your device.
- **No Remote Retention or Recovery:** Because CostingPro operates without a remote backend, we do not possess duplicate copies of your data. Once deleted from your device, your data cannot be retrieved or restored by Pareshkumar Panchal.

---

## 8. Security

We take the security of your manufacturing and commercial data seriously:

- **Application Sandboxing:** CostingPro relies on Android's application sandbox architecture, which isolates the Application's files and Room database from other applications installed on the device.
- **Controlled Component Exposure:** CostingPro does not export unprotected activities, broadcast receivers, or content providers. Its internal FileProvider is configured with `android:exported="false"` and grants temporary read access exclusively when explicitly initiated by the user.
- **No Excessive Permissions:** CostingPro does not request network permissions (`INTERNET`), external broad storage permissions, camera access, microphone access, or location tracking.
- **Device Security Responsibility:** Because data is stored on-device, overall security depends significantly on your device's security practices, such as maintaining an active device lock screen (PIN, password, or biometrics) and running a supported Android operating system version.

---

## 9. Third-Party Services and SDKs

The current version of CostingPro (V1) does not incorporate or transmit data to:

- Third-party advertising networks.
- User tracking or analytics suites.
- Third-party crash logging or diagnostic frameworks.
- Remote cloud storage or database providers.

The only interaction with third-party software occurs when you voluntarily share a PDF document with an external application of your choice via Android's system share sheet.

---

## 10. Children's Privacy

CostingPro is specialized business-to-business (B2B) software designed for industrial manufacturing engineering, cost analysis, and commercial estimation. It is intended strictly for professional and commercial use and is not directed toward children. We do not knowingly solicit, collect, or store information from children.

---

## 11. User Rights and Data Inquiries

Where applicable under relevant privacy and data-protection laws, individuals may have rights concerning their personal data.

Because CostingPro operates without cloud user accounts or centralized server storage:

- **Access and Portability:** You have direct, continuous access to all your stored records within the Application and can export cost estimates as PDF documents at any time.
- **Correction:** You can edit company profiles, customer details, rates, and costing records directly within the Application interface.
- **Erasure:** You can delete specific records in the Application or erase all records by clearing application storage or uninstalling the app.
- **Absence of Centralized Database:** Pareshkumar Panchal does not possess an account database or server repository from which your records could be located, retrieved, modified, or deleted.

For inquiries regarding this policy, contact **pareshkumar.b.panchal@gmail.com**.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect operational, legal, or regulatory changes. Any updates will be published with a revised **Effective Date** and **Last Updated** date at the top of the policy.

You are advised to review this policy periodically for any changes.

---

## 13. Contact Information

If you have questions, feedback, or concerns regarding this Privacy Policy or CostingPro's privacy practices, please contact:

**Publisher Name:** Pareshkumar Panchal
**Privacy Contact Email:** pareshkumar.b.panchal@gmail.com
**Mailing Address:** Chhani, Vadodara, 391740, Gujarat, India

---

**End of Privacy Policy**
