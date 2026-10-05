# The Elan — Furniture Sourcing Website

A static GitHub Pages-ready website for a China furniture sourcing / procurement business.

## Pages
- Home
- 30-product collection with category filters and search
- Product detail pages via `product.html?id=...`
- Sourcing process
- Project types
- About
- Contact / project enquiry
- LocalStorage cart
- Buy Now / quote request checkout

## Run locally
Open `index.html` directly, or use VS Code Live Server.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload all files from this folder to the repository root.
3. Go to Settings → Pages.
4. Under Build and deployment, select `Deploy from a branch`.
5. Choose `main` and `/ (root)`.

## Important before production launch
- Product images currently use external Unsplash URLs as visual placeholders. Replace with supplier-owned/licensed product photography before commercial launch.
- The contact and checkout forms use `mailto:` and open the visitor's email app. Connect a form backend (Formspree/Web3Forms/custom PHP/Node) for reliable submissions.
- “Buy Now” is intentionally quote-first because sourced furniture pricing depends on quantity, material, customization, packing and freight. A payment gateway can be added later for fixed-price ready-stock products.
- Contact email normalized to `hanyue461@gmail.com` because email addresses cannot contain spaces.

Contact: +86 17862890863 / hanyue461@gmail.com
