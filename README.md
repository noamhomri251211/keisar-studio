# Keisar Studio

Static site. Publish this folder as-is with GitHub Pages (Settings → Pages → Deploy from a branch → main, root).

- `index.html` is the customer app. On a github.io address it runs in live mode: sign-up, orders and usage events go to the Supabase project `keisar-studio`.
- `admin.html` is the back office (usage, orders, catalog). It needs the `ADMIN_CODE` Edge Function secret.
- Server code lives in Supabase Edge Functions: `api`, `admin`, `visualize`.
- Payment is simulated. Email addresses are not verified yet.
