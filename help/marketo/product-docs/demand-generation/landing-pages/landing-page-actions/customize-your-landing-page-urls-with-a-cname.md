---
unique-page-id: 2359746
description: Customize Your Landing Page URLs with a CNAME - Marketo Docs - Product Documentation
title: Customize Your Landing Page URLs with a CNAME
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
---
# Customize Your Landing Page URLs with a CNAME {#customize-your-landing-page-urls-with-a-cname}

Even though Marketo hosts your landing pages, the URL can be totally customized. What it looks like without a CNAME:

`https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

The way it should look:

`https://go.YourCompany.com/UnsubscribePage.html`

## Choose a CNAME {#choose-a-cname}

Pick a word to go at the beginning of the URL for your landing pages. It's just one word and should be relatively short. Examples:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

The one word (plus YourCompany.com) is called a CNAME. You'll need this later so make a note of it.

## Find your Account String {#find-your-account-string}

1. Go to the **Admin** area and click on **Landing Pages**.

   ![](assets/image2014-9-18-16-3a2-3a45.png)

   >[!NOTE]
   >
   >**Admin Permissions Required**

1. Under the **Landing** **Pages** tab, copy the **Account** **String** from the **Settings** section.

   ![](assets/image2014-9-18-16-3a44-3a12.png)

1. You will need later also, so make a note of it.

## Send Request to IT {#send-request-to-it}

Ask your IT staff to setup the following CNAME: (Replace the word [CNAME] and [ACCOUNT STRING] with the text from the previous step.)

[CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

## Complete CNAME Setup {#complete-cname-setup}

1. Once your IT has created the CNAME, go to **Admin** and click on **Landing Pages**.

   ![](assets/image2014-9-18-17-3a15-3a11.png)

1. Under the **Settings** section, click on **Edit**.

   ![](assets/image2014-9-18-17-3a15-3a18.png)

1. Enter your CNAME in **Domain name for Landing Pages**, enter your **Fallback page**, enter your **Homepage** and click **Save**.

   ![](assets/image2014-9-18-17-3a15-3a25.png)

>[!NOTE]
>
>Your fallback page will be the page leads will get redirected to if your Marketo Landing Page is unavailable.

Nice job! Your landing pages are now branded with your company domain.
