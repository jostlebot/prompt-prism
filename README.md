# Prompt Prism

A clinician configuration portal for customizing AI therapy assistant behavior.

## Features

- **Voice & Relational Mode**: Configure how the AI communicates (Witnessing, Reflective, Resonant, Coaching, Directive)
- **Functional Scope**: Enable/disable features like psychoeducation, homework delivery, risk check-ins
- **Client Scope**: Set treatment modality, focus areas, attachment profile, and permissions
- **Acuity Levels**: Adjust AI initiative based on client risk level (Low, Moderate, High)

## Setup

1. Open `index.html` in a browser
2. Enter the password: `prism2024`
3. Configure settings as needed

## Deployment

This is a static site that can be hosted on GitHub Pages, Netlify, Vercel, or any static hosting service.

### GitHub Pages

1. Push to a GitHub repository
2. Go to Settings > Pages
3. Select "Deploy from a branch" and choose `main`
4. Your site will be available at `https://username.github.io/prompt-prism`

## Security Note

The password protection is client-side only. For production use with sensitive data, implement server-side authentication.

## Changing the Password

Edit the `VALID_PASSWORD` constant in `index.html`:

```javascript
const VALID_PASSWORD = 'your-new-password';
```

## License

MIT
