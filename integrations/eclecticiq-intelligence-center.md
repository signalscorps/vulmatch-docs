---
description: >-
  Ingest threat intelligence from Vulmatch into the EclecticIQ Intelligence
  Center.
---

# EclecticIQ Intelligence Center

### Prerequisites

[A Vulmatch plan that supports use of our API.](https://www.vulmatch.com/pricing/)

### Setup

1. Navigate to the incoming feed setup page
2. Select add new feed
3. You can set most fields as you wish, the key ones are
   1. **Transport type:** TAXII 2.1 poll
   2. **Content type:** STIX 2.1
   3. **API Root URL:** https://app.vulmatch.com/taxii/taxii2/YOUR-GROUP-UUID _(_YOUR-GROUP-UUID [_can be obtained on the Group Management page in the Vulmatch web app_](https://app.vulmatch.com/user/manage\_group)_.)_
   4. **Collection ID:** YOUR-GROUP-UUID
   5. **Username:** Vulmatch username
   6. **Password:** Vulmatch API key
   7. **Added after:** _should be no more than 7 days_ because our TAXII feed does not return any more data than this
   8. **Objects per run (max):** 50
   9. **Download time frame:** advancing

### Usage

Once incoming feed is enabled, the ingested threat intelligence can be used in the EclecticIQ Intelligence Center.
