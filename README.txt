Frappe CRM WhatsApp Integration - Privacy Policy static page

Files:
- index.html: standalone static policy page suitable for Vercel or any HTTPS static host.

Before deploying:
1. Edit index.html and replace every [bracketed placeholder].
2. Replace YOUR-PRIVACY-EMAIL@example.com in both the mailto link and visible email.
3. Check every statement against your actual data collection, providers, hosting, retention, and deletion practices. Remove or revise any inaccurate statements.
4. Deploy the folder as a static site to Vercel (no build command; output directory is the project root) or another HTTPS host.
5. Open the deployed URL in a private/incognito window and confirm it loads without login, returns successfully, and is not blocked by robots.txt.
6. Add the stable HTTPS URL to Meta for Developers > Your App > App Settings > Basic > Privacy Policy URL (wording can vary). Save/publish any required app changes.

Important: A privacy policy URL is an app configuration/compliance item; it does not by itself enable WhatsApp sending. You still need working WhatsApp Cloud API credentials, required permissions, webhook/setup as applicable, and compliance with WhatsApp's current messaging rules, including required recipient opt-in.

Use a stable Vercel deployment/custom domain for production. Ngrok is suitable for temporary local development/webhook testing but its URL may change and it is not a good permanent policy URL unless you have a stable reserved domain and keep the tunnel available.
