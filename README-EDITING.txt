MON BUILDS WEBSITE — EASY EDITING VERSION

This package keeps your existing website design and adds a CMS editing area at /admin/.

IMPORTANT: For online editing, deploy this folder from a Git repository and connect it to a compatible Decap CMS backend. The included config is prepared for the Netlify Identity + Git Gateway workflow. Netlify currently marks Git Gateway as deprecated for NEW configurations, so check Netlify's current CMS/auth guidance before enabling it.

Files you can edit manually:
- content/site.json = hero and project content
- assets/ = project images
- index.html = website layout

Once your CMS backend is configured, visit:
https://YOUR-DOMAIN/admin/

The editor lets you update hero text/image, project titles, descriptions, facts, feature images and gallery images.
