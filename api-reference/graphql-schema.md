---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# GraphQL Schema

```graphql
type Query {
    RenovationAPI: RenovationAPI
    WaterTempsAPI: WaterTempsAPI
}

type RenovationAPI {
    Providers: [Provider]
    AddressInfo(streetName: String!, houseNumber: String!, postCode: String!, providerName: String): AddressInfo
    NextPickup(providerName: String!, AddressOrAddressId: String!, streetCode: String, countyID: String): [NextPickup]
    CollectionDates(providerName: String!, AddressOrAddressId: String!, streetCode: String, countyID: String): [CollectionDates]
}

type Provider {
    name: String
}

type AddressInfo {
    streetName: String
    houseNumber: String
    postCode: String
    streetCode: String
    countyId: String
    id: String
    providerName: String
}

type NextPickup {
    wasteType: String
    shortWasteType: String
    longWasteType: String
    date: String
}

type CollectionDates {
    wasteType: String
    shortWasteType: String
    longWasteType: String
    dates: [String]
}

type WaterTempsAPI {
    WaterTemperatures: [WaterTemperatures]
    WaterTemperature(id: String!): WaterTemperatures
}

type WaterTemperatures {
    id: String
    name: String
    kommune: String
    region: String
    lat: Float
    lon: Float
    temperature: Float
    time: String
    sourceDisplayName: String
}
```
