---
layout: bidder
title: OppaMedia
description: OppaMedia Bidder Adaptor
biddercode: oppamedia
pbjs: true
pbs: false
media_types: banner, native, video
gvl_id: 14 (adkernel)
tcfeu_supported: true
usp_supported: true
coppa_supported: true
gpp_supported: true
pbs_app_supported: true
schain_supported: true
userIds: all
fpd_supported: true
prebid_member: false
ortb_blocking_supported: true
multiformat_supported: will-bid-on-one
floors_supported: true
aliasCode: adkernel
sidebarType: 1
---

### Note

The OppaMedia bidding adapter requires setup and approval before implementation. Please reach out to <b.li@oppa.media> for more details.

### Bid Params

{: .table .table-bordered .table-striped }
| Name     | Scope    | Description           | Example                   | Type     |
|----------|----------|-----------------------|---------------------------|----------|
| `host`   | required | Host | `'cpm.oppa.media'` | `string` |
| `zoneId` | required | Zone Id           | `30164`                 | `integer` |
