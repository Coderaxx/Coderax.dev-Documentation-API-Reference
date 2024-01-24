---
description: Returns a list with information on all registered water temperatures.
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

# WaterTemperatures

### Sample query

{% code fullWidth="false" %}
```graphql
query WaterTempsAPI {
    WaterTempsAPI {
        WaterTemperatures {
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
{% endcode %}

### Sample response

```graphql
{
  "data": {
    "WaterTempsAPI": {
      "WaterTemperatures": [
        {
          "id": "1-2802414",
          "name": "Flødevigen",
          "kommune": "Arendal",
          "region": "Agder",
          "lat": 58.42664,
          "lon": 8.75278,
          "temperature": 4.3,
          "time": "2024-01-24T10:04:00+01:00",
          "sourceDisplayName": "Automatisk registrering"
        },
        {
          "id": "1-7528",
          "name": "Stølsviga",
          "kommune": "Arendal",
          "region": "Agder",
          "lat": 58.4225,
          "lon": 8.77026,
          "temperature": 1,
          "time": "2024-01-20T10:00:00+01:00",
          "sourceDisplayName": null
        },
        
        #... rest of the list
```
