# ConsentStatusWithdrawalFullValues - v2025.2.0



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "ConsentStatusWithdrawalFullValuesVS",
  "url" : "https://ths-greifswald.de/fhir/ValueSet/gics/ConsentStatusWithdrawalFullValues",
  "version" : "2025.2.0",
  "name" : "ConsentStatusWithdrawalFullValues",
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
  "description" : "consent states - subset WITHDRAWAL documents",
  "copyright" : "Copyright 2020-2025 Unabhängige Treuhandstelle der Universitätsmedizin Greifswald",
  "compose" : {
    "include" : [
      {
        "system" : "https://ths-greifswald.de/fhir/CodeSystem/gics/ConsentStatus",
        "concept" : [
          {
            "code" : "ACCEPTED"
          },
          {
            "code" : "WITHDRAWN"
          },
          {
            "code" : "NOT_ASKED"
          },
          {
            "code" : "NOT_CHOSEN"
          }
        ]
      }
    ]
  }
}

```
