# PromptKey Privacy Site

This folder is a minimal GitHub Pages site for the PromptKey privacy policy.

## Publish On GitHub Pages

### Option 1: Dedicated repo

1. Create a public repo such as `promptkey-privacy`.
2. Copy the contents of this folder into the repo root.
3. In GitHub, enable **Pages** from the default branch root.
4. Use the resulting URL in App Store Connect.

### Option 2: Existing site repo

1. Copy `index.html` into the privacy path for your site, for example:
   - `privacy/index.html`
2. Deploy your site normally.
3. Use the stable public URL in App Store Connect.

## Requirement Notes

For App Store purposes, the important part is:

- the page is public
- the URL is stable
- the content matches the in-app privacy policy

GitHub Pages is usually fine for this requirement if those conditions are true.
