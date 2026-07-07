# Cindie Email Signature Generator

This folder is a static client-facing email signature generator. It can be hosted anywhere that serves static files.

## Recommended Sharing Setup

Host this folder as a webpage and share one link with clients, for example:

- `https://cindie.com/signature-generator`
- `https://cindie-signature-generator.netlify.app`

Clients open the link, enter their details, upload a headshot, click **Copy Signature**, then paste into their email signature settings.

## Deploy Options

### Netlify

1. Log in to Netlify.
2. Drag this entire `cindie-email-signature-generator` folder into Netlify's deploy area.
3. Rename the site or connect a custom domain.

### Vercel

1. Create a new Vercel project.
2. Upload or connect this folder.
3. Use the default static output. No build command is needed.

### Cindie Website

Upload the folder contents to a route such as:

`/signature-generator`

The page entry point is:

`index.html`

## Files To Keep Together

- `index.html`
- `assets/`

The `asset-manifest.md` file is optional documentation and does not need to be public.

## Client Instructions

Tell clients:

1. Open the generator link.
2. Fill in their contact information.
3. Upload a headshot if desired.
4. Click **Copy Signature**.
5. Paste into Gmail, Outlook, or Apple Mail signature settings.

Do not tell clients to paste into a normal email compose window.
