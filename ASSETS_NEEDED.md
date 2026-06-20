# Assets you still need to add (the code is wired up and ready)

These are referenced in `index.html` but I can't create them for you — they
need to be real (your actual photo, actual resume, actual deployments).
Drop them in alongside `index.html` with these exact filenames and
everything will start working automatically (no further code changes needed):

1. **`resume.pdf`** — your resume, exported as PDF. Used by:
   - Nav "Resume" link
   - Hero "Download Resume" button
   - Contact section "Resume" link

2. **`headshot.jpg`** — a real, professional photo of you, ideally square,
   at least 280×280px. Until this file exists, the About section gracefully
   falls back to the "SM" initials avatar (no broken image icon).

3. **Project screenshots** (optional but recommended) — replace the gradient
   placeholder `<div class="project-media">` in each project card with an
   `<img>` tag. The exact markup to use is left as an HTML comment directly
   above each placeholder in `index.html`.

4. **Live demo URLs** — once you deploy ResumeFit / Zoomies & Snuggles /
   MediBot somewhere (Vercel/Netlify/Render are free), replace the `href="#"`
   on each "Live Demo" link and remove the `is-disabled` class + `aria-disabled`
   + `onclick="return false;"` attributes. They're disabled for now so the
   site never ships a broken/fake link.

5. **Custom domain** — once you buy `sahilmungara.dev` (or similar), you'll
   need to find-and-replace `sahilmungara.netlify.app` with your new domain
   across: `<title>`, canonical tag, OG/Twitter meta, JSON-LD `@id`/`url`
   fields, `sitemap.xml`, and `robots.txt`.

6. **Contact form activation** — the new contact form posts to
   `https://formsubmit.co/sahil.mungara147@gmail.com` (free, no signup).
   The first real submission triggers a one-time confirmation email — click
   the link in it once to activate the form permanently.

## Not implemented (needs your real content, not code)
- **Testimonials** — I didn't fabricate quotes attributed to real people.
  Once you have 1–2 genuine quotes (mentor, GSSoC teammate, etc.), send them
  to me and I'll add a styled section.
- **Blog posts** — same reasoning; I won't invent articles under your name.
  Happy to help you draft real ones whenever you're ready.
- **Backlinks** (GitHub bio, LinkedIn Featured, GSSoC profile) — these are
  actions you take on those platforms, not something in this codebase.
