[Previous Page - Home Page](index.html)

### Background
The COVID-19 pandemic highlighted the importance of identifying the scope of medication use among hospitalized patients for new and emerging diseases during public health emergencies. Data sources for accurate, efficient, scalable reporting of medication exposure among patients hospitalized with suspected or confirmed COVID-19 were lacking throughout the pandemic. This NHSN-COVID-19- Medication-Administration-FHIR implementation guide (IG) seeks to overcome some of the challenges of other time-, labor- and cost-intensive methods of quantifying and characterizing medication use, such as data based on administrative claims, by utilizing a vendor-neutral, interoperable standard for fully electronic patient-level queries of medication data among U.S. inpatient populations. It builds upon NHSN’s long-standing experience in healthcare surveillance, and hospital quality and benchmarking efforts for inpatient antibiotic use and expands upon data collected by federal health entities related to the impact of COVID-19 on hospital bed capacity, personal protective equipment, and other public health emergency resources.

### Scope
In this IG, medication administration events refer to clinician-administered events (e.g., nurse giving a patient their medication dose), those occurring in inpatient settings; this excludes: emergency department, observation/short stay, inpatient rehabilitation, outpatient surgical centers, and other outpatient (including physician office) settings. Medication administration events are collected irrespective of whether they are linked to adverse events.

### Example Scenarios
* How were scarce medications (e.g., monoclonal antibodies approved under Food and Drug Administration emergency use authorization) utilized in patients hospitalized with COVID-19? 
* In what patient populations (e.g., by age, sex, race) and in what doses, frequencies, and durations?
* What was the scope of hydroxychloroquine utilization in patients hospitalized with suspected or confirmed COVID-19?
* How did hospital antibiotic utilization change throughout the COVID-19 pandemic?

### Relationship to Other Guides/Work
Closely related to [HL7 CDA® R2 Implementation Guide: Healthcare Associated Infection (HAI) Reports - AU](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=426); however, key differences include:
1. dependence of the NHSN-COVID-19-Medication-Administration-FHIR IG on FHIR resources and
2. patient-level approach to data collection (i.e., request is for raw data and not pre-aggregated data).

[Next Page - Downloads](downloads.html)