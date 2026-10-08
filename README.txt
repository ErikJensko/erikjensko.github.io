ERIK JENSKO — ACADEMIC WEBSITE
Updated 8 October 2026. Hosting: https://erikjensko.github.io/

UPLOAD / REPLACE ON GITHUB
1. Unzip this package on your computer.
2. Open github.com/ErikJensko/erikjensko.github.io.
3. Select Add file > Upload files.
4. Drag the CONTENTS of this folder into the upload area: all HTML files,
   assets/, images/, PDF/, LICENSE.txt, robots.txt, sitemap.xml and README.txt.
   Do not upload the ZIP itself or the enclosing folder.
5. Click Commit changes and commit to main. Same-path files replace existing
   versions. Leave folders intact: index.html must be at the repository root.
6. In Settings > Pages use Deploy from a branch, main, /(root), then Save.
7. Check https://erikjensko.github.io/ after deployment finishes (up to 10 min).
   If your browser still shows old content, hard-refresh or open a private tab.
8. This package includes an empty .nojekyll file. If it is hidden on your
   computer, use GitHub's Add file > Create new file, name it .nojekyll,
   leave its contents empty and commit. No custom build workflow is needed.

If you previously uploaded OLD/, delete that folder from GitHub separately:
uploading a replacement package does not delete old files. If you uploaded
an old CV elsewhere, remove that obsolete public copy too. Keep LICENSE.txt
and the HTML5 UP design credit.

WHAT CHANGED
- Updated all four original pages and added publications.html and talks.html.
- 12 papers verified against the INSPIRE author record on 8 October 2026,
  including journal details, DOI links and individual INSPIRE entries.
- PhD and MSc theses listed separately; ORCID verified from INSPIRE.
- All website contact links use jenskoerik@gmail.com.
- Dated UCL fellowship information (April 2024–October 2026).
- Refreshed research overview and selected highlights, with ongoing work
  described as research directions rather than unpublished results.
- Updated academic history, visits, teaching, service and talks from the CV.
- Public CV copy: new email; referee contact section omitted. Original CV
  supplied to ChatGPT is unchanged.
- Retained the HTML5 UP Editorial template and existing photographs, added
  visible navigation and restrained blue styling. No analytics included.
- Removed archived OLD/ from this upload package. Core CSS/JS remain intact.

FUTURE EDITS
You can click an HTML file in GitHub, select Edit (pencil), change the text,
then Commit changes. The site will republish automatically.
index.html: home and selected research highlights.
research.html: detailed research interests.
publications.html: the one complete paper list, newest arXiv submission first.
academic.html: employment, education, visits, teaching and service.
talks.html: selected talks by year.
misc.html: personal interests and contact.
assets/css/updates.css: layout refinements and colours.
PDF/Erik_Jensko_CV.pdf: replace this file when updating the downloadable CV.

The publication list is static: add future papers to publications.html.
For a new paper, copy one <li id="paper-...">...</li> block at the top of the
list, update title, authors, journal and links, and use a unique paper ID.
The reversed numbered list adjusts its numbering automatically.
Update the description mentioning the paper count and the footer date too.
Contact details and navigation occur in each HTML file; change all six
pages together when updating those shared details.
The China visit is explicitly marked planned. Update it after it takes place.

PREVIEW LOCALLY
Double-click index.html after unzipping. No software installation needed.
Alternatively, run python3 -m http.server 8000 from this directory and open
http://localhost:8000 in a browser.

SOURCES
Latest user-supplied CV (October 2026), original website, and user-confirmed
contact details. Publication and identifier records:
https://inspirehep.net/authors/1873100
https://inspirehep.net/api/literature?q=a%20Erik.Jensko.1&size=100&sort=mostrecent
https://orcid.org/0000-0002-6422-0753

TEMPLATE
Editorial by HTML5 UP (html5up.net). Retain attribution and LICENSE.txt.
