# AIK Lunch

Lunch ordering for AIK Fotboll Damer: players pick Tuesday and Thursday dishes before Sunday 13:00, and the food coordinator reviews totals and emails the caterer.

- Player page: `index.html`
- Admin: `index.html#admin` (password protected; checked server-side)
- Backend: Supabase project "AIK Matbeställning" (eu-north-1). All data sits in a private schema; the page only calls RPC functions.
