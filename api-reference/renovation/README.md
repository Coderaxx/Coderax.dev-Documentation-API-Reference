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

# 🗑 RenovationAPI Reference

Welcome to RenovationAPI, a powerful and flexible GraphQL API solution designed to provide detailed and up-to-date information on waste collection services. This API is developed to facilitate easy access to various types of waste collection data, including schedules, types, and provider details.

### Key Features of RenovationAPI

* **Comprehensive Data Access:** RenovationAPI offers access to a wide range of data related to waste collection, including collection dates, types of waste, and provider information.
* **GraphQL Interface:** Utilizing GraphQL, the API provides a flexible query language that allows users to request exactly the data they need, reducing overhead and improving performance.
* **Multiple Providers:** The API integrates data from various waste collection providers, offering a unified interface for retrieving information across different regions and services.

### Getting Started

To start using RenovationAPI, you'll need to familiarize yourself with GraphQL queries. The API is structured to provide intuitive access to data, with clear and concise query structures.

#### Basic Query Structure

Here's a basic example of a query to fetch waste collection dates:

```graphql
graphql query {
  RenovationAPI {
    CollectionDates(providerName: "ProviderName", AddressOrAddressId: "YourAddress") {
      wasteType
      dates
    }
  }
}
```

This query will return the collection dates for the specified provider and address.

#### Exploring the Schema

The API's schema is designed to be self-explanatory, with clear type definitions and query structures. You can explore the schema [here](../graphql-schema.md) for a detailed understanding of the available queries and types.

### Documentation and Support

For more detailed information on using RenovationAPI, including advanced queries and handling responses, please refer to our comprehensive documentation. If you encounter any issues or have questions, feel free to reach out for support.
