---
description: Returns information registered water temperatures for specific station.
---

# WaterTemperature

```graphql
query WaterTempsAPI {
    WaterTempsAPI {
        WaterTemperature(id: "1-2802414") {
            id
            name
            kommune
            region
            lat
            lon
            temperature
            time
            sourceDisplayName
        }
    }
}
```
