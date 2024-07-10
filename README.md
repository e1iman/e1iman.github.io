### Redirect and QR Code Generator

This simple web page serves a dual purpose: it redirects users to another URL specified via a `redirect` GET parameter in the query string and generates a QR code for redirecting to a desired page, typically for opening a deep link to an app.
Web page is hosted at https://e1iman.github.io/

#### Usage

1. **Redirect Functionality:**
   - To use the redirect functionality, append a `redirect` parameter to the URL with the desired destination URL. For example:
     https://e1iman.github.io/?redirect=geo:51.4045,30.0562
   - When the page loads with the `redirect` parameter, it immediately redirects the user to the specified URL.

2. **QR Code Generation:**
   - Alongside the redirect functionality, a QR code is generated for the current page URL.
   - The QR code appears on the page and can be scanned to easily visit the current page on a mobile device or any QR code scanner.

#### Dependencies

- This page uses the `qr-code-styling` library (`qr-code-styling.js`) to generate QR codes dynamically.

#### License

This code is provided as-is under the MIT License. Feel free to modify and use it according to your needs.

---

This readme file provides a clear overview of how to use and implement the provided functionality in your web project. Adjustments can be made based on specific requirements or preferences.
