# Sri Maha Muni Medical Centre

Static website for Sri Maha Muni Medical Centre in Umachikulam, Madurai.

## Files

- `index.html`: complete page, matching the supplied HTML reference, with embedded CSS, images, and vanilla JavaScript.
- `docs/content-reference.md`: original English and Tamil content reference.

## Preview

Open `index.html` in a browser, or run this command from the project folder:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Then visit <http://127.0.0.1:8000>. No build step or package installation is required.

## Behaviour

The site includes responsive navigation, service sections, telephone and map links, and an enquiry form. The form prepares text for the visitor to copy and send; it does not submit enquiries to a server. Google Fonts requires an internet connection, with system font fallbacks available.

## Reference checks

The initial `index.html` is byte-for-byte identical to the supplied HTML. Markdown headings, internal link targets, embedded images, and JavaScript syntax were checked. Browser visual verification is still pending.
