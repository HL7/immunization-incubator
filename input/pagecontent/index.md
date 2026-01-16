### Introduction

This Additional Resources Incubator Implementation Guide (IG) defines FHIR resources necessary for the sharing of information related to developing personalized immunization forecasts based on a patient’s immunization history, health attributes, lifestyle and other factors. 
As implementers develop, test and implement production-ready systems utilizing the Additional Resources defined by this IG, feedback will be incorporated, and the resources will mature with the eventual goal of moving them to a Normative status in a future release of the FHIR Core Specification. We welcome all feedback on these resources.

### In this IG

- Additional FHIR Resources
    - The [**ImmunizationEvaluation**](StructureDefinition-ImmunizationEvaluation.html) resource is defined for the purpose of conveying the outcome of the assessment of the validity of an immunization event relative to a set of recommended guidelines
    - The [**ImmunizationRecommendation**](StructureDefinition-ImmunizationRecommendation.html)  resource is defined for conveying a set of personalized recommendations for an individual
- Supporting Content
    - The **Value Sets** required by these Additional Resources are defined
    - **Examples** are provided

### Relationship to Other Work

This IG references Normative resources in the FHIR R6 Core Specification and is intended to extend the immunization related capabilities of the Core Specification. The references defined in this IG may be used by other IGs to define use case specific FHIR-based interoperability solutions.

### Dependencies
{% lang-fragment dependency-table-nontech.xhtml %}

### IP Statements
{% lang-fragment ip-statements.xhtml %}