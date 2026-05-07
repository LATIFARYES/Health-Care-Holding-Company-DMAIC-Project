
SIPOC 01 — Patient Registration

This SIPOC focuses on the patient registration sub-process, which is the entry point to the Emergency Department workflow. Delays or inaccuracies at this stage directly affect triage speed, patient flow, and overall waiting time performance.

| Suppliers | Input | Process | Output | Customer |
|------------|--------|----------|---------|-----------|
| Patients | ID, Insurance information, Personal details | 1. Patient arrival and check-in | Initial patient request | Internal: Reception staff |
| Reception Staff | Registration system, Patient information | 2. Patient identity verification | Verified patient identity | Internal: Registration system |
| Insurance Providers | Insurance approval data | 3. Insurance validation | Approved patient coverage | Internal: Registration desk |
| Registration System | Patient demographics, Medical record number | 4. Electronic patient registration | Registered patient file | Internal: Triage Team |
| IT Systems | Queue management system | 5. Queue assignment | Patient queue number | Internal: Triage nurses |
| Reception Staff | Completed registration data | 6. Patient transfer to triage | Ready-for-triage patient | Internal: Triage Process |


Key Quality Concern ⚠️

Any delay in registration, incomplete patient information, insurance verification issues, or queue management failures directly increases Door-to-Doctor Time and contributes to Emergency Department overcrowding.
