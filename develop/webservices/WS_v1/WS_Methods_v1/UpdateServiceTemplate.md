---
uid: UpdateServiceTemplate
---

# UpdateServiceTemplate

Use this method to update an existing service template. Available from DataMiner 10.2.1/10.3.0 onwards.

## Input

| Item | Format | Description |
|--|--|--|
| Connection | String | The connection string. See [ConnectApp](xref:ConnectApp). |
| DmaID | Integer | The DataMiner Agent ID. |
| ServiceTemplateID | Integer | The service template ID. |
| ViewIDs | Array of Integer | The IDs of the views in which the service template should be created. |
| Template | [DMAServiceTemplate](xref:DMAServiceTemplate) | The service template configuration. |
| ExtraOptions.AutoUpdateExistingServices | Boolean | Indicates whether existing services generated with the service template should be updated automatically. |

## Output

None.
