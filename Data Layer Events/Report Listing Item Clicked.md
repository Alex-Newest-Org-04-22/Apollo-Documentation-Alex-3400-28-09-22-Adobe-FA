# Report Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Report Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "itemPosition": <itemPosition>,
                "report": {
                    "reportID": "<reportID>"
                },
                "reportID": "<reportID>"
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingItemClicked.listing[n].itemPosition|integer|Integer position of a property within a sorted result. The first returned is position 1. For map results, this value can be the rank by distance from POI.|1, 2, 3, 4, 5||||0|||
|listingItemClicked.listing[n].report.reportID|string|Unique ID for a Report||||||||
|listingItemClicked.listing[n].reportID|string|Unique ID for a Report||||||||




