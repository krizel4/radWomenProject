*Duplicate Item*
* Hold new record in sObject
`String itemName = Item_Name__c;`
`String dupItemName = 'Duplicate';`
* Create a list `newStockItem` variable to hold data
* Create a For Loop using the list
  * Identify condition: if exists then, else add

---

*Deleting Stock Item*
* Empty case array to collect and to be added
* Loop through a SOQL query of stock items that hit zero
* If stock item is NOT zero, but it's deleted,
    * then, Create a case, alert owner with info of the itme, ID, stock amount, and when it was deleted in the description)
    * add cases to list
* Insert cases
* If stock item IS zero, delete.