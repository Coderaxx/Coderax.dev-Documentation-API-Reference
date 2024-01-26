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

# 🏖 WaterTempsAPI Reference

Welcome to WaterTempsAPI, an innovative GraphQL API designed to provide real-time data on water temperatures from various locations. This API is tailored for users who need accurate and timely information about water temperatures for activities like swimming, fishing, or environmental monitoring.

### Key Features of WaterTempsAPI

* **Real-Time Data:** Access up-to-date water temperature readings from a variety of locations.
* **Historical Data:** Retrieve past temperature records to analyze trends and patterns.
* **Wide Coverage:** The API includes data from multiple regions, offering a comprehensive view of water temperatures in different areas.
* **GraphQL Flexibility:** Utilize the power of GraphQL to make precise queries, fetching only the data you need.

### Getting Started

To begin using WaterTempsAPI, you should be familiar with the basics of GraphQL queries. The API is structured to allow easy and intuitive access to water temperature data.

#### Basic Query Example

Here's a simple example of how to query the current water temperature for a specific location:

```graphql
query {
  WaterTempsAPI {
    WaterTemperature(id: "LocationID") {
      name
      temperature
      time
    }
  }
}
```

This query will return the latest water temperature reading for the specified location ID.

#### Exploring the Schema

The API's schema is designed to be user-friendly, with clear definitions for types and queries. You can explore the schema [here](../graphql-schema.md) to understand the full range of queries and data types available.

### Documentation and Support

For more comprehensive information on how to use WaterTempsAPI, including advanced query techniques and response handling, please refer to our detailed documentation. Should you have any questions or encounter issues, our support team is available to assist you.
