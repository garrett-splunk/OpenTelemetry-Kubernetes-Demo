# OTel Demo Lab — Workshop Site

Hands-on lab guide: deploy the [OpenTelemetry Demo](https://github.com/open-telemetry/opentelemetry-demo) to Kubernetes and export telemetry to Splunk Observability Cloud.

**Live site:** https://garrett-splunk.github.io/OpenTelemetry-Kubernetes-Demo/

Styled with the [Splunk Workshop Theme](https://github.com/splunk/hugo-theme-splunk-workshop).

## Local preview

```bash
open index.html
```

Or serve with any static file server:

```bash
python3 -m http.server 8080
# browse http://localhost:8080
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full lab guide |
| `styles.css` | Splunk workshop theme tokens and layout |
| `app.js` | Theme toggle, copy buttons, sidebar/TOC navigation |
| `screenshots/` | Lab images (Helm install output) |
