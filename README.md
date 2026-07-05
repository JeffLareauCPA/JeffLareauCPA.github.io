# Lareau & Lareau CPA Qualifier Web Handoff

This package is ready to be hosted on your website without requiring ChatGPT login.

## Recommended placement

Serve the page at:

`https://www.lareaucpas.com/resources/scheduler/`

Use this folder structure:

- `index.html`
- `lareau-logo.png`
- `lareau-logo.svg`

The page is self-contained and uses relative paths for the logo, so these files should stay together in the same directory.

## How to publish

1. Upload the contents of this folder to the web server path for `/resources/scheduler/`.
2. Make sure the server serves `index.html` by default.
3. Leave the logo files in the same folder as the HTML file.

## Optional embed snippet

If your web team wants to place the qualifier inside an existing page instead of serving it as the page itself, use:

```html
<iframe
  src="/resources/scheduler/"
  title="Before You Schedule Your Appointment"
  style="width: 100%; min-height: 100vh; border: 0; display: block;"
  loading="lazy"
></iframe>
```

## Notes

- The form is mobile-friendly and one-question-at-a-time.
- It does not store responses.
- It routes qualified users to the correct scheduling links and disqualified users to contact options only.
