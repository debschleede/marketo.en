---
unique-page-id: 14352581
description: Throttling Errors - Marketo Docs - Product Documentation
title: Throttling Errors
exl-id: d0abb42a-731f-401c-bf2b-590493cfae80
---
# Throttling Errors {#throttling-errors}

## File Limit Reached {#file-limit-reached}

If you're sending through your own Server, it's going to have limitations for the number of emails you can send simultaneously. When sending through Sales Connect, you have the ability to send many emails, but we try to send them all at the same time. So if you're aware that your server is going to cut you off at 100 emails per minute, you will need to only send up to 100 emails through the [web application](https://toutapp.com/login). Otherwise, the emails can land here due to the emails being throttled in your server.

## Authentication Error {#authentication-error}

This means that we were unable to authenticate the connection to your SMTP server. Most likely, your password had changes recently and you just need to authenticate your new credentials.

To do this, go to your SMTP Settings where you should see the same error message. Update your credentials and hit **Authenticate and Save** to see a confirmation message.

Go into your Failed Deliveries to try resending those emails.
