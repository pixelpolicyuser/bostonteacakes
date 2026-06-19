# Boston Tea Cake Company website

## Upload set

Upload every file in this folder to the site repository, keeping the filenames unchanged. Each HTML file includes its own CSS and JavaScript, so there are no separate style or script files to upload.

## Editing safely

Each major visible area begins with an HTML comment such as `<!-- New fundraiser form ... -->`. Search the file for that comment before editing the related text. Do not change a form's `name` value or its hidden `form-name` value after it has been deployed; Netlify uses those values to identify the form.

## Netlify form routing

Set email notifications in Netlify for these detected form names:

- `website-feedback-web-design` → `nora.mdr@gmail.com`
- Every form beginning `btcc-business-` → `bostonteacakes@comcast.net`
- Every form beginning `btcc-distributor-` → `bostonteacakes@comcast.net`
- Every form beginning `btcc-fundraiser-` → `bostonteacakes@comcast.net`

## SEO files

`sitemap.xml` lists the four public pages. `thank-you.html` is intentionally excluded from search results with `noindex`. After deployment, submit `https://bostonteacakes.club/sitemap.xml` in Google Search Console.
