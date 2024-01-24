---
description: Returns information registered water temperatures for specific station.
---

# WaterTemperature

### Sample query

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

### Sample response

```graphql
{
  "data": {
    "WaterTempsAPI": {
      "WaterTemperature": {
        "id": "1-2802414",
        "name": "Flødevigen",
        "kommune": "Arendal",
        "region": "Agder",
        "lat": 58.42664,
        "lon": 8.75278,
        "temperature": 4.3,
        "time": "2024-01-24T10:04:00+01:00",
        "sourceDisplayName": "Automatisk registrering"
      }
    }
  }
}
```
