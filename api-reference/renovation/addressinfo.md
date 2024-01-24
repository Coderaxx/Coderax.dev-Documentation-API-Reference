---
description: >-
  Returns information about the specified address to provide to the
  CollectionDates method.
---

# AddressInfo

### Sample query

```graphql
query RenovationAPI {
    RenovationAPI {
        AddressInfo(streetName: "Muségata", houseNumber: "40", postCode: "4010") {
            streetName
            houseNumber
            postCode
            streetCode
            countyId
            id
            providerName
        }
    }
}
```

### Sample response

```graphql
{
  "data": {
    "RenovationAPI": {
      "AddressInfo": {
        "streetName": "Muségata",
        "houseNumber": "40",
        "postCode": "4010",
        "streetCode": "1677",
        "countyId": "1103",
        "id": "c1e27c6c-c7d0-4f3d-9fd0-2fbebcf602f0",
        "providerName": "Stavanger kommune"
      }
    }
  }
}
```
