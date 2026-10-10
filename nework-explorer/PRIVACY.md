# Network Explorer — Privacy Policy

_Last updated: October 7, 2026_

Network Explorer is a Chrome DevTools extension. This policy explains what data it handles and how.

## Data the extension handles

While DevTools is open, the extension reads the network requests of the inspected tab through Chrome's `chrome.devtools.network` API. This includes request URLs, methods, status codes, timings, request and response headers, request payloads, and response bodies. That traffic can contain website content, cookies, authorization tokens, and any personal information the inspected website sends or receives.

## How it is used

This data is used only to display, filter, query, copy, and export network traffic inside the Network Explorer panel, at your request.

## Storage and retention

- Captured traffic is held in memory only and is discarded when DevTools closes or when you click **Clear**. It is never written to disk by the extension.
- Display preferences (font size, font family, and whether the collection query is enabled) are saved in the extension's local storage on your device.
- Files you choose to download or text you copy are handled by your browser and operating system; the extension keeps no copy.

## Sharing

The extension does not transmit any data off your device. It makes no network connections (its content security policy blocks them), includes no analytics or telemetry, and does not sell, transfer, or share data with anyone.

## Permissions

The extension requests no Chrome permissions and no host permissions. It uses only the DevTools page API available to every DevTools extension.

## Contact

Questions about this policy: dmitriy.ben@gmail.com
