---
layout: backlog
title: v4 RET - UI2 My-downloads page
kanCategory: test
kanSubCategory: pending
kanAssigned: UKMO
kanBacklog: 80
kanIssue:
kanPullReq:
kanFeature: Retrieval
kanRelease: 4.0
kanMetric: 5.2
kanSize: 5
kanPriority: 2
kanRepo: OpenWIS/openwis4
kanProject:
---
Enhancement UI2: My-downloads page.

Update - scrum - 2016-11-17: GT - Migrated into new v4.0 as part of Kanban 81. v4 - Refactoring to improve modularity.

---

This task was part of the OpenWISv4/GeoNetworksv3 [work package][WP] assigned to GeoCat in 2015.  The [documentation][doc] produced as part of that work describes the new functionality delivered.

[WP]: {{ site.baseurl | prepend: site.url }}/assets/OpenWISv4-GeoNetwork-2015-Workpackage.pdf
[doc]: {{ site.baseurl | prepend: site.url }}/assets/OpenWISv4-GeoNetwork-2015-Documentation.pdf

The outcome for this feature was:

2015 status: **MO/GeoCat Review**; Percent complete: **0**; Priority: Normal; Questions outstanding: 100% or 0% Done? In the manual, does 'redirect the user to the Users and Groups section of the admin console' really mean that, or just that identical functionality exists in the User Portal and Admin Portal?;

Extra info:

GeoNetwork shall be amended to provide users with a web-based mechanism to:

  1. monitor the status of their active downloads;
  2. discard requests that are no longer required;
  3. browse their download history; and
  4. retrieve packaged data products from the Staging Post if they are still available.

The RequestService and ProcessedRequestService SOAP web-services provide for retrieval and persistence of the request and process-request objects.
Details of active downloads should automatically be refreshed.
