# LegalEase QuickSummarizer Survey

A responsive, self-contained customer discovery survey. No dependencies, installation, or build step required.

## Included
- Business context: industry, role, monthly contract volume, purchase authority.
- Five importance attributes on a 1–7 scale.
- One primary purchase priority.
- Browser-local draft saving and individual response CSV download.

## Preview locally
Open index.html in a modern browser.

## Upload and publish with GitHub Pages
1. Extract this ZIP.
2. Create a GitHub repository.
3. Upload index.html, README.md, and .nojekyll to the repository root (not the ZIP itself).
4. In the repository Settings, open Pages.
5. Choose deployment from a branch, select main and / (root), and save.
6. Wait for deployment and open the URL shown in Pages.

If Pages is unavailable, check repository visibility and your GitHub plan. For other static hosts, deploy this folder and leave the build command empty.

## Response handling
This is a research preview. It does not send responses to a server or provide a shared research database. Drafts remain in the same browser through localStorage when browser permissions allow it. Respondents download their own CSV and share it separately. The CSV uses four-letter question codes.

Do not use this as a centrally collecting survey without adding a backend or connecting a form service and updating the privacy notice. The five attribute ratings are research hypotheses, not validated customer findings.

## Edit
All markup, styling, survey wording, and JavaScript are in index.html. No API keys or credentials are needed.

## Validation
JavaScript syntax was checked. Browser interactions and hosted deployment were not verified in the creation environment.
