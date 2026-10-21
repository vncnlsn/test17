# APS Land Services / Website V1 Staging

Static HTML, CSS and JavaScript website for GitHub Pages testing. Gallery 19 homepage preserved as the design baseline. Main navigation: Home, Services, Company, Contact. Additional service detail pages, Safety and HSE, and a staging privacy notice are accessible by internal links.

## Deploy
1. Extract this ZIP.
2. Create a separate GitHub repository for staging.
3. Upload the **contents** of the `APS_V1_Staging` folder to the repository root.
4. In Settings > Pages, select Deploy from a branch, `main`, `/ (root)`.
5. Open the GitHub Pages URL. All links are relative to support project subpaths.

## Important before production
- Every page contains `noindex,nofollow` during testing. Remove only when approved.
- The client marquee on the homepage intentionally retains labeled placeholders. Do not publish unapproved logos or client claims.
- Verify all business claims, leadership biographies, phone and email details, coverage map, HSE documentation and ISNetworld membership with APS.
- The contact form opens the visitor's email application; it does not submit to a server. Selections are held in `sessionStorage` for the browser tab.
- Replace the staging privacy notice with approved production policy before launch.
- Do not upload confidential bid data, private landowner information, or vendor onboarding records to a public repository.
- The homepage retains Gallery 19's large embedded SVG map. Future performance work can separate its code without changing the design.
