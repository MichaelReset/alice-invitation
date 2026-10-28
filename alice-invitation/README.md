# Alice in Wonderland party invitation

A free, static, interactive storybook-style invitation. No paid service or JavaScript framework required.

## Before publishing

**The inside image still contains placeholders:** `[Address]`, `[date]`, and `[contact]`. Update those in your design and replace `inside.png` before sharing publicly. Be mindful that a public GitHub Pages site is viewable by anyone with its URL, and your home address would be public if printed on the image.

## Publish using personal GitHub account MichaelReset

1. Sign in to https://github.com as **MichaelReset** (not your work account).
2. Create a new **public** repository named `alice-invitation` (or another name).
3. Upload `index.html`, `front.png`, and `inside.png` to the root of the repository. The README is optional.
4. Open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save.
5. Wait a few minutes for publication. With the suggested repo name, your link will be:
   https://michaelreset.github.io/alice-invitation/

You can preview the invitation locally by opening `index.html` in a browser. The entire invitation works without an internet connection after downloading the files.

## Notes

- The button is an invisible clickable region over the printed **Open Me** label, preserving the original cover artwork.
- The front swings open like a storybook cover. A Close invitation button returns to the front.
- Social preview tags are included, but some messaging services require an absolute public image URL; for best previews after publishing, update the `og:image` tag in `index.html` to your full GitHub Pages image URL.
