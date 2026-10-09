# SHIVAM FITNESS website

## Files
- `index.html` — responsive gym website with BMI, height and weight tools, exercise library, and a private contact form.

## Important: enable the contact form before publishing
The form is configured to send submissions to the email address you provided using FormSubmit (`https://formsubmit.co/`). Your email address is **not displayed in the page's visible contact section**, but it is present in the HTML form action and can be discovered by someone who inspects the page source. A static GitHub Pages website cannot keep a destination email secret.

### First-time setup
1. Upload `index.html` to your GitHub repository.
2. Publish it with GitHub Pages.
3. Open your published website and submit a test message through the form.
4. Check the inbox for the destination email and follow FormSubmit's activation/confirmation instructions.
5. Submit another test message after activation.

If you need the receiving email to be genuinely hidden from visitors inspecting source code, do not use a direct static form action. Use a backend or serverless function (for example, a Cloudflare Worker or another form service that keeps the destination address in server-side configuration). This requires additional setup.

## Privacy notes
- The phone number and email are not shown as visible contact details on the page.
- The Instagram username is public because you asked to include it.
- Messages submitted by visitors are processed by the form provider.
- Do not ask visitors for passwords, payment information, or other sensitive information.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` (and optionally this README).
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. Wait for GitHub Pages to provide the public website link.
