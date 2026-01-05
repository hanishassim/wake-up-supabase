# Wake Up Supabase

A tiny GitHub Actions helper that prevents free Supabase projects from being automatically paused due to inactivity.

Supabase pauses inactive free-tier projects after about a week.  
If a project stays paused for 90 days, it is permanently deleted.

Article: https://shadhujan.medium.com/how-to-keep-supabase-free-tier-projects-active-d60fd4a17263

---

## 🛡 Security

- Uses anon keys only (never the service_role key)  
- Secrets stored securely in GitHub Actions Secrets  
- Workflow never prints keys  
- Repo contains zero sensitive information
