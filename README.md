# Stop It! Support Website

This directory contains the support website for Stop It! to be hosted at `https://gzb-apps.com/stopit/support/`

## Files

- `index.html` - Main support page with FAQs, contact info, and troubleshooting
- `privacy.html` - Privacy Policy (required for App Store)
- `terms.html` - Terms of Service (required for App Store)

## Deployment Instructions

### Option 1: Upload to your existing hosting

1. Upload all files to your web server at `gzb-apps.com/stopit/support/`
2. Ensure the files are accessible at:
   - `https://gzb-apps.com/stopit/support/` (main support page)
   - `https://gzb-apps.com/stopit/support/privacy.html`
   - `https://gzb-apps.com/stopit/support/terms.html`

### Option 2: Using GitHub Pages (if preferred)

1. Create a repository called `stopit-support`
2. Upload these files to the repository
3. Enable GitHub Pages in repository settings
4. Set up a custom domain pointing to `gzb-apps.com/stopit/support`

## App Store Connect URLs

Once deployed, use these URLs in App Store Connect:

- **Support URL:** `https://gzb-apps.com/stopit/support/`
- **Privacy Policy URL:** `https://gzb-apps.com/stopit/support/privacy.html` (required for App Privacy section)

## Customization

Before deployment, you may want to update:

1. **Email addresses** - Currently set to:
   - `support@gzb-apps.com`
   - `privacy@gzb-apps.com`
   - `legal@gzb-apps.com`

2. **App Store badge** - Once your app is live, uncomment the App Store badge section in `index.html` and add your App Store link

3. **Contact information** - Ensure email addresses match your actual support email

## Testing Before Deployment

1. Open `index.html` in a web browser
2. Check all links work correctly
3. Test on mobile devices to ensure responsive design
4. Verify all email links open correctly

## Notes

- All pages are fully responsive and mobile-friendly
- Clean, minimalist design matches the app aesthetic
- No external dependencies (no jQuery, Bootstrap, etc.) for fast loading
- GDPR, CCPA, and COPPA compliant
- Meets all Apple App Store requirements

## SSL Certificate

Ensure your hosting has a valid SSL certificate so the URLs use `https://` (required by Apple).

## Support Email Setup

Make sure you have `support@gzb-apps.com` set up to receive emails. This is where user inquiries will be sent.

