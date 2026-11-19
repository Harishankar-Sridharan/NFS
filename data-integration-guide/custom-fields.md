---
description: Free fields of the entities, typologies, and displayed labels.
---

# Custom fields

Most entities have free fields to carry customer-specific data. Their number depends on the entity; for the customer, the appointment, and the resource, you notably find:

| Fields | Type | Number (customer) |
| --- | --- | --- |
| FILLER1 … FILLER5 | Text | 5 |
| QUANTITY1 … QUANTITY5 | Decimal number | 5 |
| EXTRAFILLER1 … EXTRAFILLERn | Text | 50 |
| EXTRAQUANTITY1 … EXTRAQUANTITY15 | Decimal number | 15 |
| EXTRALOGICAL1 … EXTRALOGICAL15 | Boolean | 15 |
| EXTRADATE1 … EXTRADATE15 | Date | 15 |
| EXTRADATETIME1 … EXTRADATETIME15 | Date-time | 15 |

The exact number of fields of each entity is given in the [exchange model reference](exchange-model-reference.md).

## Coded value lists (typologies)

A text field can be associated with a typology (Typology entity): a list of codes and labels. On import, a FILLERn.CODE or EXTRAFILLERn.CODE column receives a code, which is converted into a label; on export, the reverse conversion is applied. An unknown code results in an empty value.

## Displayed labels

The labels of the custom fields in the interface and in the export headers with labels come from the application's resource files, which can be overridden per instance. The technical name of the field (FILLER1, EXTRAFILLER3…) remains the one to use in exchanges.

Previous: [Integration APIs and web services](integration-apis-and-web-services.md)

Next: [Data validation and error handling](data-validation-and-error-handling.md)
