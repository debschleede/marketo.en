---
unique-page-id: 2359644
description: Show Custom HTML Form for Known People - Marketo Docs - Product Documentation
title: Show Custom HTML Form for Known People
---

# Show Custom HTML Form for Known People {#show-custom-html-form-for-known-people}

Show Custom HTML Form for Known People - Marketo Docs - Product Documentation

If a visitor is cookied (known person who provided an email address in the past), then why bother with the form? Just give them the download button. Here's how.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

1. Go to **Marketing** **Activities**.

   ![](assets/login-marketing-activities-5.png)

1. Under **Marketing** **Activities**, select your form and click **Edit** **Form**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Under **Form** **Settings**, click on **Settings**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Set If **Known** **Visitor, Show**: to **Custom** **HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Click the ![--](assets/image2014-9-25-14-3a1-3a26.png) to edit the **Custom** **HTML** that will be shown to known people.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. There's some default content, but feel free to change it up.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Available tokens:

   | Token |Description |
   |---|---|
   | {{lead.FirstName}} |This will display the person's first name. |
   | {{lead.LastName}} |This will display the person's last name. |
   | {{form.Button:default=Download}} |This will display the form button. Replace the area after the **=** to change the button text. |
   | {{form.NotYou:default=Not you?}} |This will display a link in case the person is someone else. Replace the area after the **=** to change the link text. |

   >[!CAUTION]
   >
   >Only the four tokens above can be used. Any other token will not work here.

1. Click **Finish**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Click **Approve and Close**.

   >[!NOTE]
   >
   >The form must be approved to be used on landing pages.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >`Remember to` [approve the landing page draft](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) `created by the form changes.`

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >You can direct the click of the button to the asset by setting the form follow-up page to the file's URL.

Piece of cake! Check out what a person would see if they came back to the same form: 