# ZMM Room App — frontend update

Upload these files to the root of your existing GitHub repository, replacing `index.html` and adding `manifest.json` and `sw.js`.

Important:
- This is an initial frontend, not a finished production app.
- Supabase SQL schema must already be installed.
- Phone/password signup may require SMS verification; this code does not bypass it.
- Admin bootstrap and approval interface are not implemented yet.
- Receipt uploads are deliberately disabled until private storage and access policies are configured.
- Do not use real financial data until admin setup, private storage, and security testing are complete.
- Never put Supabase secret/service-role keys in GitHub. Only the publishable key belongs in browser code.
