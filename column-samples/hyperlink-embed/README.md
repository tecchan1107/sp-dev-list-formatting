# Displaying Embedded Content Using the `embed` Action

## Summary

This sample demonstrates displaying embedded content using the `embed` action.

![screenshot of the sample](./assets/screenshot.png)

> [!NOTE]  
> - This action is only available in the newer version of the Microsoft Lists App.
> - The `embed` action is not available in the Document Library or List Web Part.

## Prerequisites

### Allowing Embedding in HTML Field Security

To embed content, the target site must be allowed for embedding. For guidance on how to allow embedding, please refer to [Allow or restrict the ability to embed content on SharePoint Lists using custom formatters](https://go.microsoft.com/fwlink/p/?linkid=2258033).

If you try to embed a site that is not allowed to be embedded, the following error screen will appear:

![screenshot of the error screen when target site is not allowed to embed](./assets/not-allowed-screen.png)

### Obtaining and Setting the Embedding URL

The URL in the Hyperlink field must be set to the embedding URL. For example, the embedding URL for YouTube can be obtained as follows:

1. Open video
1. Select the **Share** button
1. Select the **Embed** button
1. Copy the URL from the `src` attribute in the embed code.

    ![how to get the URL for YouTube embedding](./assets/youtube-embed-url.png)

If the URL is not for embedding, the following error screen may appear:

![screenshot of the error screen if the URL is not an embedding URL](./assets/refused-screen.png)

## View requirements

This format can be applied to a Hyperlink column.

## Sample

Solution|Author(s)
--------|---------
hyperlink-embed.json | [Tetsuya Kawahara](https://github.com/tecchan1107) ([@techan_k](https://twitter.com/techan_k))

## Version history

Version |Date            |Comments
--------|----------------|--------
1.0     |August 27, 2024 |Initial release

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Additional notes

- [Formatting syntax reference - customRowAction](https://learn.microsoft.com/sharepoint/dev/declarative-customization/formatting-syntax-reference#customrowaction)

<img src="https://pnptelemetry.azurewebsites.net/list-formatting/column-samples/hyperlink-embed" />