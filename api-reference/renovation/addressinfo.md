---
description: >-
  Returns information about the specified address to provide to the
  CollectionDates method.
---

# AddressInfo

```graphql
query RenovationAPI {
    RenovationAPI {
        AddressInfo(streetName: "Storgata", houseNumber: "1", postCode: "0150") {
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
