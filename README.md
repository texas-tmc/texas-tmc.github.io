# Texas Monetary Conference website

A static site (plain HTML and CSS, no build step) served by GitHub Pages.

- `index.html`: landing page for the upcoming conference
- `history.html`: history of the conference
- `programs.html`: table of previous programs
- `programs/`: program PDFs, named `YYYY_Host.pdf`
- `css/style.css`: shared styles (maroon theme, Playfair Display + Lato)
- `images/`: cover banner and campus photo

## Editing from the browser (no software needed)

Any organizer with access to the GitHub repository can edit the site at github.com:

1. Open the file (for example `index.html`), click the pencil icon, make the change, and click **Commit changes**.
2. To upload a PDF, open the `programs/` folder, then **Add file → Upload files**.
3. The live site updates about a minute later.

Every change is saved in the history, so any edit can be undone.

## Common updates

**Post the upcoming program.** Upload the PDF to `programs/` (e.g. `2027_TexasAM.pdf`). In `index.html`, replace the `<span class="button" aria-disabled="true">…</span>` line with the commented-out `<a class="button" …>View the 2027 Program →</a>` just above it, and change "Coming soon" under Program in Conference at a Glance.

**Next year's conference.** Replace `images/banner-2027.jpg` with the new banner, then update the dates and location in `index.html`.

**Add a year to Previous Programs.** Put the PDF in `programs/` and add a `<tr>` at the top of the table in `programs.html`.

Missing years with no program on file: 2007, 2009–2013, 2016, 2020–2021. The 1993–2005 rows list hosts only, except 2003. Programs that exist only online (2003, and the 2014 Dallas Fed page) are linked with "Web page ↗".

To preview locally, open `index.html` in a browser.
