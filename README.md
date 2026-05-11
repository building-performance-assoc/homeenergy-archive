# Home Energy Magazine Archive

Complete archive of Home Energy Magazine — 837 articles and 1,092 blog posts on residential energy efficiency from 2001–2020.

## Deploying to GitHub Pages

1. Create a free account at [github.com](https://github.com)
2. Click **New Repository** → name it `homeenergy-archive` → set to **Public** → click Create
3. Upload this entire folder (drag and drop all files)
4. Go to **Settings → Pages → Source** → select `main` branch → Save
5. Your site will be live at `https://yourusername.github.io/homeenergy-archive`

## Adding Your Images

Once your Wayback Machine image download completes:
1. Copy all images from `recovered_images/` into the `images/` folder in this archive
2. Re-upload to GitHub

## Custom Domain (Optional)

To use a custom domain like `homeenergyarchive.org`:
1. Buy the domain at Namecheap or GoDaddy (~$12/year)
2. In GitHub Pages settings, enter your custom domain
3. Add a CNAME record at your domain registrar pointing to `yourusername.github.io`

## Site Structure

```
index.html          ← Homepage with search
articles/           ← 837 individual article pages
blogs/              ← 1,092 individual blog pages
images/             ← Put recovered images here
css/style.css       ← Stylesheet
js/articles.json    ← Search index
js/blogs.json       ← Search index
sitemap.xml         ← For Google indexing
robots.txt          ← Search crawler instructions
llms.txt            ← AI search optimization
```
