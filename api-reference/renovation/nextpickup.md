---
description: Returns the next collection dates for each waste type.
---

# NextPickup

### Sample query

```graphql
query RenovationAPI {
  RenovationAPI {
    NextPickup(
      AddressOrAddressId: "c1e27c6c-c7d0-4f3d-9fd0-2fbebcf602f0"
      providerName: "Stavanger kommune"
    ) {
      wasteType
      shortWasteType
      longWasteType
      date
    }
  }
}
```

### Sample response

```graphql
{
  "data": {
    "RenovationAPI": {
      "NextPickup": [
        {
          "wasteType": "general",
          "shortWasteType": "Rest",
          "longWasteType": "Restavfall",
          "date": "fredag 26. januar 2024"
        },
        {
          "wasteType": "bio",
          "shortWasteType": "Mat",
          "longWasteType": "Matavfall",
          "date": "fredag 2. februar 2024"
        },
        {
          "wasteType": "garden",
          "shortWasteType": "Hage",
          "longWasteType": "Hageavfall",
          "date": "fredag 2. februar 2024"
        },
        {
          "wasteType": "paper",
          "shortWasteType": "Papp",
          "longWasteType": "Papp/papir",
          "date": "fredag 9. februar 2024"
        }
      ]
    }
  }
}
```
