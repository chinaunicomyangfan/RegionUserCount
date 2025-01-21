# RegionDeviceCount API User Story - Emergency Rescue

| **Item** | **Details** |
| ---- | ------- |
| ***Summary*** | As an emergency rescue worker, I hope to be able to obtain the number of users in an area where a special emergency activities could be needed through an API, so as to quickly understand the situation, plan and guide the rescue work..Here is my requirements.<br>•I hope to obtain the number of connected devices on people in the area by providing coordinates or boundary information.<br>•I need the information returned by the API to include the total number and distribution of the devices in that area.<br>•I need to obtain real-time information|
| ***Roles, Actors and Scope*** | **Roles:**  API Customer: emergency rescue worker. <br> API Provider:Communication Service Provider (CSP).  <br> **Scope:** Returns the real-time number of devices in a specific area through an API |
| ***Pre-conditions*** |The preconditions are listed below:<br><ol><li>The Customer has been onboarded to the CSP's API platform.</li><li>The Customer has successfully subscribed to the RegionDeviceCount product from the product catalog.</li><li>The means to get the access token are known to the API Customer to ensure secure access of the API.|
| ***Activities/Steps*** | **Starts when:** API Customer initiate requests to query the number of devices in a certain area <br>**Ends when:** CSP returns the number of devices in the area to the API Customer. |
| ***Post-conditions*** | CSP returns accurate statistical results, and emergency rescue worker.can quickly locate key rescue areas based on results.|
| ***Exceptions*** | Several exceptions might occur during the RegionDeviceCount API operations<br>- Unauthorized: Not valid credentials (e.g. use of already expired access token).<br>- Invalid input: Not valid input data to invoke operation (e.g.Area format error, or inability to obtain valid data within the area).<br>|
