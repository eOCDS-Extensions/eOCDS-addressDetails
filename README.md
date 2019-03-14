## Background

In lot of cases we are facing with a lack of structured information regarding the address of party, place of performance, jurisdiction and so on. To achieve more detailed and (most important) structured description of such information, could something like this be considered as a possible extension of 'Address' object?

---

# AddressDetails

```
{
  "address": {
    "addressDetails": {
      "countryDetails": {
        "scheme": "iso-alpha2",
        "id": "UA",
        "description": "Ukraine",
        "url": ""
      },
      "regionDetails": {
        "scheme": "iso-alpha2",
        "id": "UA-12",
        "description": "Dnipropetrovska oblast",
        "url": ""
      },
      "localityDetails": {
        "scheme": "UN/LOCDE",
        "id":"UA-DNK",  
        "description": "Dnipro",
        "url": "https://service.unece.org/trade/locode/ua.htm"
      },
      "NUTSCode": "UA"
    }
  }
}
```
