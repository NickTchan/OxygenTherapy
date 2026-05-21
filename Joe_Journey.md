# Patient Care Team for Joe's Scenario (74-year-old Male, ED Presentation)

Below is the breakdown of healthcare professionals who would interact with Joe in this learning scenario. This structure is organized for a nursing and Junior Medical Officer (JMO) learning module about oxygen therapy decision-making and care transitions.

## Key Interacting Personnel

| Professional | Role in Scenario | Typical Contacts with Joe |
|:------------|:-----------------|:--------------------------|
| **Triage Nurse** | First contact on arrival | Initial assessment, vital signs, oxygen saturation check, handoff deck preparation |
| **JMO (Junior Medical Officer)** | ED physician | Initial assessment, initial decision regarding supplementary oxygen, ordering investigations |
| **Consultant** | Senior physician | Governance review (specifically oxygen threshold decision-making, i.e., no O2 until SpO₂ <92%), ward referral |
| **ED Nurse** | Clinical care on acutely care | Administering/supervising O₂, monitoring vitals, medication administration |
| **Ward Nurse** | Post-transfer nursing care | Wards oxygen titration, monitoring respiratory status, ongoing observations |
| **Respiratory Therapist** | (Optional - some facilities) | Ward-level O₂ titration and maintenance (if available) |
| **Other Support Staff** | | Porters, administrative staff during care coordination |

## Detailed Breakdown of Key Interactions

### 1. Triage Nurse
- The first point of contact upon Joe's arrival.
- Takes baseline vital signs including `[SpO₂]`, respiratory rate, and temperature.
- Performs initial [ABCDE] airway, breathing, circulation assessment.
- **Key Learning Point:** Recognize signs of respiratory compromise and appropriate use of triage scales (e.g., ATS or Manchester classification).

### 2. Junior Medical Officer (JMO)
- Performs initial clinical assessment including auscultation (hears rhonchi/wheezes on lower right lung).
- **Targeted Learning Decision:** Must decide whether to initiate supplementary oxygen.
- In this scenario, the educational challenge is to **delay oxygen initiation** initially as part of the learning sequence:
    - The consultant review will demonstrate the pelvicatal of delaying supplemental oxygen until `[SpO₂] < 92%` (per learning scenario guidelines).
- Orders relevant investigations (e.g., CXR, blood work, sputum culture for pneumonia).

### 3. Consultant (Respiratory/Internal Medicine)
- Reviews patient escalates/guides oxygen titration policy:
  - "No O₂ until `[SpO₂] < 92%`"
- Directs transfer to general ward for ongoing care.
- **Key Learning Point:** illustrates consultant-level oversight and the communication of thresholds for care intervention.

### 4. ED/Ward Nurses
- Administer and monitor oxygen titration once administered.
- Monitor [SpO₂, RR, HR, BP] at regular intervals.
- Escalate to medical team if saturation changes.
- **Key Learning Point:** Oxygen titration documentation, recognizing when escalation is needed when saturation drops.

### 5. General Ward Team
- **Ward Nurses** manage ongoing oxygen therapy and monitor response to treatment.
- Provide reassessment, ensure IVs, medication, wound/hygiene care.
- Support discharge planning or hospital stay as required.

```mermaid
graph TD
    TN["Triage Nurse"]
    JMO["JMO"]
    C["Consultant"]
    EDN["ED Nurse"]
    W["Ward Nurse"]
    
    JMO --> TN
    JMO --> C
    C --> W
    W --> TN --> JMO
    W --> EDN