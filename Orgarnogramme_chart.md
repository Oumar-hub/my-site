# Engineering Gounkoto - Organogramme Chart

```mermaid
flowchart TB
    UG["UG Engineering<br/>Superintendent: Harouna Sanogo"]

    UG --> EI["Shaft Instrumentations And Electrical"]
    UG --> FP["Fixed Plant Mechanical"]

    EI --> EIF["Elect & Inst Foreman<br/>Siaka Kone"]
    EIF --> IE["Instrumentation Engineer<br/>Sory I Dembele<br/>Vacant: 1"]
    EIF --> EE["Electrical Engineer<br/>Boubacar Traore"]
    EIF --> ES["Electrical Senior Supervisor<br/>Salif Diawara<br/>Vacant: 1"]
    EIF --> SUPI["Supervisor<br/>Zeze Camara"]

    IE --> OTA["OT & Automation Teams<br/>Available: 11 | Required: 14 | Gap: 3"]
    OTA --> OTA1["OT & Automation Team 1<br/>Vacant, Vacant, Vacant<br/>RA: 3"]
    OTA --> OTA1B["OT & Automation Team 1<br/>Siaka Sogodogo<br/>Fousseni Konate<br/>Ibrahima Diakite"]
    OTA --> OTA2["OT & Automation Team 2<br/>Hamidou Tangara<br/>Fousseni Sylla<br/>Abdoul K Coulibaly"]
    OTA --> OTA3["OT & Automation Team 3<br/>Mohamed L. Sylla<br/>Mamadou Lougue<br/>Ibrahima Traore"]
    IE --> INST["Instrumentation Team<br/>Lalah Aicha Bah<br/>Awa K Bah"]

    ES --> SHIFTEI["Shift Supervisors<br/>Sidi Kone<br/>Karamoko Dembele<br/>Mohamed Sacko<br/>Drissa Samogo - Acting"]
    EE --> DAYE["Day Artisan Electrical<br/>Clarice Diarra<br/>Konimba Diarra"]
    EE --> PRODE["Production Electricians<br/>8 available / 8 required"]
    EE --> PASTE["Paste Electricians<br/>8 available / 8 required"]

    FP --> FPSF["Fixed Plant Foreman / Snr Foreman<br/>Diawoye Sissoko"]
    FPSF --> FPF["Foreman<br/>Harouna Kone"]
    FPF --> SMS["Senior Mechanical Supervisor<br/>Sory Diarra"]
    FPF --> SMSB["Senior Mechanical Supervisor Backfill<br/>Ousmane Coulibaly"]

    SMS --> SHIFTM["Shift Supervisors / Day Crew Leads<br/>Djibril Sanogo<br/>Abdoulaye Keita<br/>Yaya Mariko<br/>Moutaga Sissoko - Acting<br/>Moussa Toure<br/>Aliou K Keita<br/>Seydou Sow<br/>Djibroulaye Mariko<br/>Brehima Konate"]
    SMS --> FIT["Fitters<br/>Available: 9 | Required: 10 | Gap: 1"]
    SMS --> PUMP["Day Crew Pumping<br/>Cheick Hamala Konate<br/>Awa Daou<br/>Aissata Diakite"]
    SMSB --> BM["Boiler Makers<br/>Patrice Traore<br/>Laya Kone<br/>Wahidou Sangare<br/>Ely Berthe"]
    SMSB --> DCBM["Day Crew Boiler Makers<br/>Youssouf Diakite<br/>Evariste Dakouo"]

    classDef top fill:#1f4e79,color:#fff,stroke:#17365d,stroke-width:1px;
    classDef dept fill:#d9ead3,stroke:#6aa84f,stroke-width:1px;
    classDef lead fill:#fff2cc,stroke:#bf9000,stroke-width:1px;
    classDef team fill:#eef3f8,stroke:#9eafc5,stroke-width:1px;
    classDef gap fill:#fce4d6,stroke:#c65911,stroke-width:1px;

    class UG top;
    class EI,FP dept;
    class EIF,FPSF,FPF,IE,EE,ES,SUPI,SMS,SMSB lead;
    class OTA,FIT gap;
    class OTA1,OTA1B,OTA2,OTA3,INST,SHIFTEI,DAYE,PRODE,PASTE,SHIFTM,PUMP,BM,DCBM team;
```

## Headcount Summary

### Electrical And Instrumentation

| Position | Available | Requirement | Gap |
|---|---:|---:|---:|
| Foreman | 1 | 1 | 0 |
| Inst Eng | 1 | 2 | 1 |
| Elect Eng | 1 | 1 | 0 |
| Snr Sup | 2 | 3 | 1 |
| OT & Auto Team | 11 | 14 | 3 |
| Shift Sup | 6 | 6 | 0 |
| Prod Elec | 8 | 8 | 0 |
| Paste Elec | 8 | 8 | 0 |

### Fixed Plant Mechanical

| Position | Available | Requirement | Gap |
|---|---:|---:|---:|
| Snr Foreman | 1 | 1 | 0 |
| Foreman | 1 | 1 | 0 |
| Snr Sup | 2 | 2 | 0 |
| Shift Sup | 9 | 9 | 0 |
| Fitters | 9 | 10 | 1 |
| DS Pumping | 3 | 3 | 0 |
| Boilermakers | 6 | 6 | 0 |
