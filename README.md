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

Missing years with no program on file: 1998, 2010, 2012, 2016, 2020–2021 (no conference was held in 2016 or 2020–2021; 2010 and 2012 have no known records). Original program files are used where they exist (2000, 2001, 2004, 2005, 2006, 2013–2026). PDFs for 1994, 1997, 1999, 2002, 2003, 2007, 2008, 2009, and 2011 were generated from the appendix of Mark A. Wynne, "The Texas Monetary Conference Story, 1993–2015" (draft of August 22, 2025); 1993, 1995, and 1996 have no surviving program, so their PDFs list the known participants and are linked as "Participants". Programs available online are also linked with "Web page ↗" (Wayback Machine snapshots for 2000, 2001, 2004, 2005, 2009, and 2013; UH for 2003; Dallas Fed for 2014). The "No." column numbers conferences from 1993 = 1st; 2019 = 25th, with no conference in 2016 (the October 2015 UH meeting counts as the 22nd) or in 2020–2021 (COVID), so 2027 is the 31st. December 2009 (UT Austin) is the 17th and April 2011 (SMU) the 19th.

To preview locally, open `index.html` in a browser.
