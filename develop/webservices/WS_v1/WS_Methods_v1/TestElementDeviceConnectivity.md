---
uid: TestElementDeviceConnectivity
---

# TestElementDeviceConnectivity

This method allows you to test a connection to a device, without actually creating an element. Available from DataMiner 9.5.12 onwards.

## Input

| Item | Format | Description |
|--|--|--|
| Connection | String | The connection string. See [ConnectApp](xref:ConnectApp). |
| DmaID | Integer | The DataMiner Agent ID. |
| Configuration | [DMAElementConfiguration](xref:DMAElementConfiguration) | The element configuration for which the connection is to be tested. |

## Output

| Item | Format | Description |
|--|--|--|
| TestElementDevice­ConnectivityResult | Array of string | The result of the connection test, containing the connection state as well as any errors that were returned. |
