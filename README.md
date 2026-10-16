# TripleZ website: launch build

Open `index.html` in a browser to click through the whole site. Every page links to the others.

| Page | File | Built from |
|---|---|---|
| Home | index.html | mockups/TripleZ_Homepage_Mockup_v11.html |
| Why Colombia | why-colombia.html | mockups/why-colombia_v3.html |
| About | about.html | mockups/about_v3.html |
| Knowledge Base | knowledge-base.html | mockups/knowledge-base_v1.html |
| Resume 101 (post) | resume-101.html | mockups/post-resume-101_v1.html |
| Success Stories | success-stories.html | mockups/success-stories_v2.html |
| Client Portal | client-portal.html | mockups/client-portal_v1.html |
| Talent Acquisition | talent-acquisition.html | mockups/talent-acquisition_v2.html |
| Back Office | back-office.html | mockups/back-office_v2.html |
| Equipment | equipment.html | mockups/equipment_v1.html |

Changes made for launch (Oct 14, 2026): one shared menu on every page, "Design mockup" banners and footer notes removed, homepage title set, all links point at the files above.

## Still open before launch
- Service pages: Talent Acquisition, Back Office and Equipment are done (linked from the homepage cards, the Services menu and About). Employer of Record and Workforce Consulting "Learn more" links still point to the services section.
- Contact form (every page) sends to cynthia@triplez.com.co through FormSubmit (formsubmit.co). The first real submission triggers a one-time activation email to Cynthia that she must confirm. It only works on the live site, not in the Claude preview.
- "Book a call" links to https://calendar.app.google/CwoYRGL3jgAScoQU9
- Images live in img/ (moved out of the pages 2026-10-16 for speed; map resized and large images converted to WebP). Logo copies: triplez_logo.png, favicon.png, apple-touch.png.
- SEO basics done 2026-10-14: titles, descriptions, canonical URLs, link-preview tags (og-image.png), sitemap.xml, robots.txt, Organization schema on home, client portal set to noindex. Redirects from the 4 known old Wix URLs are in vercel.json (add any others before launch).
- Hosting: live on Vercel since 2026-10-14 (repo cdiazrueda/triplezwebsite2026, pushes to main deploy). DNS is managed in Wix; move it to GoDaddy before cancelling Wix.
