---
unique-page-id: 2359793
description: Use Emails in Social Promotions - Marketo Docs - Product Documentation
title: Use Emails in Social Promotions
---

# Use Emails in Social Promotions {#use-emails-in-social-promotions}

Use Emails in Social Promotions - Marketo Docs - Product Documentation

When you create a [referral offer](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) or a [sweepstakes](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), you can include emails to send when the person signs up, and again when the person has won the reward.

>[!TIP]
>
>`To create an email, see` [Send an Email Blast](../../../../../welcome-to-marketo-docs/getting-started/quick-wins/send-an-email.md) `.`

In the emails, use these tokens:

* **Sign-up email**: Use **{{social.Share Url}}** to send each participating person a personalized share link.

* **Fulfillment email**: Use **{{social.Promo Code}}** to send each winner a [promo code](use-promo-codes-for-offer-fulfillment.md).

>[!NOTE]
>
>**Prerequisites**
>
>`Before you can add an email to a social app, it must be`*operational* `and`*approved* `. See` [Edit Settings for an Email](../../../../../welcome-to-marketo-docs/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) `.`

1. Go to **Marketing Activities**.

   ![](assets/ma.png)

1. Select the app, and click **Edit Draft**.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. In the social app editor, go to **App Settings > Offer Details** ` (or **Sweepstakes Details**)`.

   ![](assets/image2014-9-19-16-3a12-3a41.png)

   ##### Add the sign-up email. {#useemailsinsocialpromotions-addthesign-upemail.}

   ![](assets/image2014-9-19-16-3a12-3a49.png)

   >[!NOTE]
   >
   >The confirmation email is sent automatically when a person signs up.

   ##### Add the fulfillment email. {#useemailsinsocialpromotions-addthefulfillmentemail.}

   ![](assets/image2014-9-19-16-3a15-3a26.png)

1. In a referral offer, choose whether the fulfillment email is sent automatically or manually.

   ![](assets/image2014-9-19-16-3a15-3a36.png)

>[!NOTE]
>
>`In a sweepstakes, the fulfillment email is always sent automatically when you` [select the winner](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md) `.`

>[!NOTE]
>
>**Definition**
>
>* **auto on goal**: The fulfillment email is sent automatically as each participant meets the goal.
>* **manually send**: Once people start meeting the goal, return to your referral offer to manually [send the fulfillment email](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>

>[!NOTE]
>
>**Related Articles**
>
>Next, you can [choose the share URL](choose-the-share-url-for-a-social-app.md) or, in your referral offer, you can [upload the promo codes](use-promo-codes-for-offer-fulfillment.md) you will send out.
