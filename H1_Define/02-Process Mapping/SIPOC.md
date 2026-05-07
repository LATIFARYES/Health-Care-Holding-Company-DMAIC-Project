
# SIPOC

| Suppliers | Input | Process | Output | Customer |
|------------|--------|----------|---------|-----------|
| Patients, Reception Staff | Patient information, ID, Insurance details | 1. Patient Registration | Registered patient record | Internal: Triage Team |
| Patients, Nurses | Symptoms, Vital signs, Medical history | 2. Triage Process | Patient priority classification | Internal: Emergency Physicians |
| Internal: Registration & Triage | Patient file, Triage assessment | 3. Medical Assessment | Diagnosis and treatment plan | Internal: Treatment Area |
| Physicians, Nurses, Laboratory, Radiology | Medical orders, Lab results, Imaging | 4. Treatment Process | Stabilized patient | Internal: Discharge / Admission |
| Internal: Triage Team | Minor cases, Fast Track resources | 5. Fast Track | Rapid treatment and discharge | Internal: Discharge Team |
| Internal: Treatment Area, Bed Management | Completed treatment, Admission request | 6. Discharge / Admission | Discharged or admitted patient | External: Patients, Inpatient Departments |
