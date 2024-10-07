# Redirect

A simple and free solution to redirect users to any website while tracking visits with Google Analytics. It serves as a perfect alternative to paid services like Bitly and must be hosted on GitHub Pages.

Use Cases:

- **Email Campaigns**: Track clicks from your emails.
- **Social Media Links**: Monitor traffic from your social posts.

## Example

The following URL will redirect the user to https://example.com while tracking the visit with Google Analytics:

```
https://rzagreb.github.io/r?url=https%3A%2F%2Fexample.com&utm_source=example
```

## How to Get Started

1. Clone the Repository.
2. Replace the existing GTM ID with your own (it starts with GTM-)
   - [How to create your own GTM container](https://support.google.com/tagmanager/answer/14842164)
3. Host on Github Pages
   1. Go to the repository Settings.
   2. Navigate to the Pages section.
   3. Set the Branch to /(root) and save.
