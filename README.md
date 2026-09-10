# Kiosk Admin Dashboard V1

Vercel-ready admin dashboard for the new Android Kiosk System. Uses Supabase Auth + Postgres.

## Deploy
1. Create Supabase project.
2. Run `supabase/schema.sql` in SQL Editor.
3. Create an admin user in Supabase Authentication.
4. Put your Supabase URL and anon key in `public/config.js`.
5. Push this folder to GitHub. Import repo into Vercel. Output directory: `public`; no build command.

Never put the Supabase service-role key in the browser.
