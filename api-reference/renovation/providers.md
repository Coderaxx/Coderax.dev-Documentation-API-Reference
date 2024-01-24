---
description: Returns a list of all supported renovation providers through the API.
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Providers

### Sample query

```graphql
query RenovationAPI {
    RenovationAPI {
        Providers {
            name
        }
    }
}
```

### Sample response

```graphql
{
  "data": {
    "RenovationAPI": {
      "Providers": [
        {
          "name": "Avfall Sør"
        },
        {
          "name": "BIR"
        },
        {
          "name": "FIAS"
        },
        {
          "name": "Follo Ren"
        },
        {
          "name": "Fosen Renovasjon"
        },
        {
          "name": "Fredrikstad Kommune"
        },
        {
          "name": "Glør"
        },
        {
          "name": "HIM"
        },
        {
          "name": "HRA"
        },
        {
          "name": "IRIS"
        },
        {
          "name": "IVAR Ryfylke"
        },
        {
          "name": "Innherred Renovasjon"
        },
        {
          "name": "MAREN"
        },
        {
          "name": "Min Renovasjon"
        },
        {
          "name": "Oslo Kommune"
        },
        {
          "name": "ReMidt"
        },
        {
          "name": "SHMIL"
        },
        {
          "name": "SIM"
        },
        {
          "name": "Sandnes Kommune"
        },
        {
          "name": "Stavanger Kommune"
        },
        {
          "name": "TRV"
        },
        {
          "name": "Time Kommune"
        }
      ]
    }
  }
}
```
