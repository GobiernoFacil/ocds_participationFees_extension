# Participation Fees
Extend the tender properties to addinformation about the location and the cost of the bases for the tendering.

## Example

```
tender {
  participationFees : {
    value : {
      amount : 3500,
      currency : "MXN",
      paymentMethod : "transfer"
    },

    address : {
      countryName : "Mexico",
      postalCode : "74000",
      region : "Puebla",
      locality : "San Martín Texmelucan",
      streetAddress : "Salón de fiestas Lupita, jardines de Cocoyoc 21, Col. Valle de San Martín"
    },

    date : "2020-01-06T00:00:00"
  }
}
```
