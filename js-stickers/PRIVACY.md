# JS Stickers — Privacy Policy

_Last updated: October 24, 2026_

JS Stickers is a Chrome extension that shows the live values of JavaScript expressions you write, evaluated on the page in the current tab. This policy explains what data it handles and how.

## Data the extension handles

- The expressions you type in the popup, and the sites you pin each one to.
- Popup settings: width, font size, view options, and each sticker's height and collapsed state.
- While the popup is open, the address of the active tab, from which it takes the site's hostname.
- The values your expressions return from the page. These contain whatever page content your expressions read, which can include personal information if an expression reads it.

## How it is used

- While the popup is open, your expressions run on the active tab through Chrome's `chrome.userScripts` API, and their values are shown in the popup.
- The tab's hostname is used to show the stickers saved for that site.

## Storage and retention

- Expressions and settings are saved in the extension's local storage (`chrome.storage.local`) on your device, until you delete a sticker or uninstall the extension.
- Expression values are held in memory only and are discarded when the popup closes. They are copied to the clipboard only when you click the copy button.

## Sharing

The extension does not transmit any data off your device. It makes no network connections of its own, includes no analytics or telemetry, and does not sell, transfer, or share data with anyone. Expressions run inside the page as you wrote them, so a request made by an expression you wrote (for example `fetch(...)`) is sent by that page.

## Permissions

- `userScripts`: runs the expressions you write on the current tab.
- `storage`: saves your expressions and settings on your device.
- Access to all sites: lets expressions run on whichever site is open, and lets the popup read the tab's hostname. Code runs only on the active tab, and only while the popup is open.

## Contact

Questions about this policy: dmitriy.ben@gmail.com
