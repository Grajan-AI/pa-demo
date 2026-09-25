PA v3 browser-only demo

1. Host index.html on an HTTPS static website.
2. Add the site's exact origin to Google Auth Platform > Clients > My Personal AI Web > Authorized JavaScript origins.
3. Keep the OAuth app in Testing and the demo Gmail as a Test User.
4. Open the hosted site and click Connect Google.

No Client Secret is stored in this page. Do not add a Google Client Secret or AI API secret to browser JavaScript.

PA v3 reads the School Registration demo email and lists upcoming Calendar events. The AI reasoning layer will be added later through a secure backend/gateway.
