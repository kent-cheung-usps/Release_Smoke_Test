Relesae tests

2025-07-02

[Build#: COP-(2.2.1-release-sit-env-2.2.1-e0b8810-12), Date: Jul 2, 2025]

`Regression Test for existing user`

Login: catccwoman (generic user | Firefox Private Mode)
- Add Mailer ID (MID)
  - OUTBOUND & RETURNS [✔]
  - OUTBOUNT ONLY [✔]
  - RETURNS ONLY [✔]
- Add Locations
  - OUTBOUND & RETURNS [✔]
  - OUTBOUNT ONLY [✔]
  - RETURNS ONLY [✔]
- Navigate to "Ship Now" [✔]
- Navigate to "Ship with APIs" [✔]
- Navigate to EPS : "Manage Accounts" [✔]
- Navigate to EPS CC [✔]
- Third Party Billing Enrollments [✔]
- Download Priority Mail 5x5 [✔]
- CIAM auto sign out after sign out from EPS [✔]
- CIAM auto sign in after sign in from BCG [✔]

2025-07-03

[Build#: COP-(2.2.1-release-sit-env-2.2.1-e0b8810-12), Date: Jul 2, 2025]

`Onboarding New User`

Login: catpeter03 (generic user | Incognito)
- Registration process
  - Address creation [✔]
  - CRID creation [✔]
  - Payment Account creation [✔]
- Add Mailer ID (MID)
  - OUTBOUND & RETURNS [✔]
  - OUTBOUNT ONLY [✔]
  - RETURNS ONLY [✔]
- Add Locations
  - OUTBOUND & RETURNS [✔]
  - OUTBOUNT ONLY [✔]
  - RETURNS ONLY [✔]
- Navigate to "Ship Now" [✔]
- Navigate to "Ship with APIs" [✔]
- Navigate to EPS : "Manage Accounts" [✔]
- Navigate to EPS CC [✔]
- Navigate to "Priority Mail Next Day" Link [✔]
- Download Priority Mail 5x5 [✔]
- Third Party Billing Enrollments [✔]
- CIAM auto sign out after sign out from EPS [✔]
- Login to BCG (catpeter01) [✔]
- Business location pull down box [✔]
  <img src="https://github.com/user-attachments/assets/9122f907-a47f-4bec-a99d-ee7dae8c7968" alt="Alt Text" width="300" height="100">
- BCG Profile Integrity [✔]
- MID Integrity mid-cat.usps.com [✔]




 
---
<!--
Potential defect: (Resolved. Expected.)

1. login to existing user (ex. catccwoman / Cop@9075)
2. Manage Locations -- > Actions -- > Add Mailer ID
3. DO NOT touch "Associate new Mailer ID to a CRID"
4. Only select EPA
5. Check Returns Mailer ID (Ref to screenshot)![image](https://github.com/user-attachments/assets/3780ce97-58eb-4b79-a517-deab07d02642)
6. Click "Request Mailer ID" button
7. Result: Missing Company and Address. Even worst, cannot reproduce.![image](https://github.com/user-attachments/assets/118f72f5-434d-4c44-b3eb-245ac6562d5e)
-->
