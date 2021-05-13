# User Subscribed

## Javascript Code
```js
window.appEventData1305RL = window.appEventData1305RL || [];
appEventData1305RL.push({
  "event": "User Subscribed",
    "subscription": {
        "subscriptionType": "<subscriptionType>"
    },
    "user": {
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|profileAttributesList|string|A twice delimited string of key / value pairs.  Use ~ between key and value.  Use | between pairs|homeStore~234|loyaltyTier~gold|memberSince~2002|||||||
|subscriptionType|string|Describes the type of subscription. |news, updates, sales, events|||||||
