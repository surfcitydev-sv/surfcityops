# Surf City Ops

A responsive, dependency-free English/Spanish homepage. Open index.html in a browser to preview it.

## Before launch

- Confirm the service wording and business contact email.
- Replace the project-brief download with the approved contact method when available. Currently this form only downloads a local text file; it sends nothing.
- No testimonials, client counts, performance claims, analytics, SMS services, or paid dependencies are included.

## GitHub Pages

Upload index.html and .nojekyll to the root of the intended GitHub repository. Configure Pages to publish from the main branch and root folder. First confirm the default Pages URL works. Then add surfcityops.com as the custom domain and configure DNS using GitHub's current official documentation. Enable HTTPS after domain verification and certificate issuance.

Do not change existing DNS without reviewing its current records, particularly mail records. CNAME is intentionally omitted until the custom domain is connected.

Official documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
