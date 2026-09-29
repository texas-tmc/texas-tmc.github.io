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

**Post the upcoming program.** Put the PDF in `programs/`. In `index.html`, change the host line and replace the "Program coming soon" badge with a link, for example `<a class="badge" href="programs/2027_TexasAM.pdf">View program</a>`.

**Add a year to Previous Programs.** Put the PDF in `programs/` and add a `<tr>` at the top of the table in `programs.html`.

Missing years with no program on file: 2007–2013, 2016, 2019–2021. The 1993–2005 rows list hosts only.

To preview locally, open `index.html` in a browser.
