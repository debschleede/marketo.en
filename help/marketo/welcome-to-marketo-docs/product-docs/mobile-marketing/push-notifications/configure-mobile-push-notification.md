---
unique-page-id: 7512454
description: Configure Mobile Push Notification - Marketo Docs - Product Documentation
title: Configure Mobile Push Notification
---

# Configure Mobile Push Notification {#configure-mobile-push-notification}

Configure Mobile Push Notification - Marketo Docs - Product Documentation

##### 1. Go to the Marketing Activities area. {#configuremobilepushnotification-gotothemarketingactivitiesarea.}

![](assets/2fbf1ab6-2247-40c8-980d-be56b9d94890.png)  

##### 2. Select your push asset and click Edit Draft. {#configuremobilepushnotification-selectyourpushassetandclickeditdraft.}

![](assets/image2016-8-23-16-3a49-3a48.png)  

##### 3. Go to Setup. {#configuremobilepushnotification-gotosetup.}

![](assets/image2016-8-23-16-3a51-3a56.png)  

##### 4. Select your desired app. Android and Apple platforms are enabled by default. {#configuremobilepushnotification-selectyourdesiredapp.androidandappleplatformsareenabledbydefault.}

![](assets/image2016-8-23-16-3a53-3a33.png) 

##### 5. If your Push message applies to only one platform (for example, cases for iPhones), then you can exclude the other platform by sliding its selector to Disabled.  {#configuremobilepushnotification-ifyourpushmessageappliestoonlyoneplatform(forexample-casesforiphones)-thenyoucanexcludetheotherplatformbyslidingitsselectortodisabled.}

![](assets/image2016-8-23-16-3a41-3a48.png)

##### 6. Click NEXT. {#configuremobilepushnotification-clicknext.}

![](assets/image2016-8-23-16-3a43-3a28.png)

##### 7. Enter message text or select the token icon to add tokens. Then, select a Tap Action. {#configuremobilepushnotification-entermessagetextorselectthetokenicontoaddtokens.then-selectatapaction.}

![](assets/image2015-9-14-16-3a7-3a43.png)

>[!NOTE]
>
>If a platform is enabled, it appears on the left side of the phone screen display. It displays in color when it's selected.

>[!NOTE]
>
>**Definition**
>
>There are three types of** Tap Actions:**
>
>**Launch App** - **This App** opens the home page of your app when the notification is tapped. **Custom** uses a deep link to open other areas of your app or any other app to which you have the link (see [Deep Link URIs](#ConfigureMobilePushNotification-Deeplink) below for details).
>
>**Landing Page** - takes you to a specified Marketo landing page.
>
>**External URL** - takes you to a non-Marketo landing page.

##### 8. To insert a deep link for a custom tap action, click Custom and enter the [deep link URI](#ConfigureMobilePushNotification-Deeplink) in the field. {#configuremobilepushnotification-toinsertadeeplinkforacustomtapaction-clickcustomandenterthedeeplinkuriinthefield.}

![](assets/image2016-7-28-16-3a19-3a13.png)

##### 9. To insert tokens, select a token, enter a default value, and click Insert. {#configuremobilepushnotification-toinserttokens-selectatoken-enteradefaultvalue-andclickinsert.}

>[!NOTE]
>
>Tokens appear where you place the cursor in the text box. You can use more than one token.

![](assets/image2015-8-10-14-3a48-3a52.png)

>[!NOTE]
>
>Messages and Tap Actions will look the same on both platforms.

##### 10. For iOS only, check the checkbox to tell the app to play a sound when the message arrives. Android plays the sound automatically. {#configuremobilepushnotification-foriosonly-checkthecheckboxtotelltheapptoplayasoundwhenthemessagearrives.androidplaysthesoundautomatically.}

![](assets/ios-tap-and-notification-hand.png)

##### 11. Preview the other platform and click FINISH. {#configuremobilepushnotification-previewtheotherplatformandclickfinish.}

![](assets/image2015-9-14-16-3a12-3a34.png)  

##### 12. Click APPROVE AND CLOSE. {#configuremobilepushnotification-clickapproveandclose.}

![](assets/323dda12-0543-4558-8562-563eed5fa0e0.png)

Congratulations! Now the push notification is ready to be sent.

#### Deep Link URIs {#configuremobilepushnotification-deeplinkdeeplinkuris}

When subscribers click on a button in a push message, it can take them either to your app’s home page or directly to a specific page within the app. A deep link is a unique reference to a specific page in your app, and looks a lot like a website link.

A deep link URI is made up of three parts: scheme name, path, and identifier. In the example below, “myappname” is the scheme. “products” is the path, and “purple-shirt” is the identifier. When the customer taps, they are taken specifically to the purple shirt item within your app’s product pages.

![](assets/image2016-7-29-12-3a49-3a1.png)

That said, your app’s deep link structure may be different from the above example. Your developer has many options in defining deep link URI’s, so ask your developer to send you the URIs (links) for the pages you are interested in using. This will ensure that the URIs you enter in push messages point to the right places. Your developer can [find more information here](http://developers.marketo.com/mobile/enabling-deep-links-in-your-app/).

>[!NOTE]
>
>**Related Articles**
>
>* [Send a Mobile Push Notification](send-a-mobile-push-notification.md)
>
