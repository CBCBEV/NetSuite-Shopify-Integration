<img src="images/favicon-image.png" align="right" width="120" height="120"/>

# Items (Export to Shopify)
### CBC Specialty Beverage

When creating **New** items or editing _existing_ _items_ it is important to check, fill a few NetSuite fields required in order to export items to Shopify. It is possible to encounter items that only exist in NetSuite and not in Shopify. 

### How does it work?

The integrator/connector relies on a list of data that is given from a NetSuite saved search, the connector runs on user action (click of a button) or on a scheduled basis. In our case we have this connector set to run on the following:

```
(GMT-06:00) Central Time (US & Canada)
Frequency: Once Weekly
Start Time: 6:10 AM
Runs on this day: Friday
```

**Please note: This may change at any time.**

## Item Criteria (Must):

- Item must be one of the following:
    - Inventory Item
    - Kit/Package
    - Assembly/Bill of Materials

- Item must be: **Active**

- Price Level: Base Price (must have a value at that pricing level)

## Important Item Fields:

_Found under the **eTail** subtab in NetSuite_

- Etail Channel (2):  **Shopify**
- Shopify Enable Out Of Stock Selling: ✅
- Shopify Stores: **CBC Specialty Beverage**
- Shopify Product Visibility: **Online Store**


## Main Process:

- NetSuite Saved Search:
    ``` Celigo Shopify Item Export  [CBC Specialty Beverage]```
    -   Note: Please Do Not Make Any Changes to the Saved Search :)
- Meeting the all the criteria and having the fields correctly will result in the item being listed under the _Item_ _Export_ saved search. 
- The following schedule or the Friday morning of the current week, the item will be exported to Shopify and it only takes 2-3 minutes before it shows up in the store. 

If you run into any issues and the item does not show up in Shopify after following all the instructions please send an email to jromualdo@cbcbev.com

### Diagram:


<img src="images/diagram.png" width="100%" height="60%"/>
