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

{% code lineNumbers="true" fullWidth="false" %}
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
