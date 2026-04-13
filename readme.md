# Kevin T. Morris – Personal Website

A static academic website. No build tools, no frameworks, no dependencies — just HTML and CSS.

## Files

- `index.html` — Home page
- `research.html` — Research (organized thematically)
- `books.html` — Books
- `impact.html` — Public impact (courts, Congress, policy, media)
- `cv.html` — CV download page
- `style.css` — Shared stylesheet
- `morris.jpg` — **You need to add this** (your headshot)
- `morris_cv.pdf` — **You need to add this** (your CV PDF)

## Deploying to GitHub Pages (free)

1. Create a new GitHub repository (e.g., `kevintmorris.github.io`)
2. Upload all files to the repository
3. Go to Settings → Pages → set source to "main" branch
4. Your site will be live at `https://kevintmorris.github.io`
5. To use your custom domain (`kevintmorris.com`):
   - Add a file called `CNAME` containing just: `www.kevintmorris.com`
   - In your domain registrar (wherever you bought the domain), update DNS:
     - Add a CNAME record: `www` → `kevintmorris.github.io`
     - Add A records pointing to GitHub's IPs (see GitHub docs)

## Deploying to Netlify (free, slightly easier)

1. Go to netlify.com, sign up, click "Add new site" → "Deploy manually"
2. Drag and drop this entire folder
3. Set custom domain in Site Settings → Domain management

## Things to customize

- Replace `morris.jpg` with your actual headshot
- Replace `morris_cv.pdf` with your actual CV
- Update the book cover placeholder when the actual cover is available
- Add/remove media outlets on the impact page as needed
- Update the media grid with specific article links if desired
- When *The New Lost Cause* is ready to announce, add a second section to books.html

## Fonts

The site uses Google Fonts (Cormorant Garamond + Source Sans 3), loaded via CDN. No local font files needed.
