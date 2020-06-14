---
unique-page-id: 11383953
description: Set Up Facebook Offline Conversions - Marketo Docs - Product Documentation
title: Set Up Facebook Offline Conversions
---

# Set Up Facebook Offline Conversions {#set-up-facebook-offline-conversions}

Set Up Facebook Offline Conversions - Marketo Docs - Product Documentation

By sending offline conversion data back to Facebook for people created via Lead Ads, your advertising team can optimize their ad spend better than ever. Here's how to set it up.

>[!NOTE]
>
>**Prerequisites**
>
>* You must [set up Facebook Lead Ads](set-up-facebook-lead-ads.md).
>* You must have an approved model in [Revenue Cycle Modeler](../../../../welcome-to-marketo-docs/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models.md).
>

### What's in this article? {#what-s-in-this-article}

[Admin Configuration](#setupfacebookofflineconversions-adminconfiguration)  
[Revenue Cycle Modeler Configuration](#setupfacebookofflineconversions-revenuecyclemodelerconfiguration)

#### Admin Configuration {#setupfacebookofflineconversions-adminconfiguration}

##### 1. Go to Marketo Admin. {#setupfacebookofflineconversions-gotomarketoadmin.}

![](assets/image2016-11-29-13-3a8-3a45.png)

##### 2. Go to LaunchPoint and double-click the Facebook Lead Ads service you created previously. {#setupfacebookofflineconversions-gotolaunchpointanddouble-clickthefacebookleadadsserviceyoucreatedpreviously.}

>[!NOTE]
>
>If you haven't done that, go ahead and [Set Up Facebook Lead Ads](set-up-facebook-lead-ads.md), then come back here.

![](assets/image2016-11-29-13-3a10-3a43.png)  

##### 3. If you like, edit the Display Name to include Offline Conversions. Click Next. {#setupfacebookofflineconversions-ifyoulike-editthedisplaynametoincludeofflineconversions.clicknext.}

![](assets/image2016-11-29-13-3a12-3a19.png)

##### 4. Check Enable Offline Conversions and click Next. {#setupfacebookofflineconversions-checkenableofflineconversionsandclicknext.}

![](assets/image2016-11-29-13-3a13-3a32.png)

##### 5. Click Next. {#setupfacebookofflineconversions-clicknext.}

![](assets/image2016-11-29-13-3a14-3a17.png)

##### 6. Click Save. {#setupfacebookofflineconversions-clicksave.}

![](assets/image2016-11-29-13-3a14-3a52.png)

Sweet! You're halfway done enabling Facebook Offline Conversions. Let's hop over to the Revenue Cycle Modeler to map the stages.

![](assets/image2016-11-29-13-3a16-3a55.png)

#### Revenue Cycle Modeler Configuration {#setupfacebookofflineconversions-revenuecyclemodelerconfiguration}

##### 1. Go to Analytics. {#setupfacebookofflineconversions-gotoanalytics.}

![](assets/image2016-11-29-13-3a29-3a23.png)

##### 2. Select your model and click Edit Draft. {#setupfacebookofflineconversions-selectyourmodelandclickeditdraft.}

![](assets/image2016-11-29-13-3a31-3a6.png)

>[!NOTE]
>
>Currently, there are 10 Facebook events you can map Revenue Cycle Stages to:
>
>* Adds of Payment Info
>* Adds to Cart
>* Adds to Wish List
>* Registrations Completed
>* Checkouts Initiated
>* Person
>* Other
>* Purchase
>* Searches
>* Content Views
>

##### 3. Select the stage you want to map, then from the Facebook Conversion drop-down, select the Facebook Event you want to map it to. Repeat this step to map all the stages in your RCM to offline conversion stages on Facebook. {#setupfacebookofflineconversions-selectthestageyouwanttomap-thenfromthefacebookconversiondrop-down-selectthefacebookeventyouwanttomapitto.repeatthissteptomapallthestagesinyourrcmtoofflineconversionstagesonfacebook.}

![](assets/1-1.png)

##### 4. When you're done mapping, close the model. {#setupfacebookofflineconversions-whenyou'redonemapping-closethemodel.}

![](assets/2.png)

##### 5. Approve your model and you're done! {#setupfacebookofflineconversions-approveyourmodelandyou'redone!}

![](assets/image2016-11-29-15-3a6-3a30.png)

Now, when Lead Ad leads reach the stages you mapped, the conversions are sent over to Facebook for reporting.

>[!CAUTION]
>
>Check your Facebook account and ensure that all [ads are associated](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&cmsid&creative=link&creative_detail=advertiser-help-center&create_type&destination_cms_id&orig_http_referrer) to the Marketo Offline Conversions Event Set. If they're not, ad attribution may not work.

>[!NOTE]
>
>Offline Conversion Data is sent from Marketo to Facebook several times daily.

>[!NOTE]
>
>**Related Articles**
>
>* [Understanding Facebook Offline Conversions](understanding-facebook-offline-conversions.md)
>
