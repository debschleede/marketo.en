---
unique-page-id: 11376159
description: Before You Create Push Notifications and In-App Messages - Marketo Docs - Product Documentation
title: Before You Create Push Notifications and In-App Messages
---

# Before You Create Push Notifications and In-App Messages {#before-you-create-push-notifications-and-in-app-messages}

Before You Create Push Notifications and In-App Messages - Marketo Docs - Product Documentation

Creating push notifications and in-app messages isn't difficult, but you need to have everything ready before you can start. The Marketo Admin and mobile app developer should follow the steps below to&nbsp;prepare the necessary integrations.

##### 1. First, the Marketo Admin [adds a mobile app](welcome-to-marketo-docs/product-docs/mobile-marketing/admin-(mobile-marketing)/add-a-mobile-app.md) {#beforeyoucreatepushnotificationsandin-appmessages-first-themarketoadminaddsamobileapp}

##### 2. The Marketo Admin then [sends a code snippet to the developer](welcome-to-marketo-docs/product-docs/mobile-marketing/admin-(mobile-marketing)/send-sdk-code-to-a-developer.md) {#beforeyoucreatepushnotificationsandin-appmessages-themarketoadminthensendsacodesnippettothedeveloper}

##### 3. The developer downloads the SDK, and includes snippet and other methods, for [Android](http://developers.marketo.com/documentation/mobile/installation-instructions-on-android/) or [iOS](http://developers.marketo.com/documentation/mobile/installation-instructions-on-ios/) {#beforeyoucreatepushnotificationsandin-appmessages-thedeveloperdownloadsthesdk-andincludessnippetandothermethods-forandroidorios}

##### 4. By default, in-app messages are triggered when your app opens. If you want to trigger messages for other events, such as when a particular page is viewed or a specific button is pushed, the developer needs to add custom events to the code (see [Custom Events for In-App Messages](#BeforeYouCreatePushNotificationsandIn-AppMessages-CustomEvents) below) {#beforeyoucreatepushnotificationsandin-appmessages-bydefault-in-appmessagesaretriggeredwhenyourappopens.ifyouwanttotriggermessagesforotherevents-suchaswhenaparticularpageisviewedoraspecificbuttonispushed-thedeveloperneedstoaddcustomeventstothecode(seecusto}

##### 5. The developer [generates the Server API key and project number for Android](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-android/) or [the certification and password for iOS](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-ios/) and sends it to the Marketo Admin {#beforeyoucreatepushnotificationsandin-appmessages-thedevelopergeneratestheserverapikeyandprojectnumberforandroidorthecertificationandpasswordforiosandsendsittothemarketoadmin}

##### 6. The Marketo Admin configures push notification access [with the Server API key (Android)](welcome-to-marketo-docs/product-docs/mobile-marketing/admin-(mobile-marketing)/configure-mobile-app-android-push-access.md) or [with the certificate (iOS)](welcome-to-marketo-docs/product-docs/mobile-marketing/admin-(mobile-marketing)/configure-mobile-app-ios-push-access.md)  {#beforeyoucreatepushnotificationsandin-appmessages-themarketoadminconfigurespushnotificationaccesswiththeserverapikey(android)orwiththecertificate(ios)}

>[!TIP]
>
>It's easy for a Marketo Admin to check to see if your push configuration is verified. Just go [here](welcome-to-marketo-docs/product-docs/mobile-marketing/admin-(mobile-marketing)/verify-push-configuration.md).

#### Custom Events for In-App Messages {#beforeyoucreatepushnotificationsandin-appmessages-customeventscustomeventsforin-appmessages}

`For in-app messaging, the display trigger is set to **App Open** by default. If you want to use any custom events to trigger the display of in-app messages (for example, **Clicks Add to Cart**, **Views Settings Page**), create a list of desired events and give it to your mobile apps developer. The developer will then add the custom events into the code. After they are approved, they appear as display triggers when setting up your audience.`**Caution** `: The custom event coding approval process may take some time to complete.`

After you've got all of your preparation done for in-app messages and push notifications, it's time to get started!

>[!NOTE]
>
>**Related Articles**
>
>* [Create an In-App Message](../../../../welcome-to-marketo-docs/product-docs/mobile-marketing/in-app-messages/create-an-in-app-message.md)
>
>* [Create a Push Notification](../../../../welcome-to-marketo-docs/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)
>
