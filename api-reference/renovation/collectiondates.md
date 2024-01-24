---
description: Returns the next collection dates for each waste type.
---

# CollectionDates

```graphql
query RenovationAPI {
    RenovationAPI {
        CollectionDates(
            providerName: "Oslo kommune"
            AddressOrAddressId: "Storgata 1"
            addressName: null
            countyName: null
            countyID: null
            streetCode: null
        ) {
            wasteType
            date
            shortWasteType
            longWasteType
        }
    }
}
```
