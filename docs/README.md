# Zendesk Chat

This app provides a storefront widget for the [Zendesk](https://zendesk.com/) chat functionality to comunicate with your store's customers while they navigate your store.

## Before you start

To use the chat you need to have an active [Zendesk](https://zendesk.com/) account. Some features are only available for specific plans.

## Installation

1. Open the VTEX App Store and install the [Zendesk Chat](https://apps.vtex.com/vtex-zendesk-chat/p) app on your store.
2. On VTEX Admin, go to **Extensions Hub > App Management** and click the Zendesk Chat app settings.
3. Fill in your Zendesk Chat's Account Key, which you can find on Zendesk following [these instructions](https://support.zendesk.com/hc/en-us/articles/4408825772698-How-do-I-find-my-Chat-Account-Key-).
4. Click `Save`.
5. Copy the following script and insert it into your website's HTML source code between the `<head>` tags. This code must be inserted into every page where you want to display the Web Widget.

   ```html
   <script id="ze-snippet" src="https://static.zdassets.com/ekr/snippet.js?key=xxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxxx> </script>
   ```
> Replace the key value, i.e. `xxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`, according to your scenario.
