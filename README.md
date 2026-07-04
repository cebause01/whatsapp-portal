# WhatsApp Link Portal

A simple landing page (like Linktree) that links to your WhatsApp chat. Use this URL on Facebook instead of the direct WhatsApp link.

## Local preview

Open `index.html` in your browser, or run a local server:

```bash
npx serve .
```

## Deploy (free options)

1. **Netlify** — drag the `portal` folder to [app.netlify.com/drop](https://app.netlify.com/drop)
2. **GitHub Pages** — push to GitHub, enable Pages from the repo settings
3. **Vercel** — import the folder at [vercel.com](https://vercel.com)

After deploy, put your site URL (e.g. `https://cebause.one/whatsapp`) on Facebook.

## Different message per post

Add `?text=` to your link. Each post can use a different starting message:

| Link | WhatsApp opens with |
|------|---------------------|
| `https://cebause.one/whatsapp` | `tiong3e` (default) |
| `https://cebause.one/whatsapp?text=tiong3e` | `tiong3e` |
| `https://cebause.one/whatsapp?text=product123` | `product123` |
| `https://cebause.one/whatsapp?text=Hi%20from%20Facebook` | `Hi from Facebook` |

You can also use `?msg=` instead of `?text=`.

## Customize

Edit `index.html`:

- **Name** — change `Zulkifli` to your display name
- **Default message** — change `DEFAULT_MESSAGE` in the script
- **Phone number** — change `PHONE` in the script
