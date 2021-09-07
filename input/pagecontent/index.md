### Overview

This IG will support electronic submission of patient/line-level medication administration data to the National Healthcare Safety Network (NHSN). The intent of this project is to establish an electronic submission standard that is vendor-neutral that leverages existing workflows and eliminates duplicate documentation. This project will work with EHR vendors to identify data elements that can be used to describe medications administered (name, formulation, route, dose, duration) to hospitalized patients (inpatients) diagnosed with COVID-19 as part of NHSN COVID-19 reporting pathways. Medication administration events would be reported irrespective of whether or not medication administration was linked to an adverse event, refer to clinician-administered events (e.g., nurse giving a patient their medication dose), and only those occurring in inpatient settings; this excludes: emergency department, observation/short stay, inpatient rehabilitation, outpatient surgical centers, and other outpatient (including physician office) settings.

Medication data are integral to informing the quality, safety, and costs of U.S. healthcare, supporting federal, state, and local public health, and guiding clinical decision-making in patient care. In inpatient workflows, medication administration—as captured by electronic medication administration (eMAR) records—is considered the gold standard for accurately measuring in-hospital medication exposure, including identifying the exact medications patients have received, in what formulations, doses, and for what duration of time. The need for medication administration information has never been clearer as during the COVID-19 pandemic, where identification of the medications that acutely ill hospitalized patients with COVID-19 had received was integral to understanding clinical management of this new public health threat and directing public health resources, including scarce medications. The continued reliance on the "medication list" resource instead of the "medication administration" resource is a severe limitation in achieving accurate representation of medication exposure in U.S. healthcare data through FHIR resources.

### IG

This implementation guide provides HL7 FHIR resources to define standards for exchange between a hospital and NHSN. 

This publication provides the data model, defined data items, and their corresponding code and value sets, for reporting inpatient medication administration data for inpatients diagnosed with COVID-19. This guide describes constraints on the US Core and base FHIR resources for reporting, which are derived from requirements developed by the NHSN in consultation with the Health Level Seven (HL7) Pharmacy Work Group. Resources in this US Realm implementation guide are specific to reporting medication administration data to NHSN.

This guide contains a library of FHIR profiles and is compliant with FHIR Release 4. At a minimum, a Document Bundle and Composition will be exchanged along with a Patient, and associated COVID-19 Condition and laboratory results.

This guide defines 4 new Profiles:

* [Composition - Inpatient Medication Administration](StructureDefinition-Composition-inpatient-med-admin.html)
* [Condition - Lab Confirmed COVID-19](StructureDefinition-Condition-lab-confirmed-covid.html)
* [Condition - Suspected COVID-19](StructureDefinition-Condition-suspected-covid.html)
* [Observation - Laboratory SARS COVID-19](StructureDefinition-Observation-lab-sars-cov.html)



### Authors

<table>
<thead>
<tr>
<th>Name</th>
<th>Email/URL</th>
</tr>
</thead>
<tbody>
<tr>
<td>HL7 International - Pharmacy</td>
<td><a href="http://www.hl7.org/Special/committees/medication" target="_new">http://www.hl7.org/Special/committees/medication</a></td>
</tr>
</tbody>
</table>


