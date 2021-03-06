---
layout: backlog
title: v4 SYS - ADMIN5 Configure dissemination channels for Groups
kanCategory: test
kanSubCategory: pending
kanAssigned: UKMO
kanBacklog: 69
kanIssue:
kanPullReq:
kanFeature: System Admin
kanRelease: 4.0
kanMetric: 5.2
kanSize: 5
kanPriority: 3
kanRepo: OpenWIS/openwis4
kanProject:
---
Enhancement ADMIN5: Configure dissemination channels for Groups.

Update - scrum - 2016-11-17: GT - Migrated into new v4.0 as part of Kanban 81. v4 - Refactoring to improve modularity.

---

This task was part of the OpenWISv4/GeoNetworksv3 [work package][WP] assigned to GeoCat in 2015.  The [documentation][doc] produced as part of that work describes the new functionality delivered.

[WP]: {{ site.baseurl | prepend: site.url }}/assets/OpenWISv4-GeoNetwork-2015-Workpackage.pdf
[doc]: {{ site.baseurl | prepend: site.url }}/assets/OpenWISv4-GeoNetwork-2015-Documentation.pdf

The outcome for this feature was:

2015 status: **MO Test**; Percent complete: **100**; Priority: Normal; Questions outstanding: nil;

Extra info:

An OpenWIS deployment will provide a number of channels for disseminating data products to users via subscription or ad-hoc delivery request (e.g. email, FTP etc.).
The available dissemination channels shall be specified in as configuration items.

GeoNetwork shall be amended such that a User Administrator can assign to a Group the permission to use a dissemination channel. A Group may be permitted to use multiple dissemination channels. At a minimum, all Groups are permitted to disseminate data products via Staging Post- in which case an email notification is generated indicating the URL of the data product that has been generated.
