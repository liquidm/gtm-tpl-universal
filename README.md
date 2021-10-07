## LiquidM Universal Pixel for Google Tag Manager

This pixel allows you to attribute conversions to campaigns and ads, run CPC+ campaigns and build audiences for retargeting. The description of attribution models is available in Platform Guide.

### CPC+ campaigns

CPC+ campaigns are based on complete view events. In order to track them add LiquidM Universal Pixel with the type `CPC+ Complete View Tracking` to all your landing pages. Please refer to LiquidM Platform Guide or https://liquidm.com/cpc-plus/ for further information.

### Conversion Tracking

Conversion Tracking requires two pixels to be implemented. For the first one add LiquidM Universal Pixel with the type `Conversion Tracking` and attribution type `Deferred Tracking (1st party cookies)` to all your pages. The second pixel needs to be added to the page where the conversion happens (e.g. checkout page). Add a pixel with the type `Conversion Tracking` and attribution type `Click token` to that page.

Please refer to the LiquidM Platform Guide in your account for further information.

### Retargeting segments

In order to retarget user who have visited your site or have converted (e.g. visited checkout page) add LiquidM Universal Pixel with the pixel type `Retargeting segments` and set Segment Token. Select the same segment in the Targeting section of your ad to retarget or exclude the audience. Please refer to the LiquidM Platform Guide for further information about retargeting.
