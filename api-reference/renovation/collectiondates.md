---
description: Returns the next collection dates for each waste type.
---

# CollectionDates

### Sample query

```graphql
query RenovationAPI {
  RenovationAPI {
    CollectionDates(
      AddressOrAddressId: "c1e27c6c-c7d0-4f3d-9fd0-2fbebcf602f0"
      providerName: "Stavanger kommune"
    ) {
      wasteType
      shortWasteType
      longWasteType
      dates
    }
  }
}
```

### Sample response

```graphql
{
  "data": {
    "RenovationAPI": {
      "CollectionDates": [
        {
          "wasteType": "general",
          "shortWasteType": "Rest",
          "longWasteType": "Restavfall",
          "dates": [
            "fredag 26. januar 2024",
            "fredag 9. februar 2024",
            "fredag 23. februar 2024",
            "fredag 8. mars 2024",
            "fredag 22. mars 2024",
            "fredag 5. april 2024",
            "fredag 19. april 2024",
            "fredag 3. mai 2024",
            "torsdag 16. mai 2024",
            "fredag 31. mai 2024",
            "fredag 14. juni 2024",
            "fredag 28. juni 2024",
            "fredag 12. juli 2024",
            "fredag 26. juli 2024",
            "fredag 9. august 2024",
            "fredag 23. august 2024",
            "fredag 6. september 2024",
            "fredag 20. september 2024",
            "fredag 4. oktober 2024",
            "fredag 18. oktober 2024",
            "fredag 1. november 2024",
            "fredag 15. november 2024",
            "fredag 29. november 2024",
            "fredag 13. desember 2024",
            "fredag 27. desember 2024"
          ]
        },
        {
          "wasteType": "bio",
          "shortWasteType": "Mat",
          "longWasteType": "Matavfall",
          "dates": [
            "fredag 2. februar 2024",
            "fredag 16. februar 2024",
            "fredag 1. mars 2024",
            "fredag 15. mars 2024",
            "onsdag 27. mars 2024",
            "fredag 12. april 2024",
            "fredag 26. april 2024",
            "fredag 10. mai 2024",
            "fredag 24. mai 2024",
            "fredag 7. juni 2024",
            "fredag 21. juni 2024",
            "fredag 5. juli 2024",
            "fredag 19. juli 2024",
            "fredag 2. august 2024",
            "fredag 16. august 2024",
            "fredag 30. august 2024",
            "fredag 13. september 2024",
            "fredag 27. september 2024",
            "fredag 11. oktober 2024",
            "fredag 25. oktober 2024",
            "fredag 8. november 2024",
            "fredag 22. november 2024",
            "fredag 6. desember 2024",
            "fredag 20. desember 2024"
          ]
        },
        {
          "wasteType": "garden",
          "shortWasteType": "Hage",
          "longWasteType": "Hageavfall",
          "dates": [
            "fredag 2. februar 2024",
            "fredag 16. februar 2024",
            "fredag 1. mars 2024",
            "fredag 15. mars 2024",
            "onsdag 27. mars 2024",
            "fredag 12. april 2024",
            "fredag 26. april 2024",
            "fredag 10. mai 2024",
            "fredag 24. mai 2024",
            "fredag 7. juni 2024",
            "fredag 21. juni 2024",
            "fredag 5. juli 2024",
            "fredag 19. juli 2024",
            "fredag 2. august 2024",
            "fredag 16. august 2024",
            "fredag 30. august 2024",
            "fredag 13. september 2024",
            "fredag 27. september 2024",
            "fredag 11. oktober 2024",
            "fredag 25. oktober 2024",
            "fredag 8. november 2024",
            "fredag 22. november 2024",
            "fredag 6. desember 2024",
            "fredag 20. desember 2024"
          ]
        },
        {
          "wasteType": "paper",
          "shortWasteType": "Papp",
          "longWasteType": "Papp/papir",
          "dates": [
            "fredag 9. februar 2024",
            "fredag 8. mars 2024",
            "fredag 5. april 2024",
            "fredag 3. mai 2024",
            "fredag 31. mai 2024",
            "fredag 28. juni 2024",
            "fredag 26. juli 2024",
            "fredag 23. august 2024",
            "fredag 20. september 2024",
            "fredag 18. oktober 2024",
            "fredag 15. november 2024",
            "fredag 13. desember 2024"
          ]
        }
      ]
    }
  }
}
```
