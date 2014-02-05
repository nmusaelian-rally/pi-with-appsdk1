pi-with-appsdk1
===============
1.33 is the latest version of AppSDK1.x
If you want to access Portfolio Items or Blocked Reason, or any other feature introduced in later versions of WS API up to 1.43 this syntax will allow it:

<script type="text/javascript" src="/apps/1.33/sdk.js?apiVersion=1.43"></script>

This has to be used with caution. One thing that definitely will break is around calculations of timebox start and end dates.  That's why many legacy Rally App Catalog apps are still at 1.29.
This is due to changes in API Version 1.30. See API versioning section in the WS API documentation:
https://rally1.rallydev.com/slm/doc/webservice/versioning.jsp

Note that this method does not work with v2.0 of WS API.
