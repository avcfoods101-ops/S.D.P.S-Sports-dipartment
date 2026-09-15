# S.D.Public School — SPORTS DEPARTMENT

## Netlify / No Supabase

This is the production website package for GitHub → Netlify deployment.

### Deploy
1. Extract this ZIP.
2. Upload the extracted files/folders to the root of your GitHub repository (do not upload the ZIP itself).
3. In Netlify: Add new project → Import from GitHub → select the repository.
4. Deploy. No Supabase and no Render are required.
5. Netlify Functions and Netlify Blobs provide the backend and persistent data storage.

### Login security
- Login credentials are **not displayed on the website login screen**.
- The system uses role-based access for Owner, Sports Teacher, House Teacher, Prefect and Student.
- Change the initial administrator passwords after the first successful login.

### Important
Use the repository root as the Netlify base directory. The included `netlify.toml` sets the publish directory to `static`, the functions directory to `netlify/functions`, and routes `/api/*` to the backend function.
