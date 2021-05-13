# CTA Link Clicked

## Javascript Code
```js
window.appEventData1305RL = window.appEventData1305RL || [];
appEventData1305RL.push({
  "event": "CTA Link Clicked",
    "linkInfo": {
        "linkContainer": "<linkContainer>",
        "linkId": "<linkId>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkContainer|string|Indicates the container for a clicked link within the hierarchy [Site > Page > Region > Container > linkID]|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
