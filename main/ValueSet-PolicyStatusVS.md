# PolicyStatus - v2025.2.0



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "PolicyStatusVS",
  "url" : "https://ths-greifswald.de/fhir/ValueSet/gics/PolicyStatus",
  "version" : "2025.2.0",
  "name" : "PolicyStatus",
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
  "description" : "set of policy status states used for consent management",
  "copyright" : "Copyright 2020-2025 Unabhängige Treuhandstelle der Universitätsmedizin Greifswald",
  "compose" : {
    "include" : [
      {
        "valueSet" : ["http://hl7.org/fhir/ValueSet/consent-provision-type"]
      },
      {
        "system" : "http://terminology.hl7.org/CodeSystem/v3-NullFlavor",
        "concept" : [
          {
            "code" : "UNK"
          }
        ]
      }
    ]
  }
}

```
