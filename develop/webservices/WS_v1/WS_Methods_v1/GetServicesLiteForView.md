---
uid: GetServicesLiteForView
---

# GetServicesLiteForView

Use this method to retrieve basic information on all the services in a particular view.

This method is a faster alternative to the method *GetServicesForView*, as it retrieves only basic information about the services. See [GetServicesForView](xref:GetServicesForView).

## Input

| Item            | Format  | Description                                                                      |
|-----------------|---------|----------------------------------------------------------------------------------|
| Connection      | String  | The connection ID. See [ConnectApp](xref:ConnectApp). |
| ViewID          | Integer | The view ID.                                                                     |
| IncludeSubViews | Boolean | Whether the subviews of the specified view should be included in the search.     |

## Output

| Item | Format | Description |
|--|--|--|
| GetServicesLiteFor­ViewResult | Array of [DMAElementLite](xref:DMAElementLite) | A list with basic info about all the services in the specified view. |
