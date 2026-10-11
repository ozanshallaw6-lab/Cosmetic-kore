COSMETIC KORE — website with editable product catalog

FILES TO UPLOAD TO YOUR GitHub repository:
- index.html (public store)
- admin.html (private-use management page; keep your GitHub token secret)
- catalog.json (the product list and compressed product images)

Important setup:
1. Upload all three files to the ROOT of your GitHub repository `ozanshallaw6-lab/Cosmetic-kore` on the `main` branch.
2. In Netlify, connect this site to the GitHub repository (Project configuration / Build & deploy / Continuous deployment, or import the repo). Publish directory should be the repository root; no build command is needed.
3. Open `https://YOUR-NETLIFY-SITE/admin.html` to manage products.
4. Create a fine-grained GitHub Personal Access Token limited to this repository with Contents: Read and write. Enter it on admin.html. Never share the token with anyone; it only needs repository Contents permission.
5. Edit products and click save all. Each save commits catalog.json; Netlify will redeploy automatically once linked to GitHub.

This package includes the product catalog and prices supplied in the conversation. Prices not provided remain blank and prompt customers to ask on WhatsApp. Some product images use the available product photos; replace images through admin as needed.
