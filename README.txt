AVOA SIMPLE EC ISSUES SITE

Files:
- index.html  = static website
- data.js     = data displayed by the website
- AVOA_EC_Issues.xlsx = Excel source

Update workflow:
1. Update the Excel sheet.
2. Export/copy the Excel rows into data.js using the same fields:
   serial, date, impact, issue, remarks.
3. Commit index.html + data.js to GitHub.
4. GitHub Pages automatically shows the committed data.

For a fully automatic Excel -> GitHub Pages workflow, use a GitHub Action or a small conversion script.
