# identity resource type

The **identity** resource represents an identity of an _actor_. For example, and
actor can be a user, device, or application.

## Properties

| Property    | Type   | Description                                                                                                                                                                                                                                                                                                           |
|:------------|:-------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| displayName | String | The identity's display name. Note that this may not always be available or up to date. For example, if a user changes their display name, the API may show the new value in a future response, but the items associated with the user won't show up as having changed when using [find changes](../api/item_delta.md) |
| id          | String | Unique identifier for the identity.                                                                                                                                                                                                                                                                                   |

## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.identity"
}-->

```json
{
  "displayName": "string",
  "id": "string"
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "identity resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
