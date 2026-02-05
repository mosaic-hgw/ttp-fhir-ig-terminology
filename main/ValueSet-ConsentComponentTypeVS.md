# ConsentComponentType - v2025.2.0



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "ConsentComponentTypeVS",
  "url" : "https://ths-greifswald.de/fhir/ValueSet/gics/ConsentComponentType",
  "version" : "2025.2.0",
  "name" : "ConsentComponentType",
  "status" : "active",
  "experimental" : false,
  "date" : "2025-06-12",
  "publisher" : "Independent Trusted Third Party of the University Medicine Greifswald",
  "contact" : [
    {
      "name" : "Independent Trusted Third Party of the University Medicine Greifswald",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://www.ths-greifswald.de/"
        }
      ]
    }
  ],
  "description" : "Types of consent components relevant to gICS for differentiation as a search criterion",
  "copyright" : "Copyright 2020-2025 Unabhängige Treuhandstelle der Universitätsmedizin Greifswald",
  "compose" : {
    "include" : [
      {
        "system" : "http://fhir.de/ConsentManagement/CodeSystem/QuestionnaireComponents"
      },
      {
        "system" : "https://ths-greifswald.de/fhir/CodeSystem/gics/ConsentComponentType"
      }
    ]
  }
}

```
