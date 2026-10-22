Instagram Comment Automation — Legal Pages

Files:
- privacy-policy.html
- data-deletion.html

Before publishing:
1. Replace every occurrence of [REPLACE WITH A MONITORED PRIVACY CONTACT EMAIL] with an email address you actively monitor.
2. Review the pages and make sure the descriptions match your actual n8n workflow, permissions, data access, execution history retention, and deletion process.
3. Configure n8n execution data retention and make sure you can locate/delete records when a valid request is received.
4. Publish both pages over HTTPS.
5. Test both pages in a private/incognito browser window.
6. Use the published privacy-policy URL in Meta's Privacy Policy URL field and the published data-deletion URL in the User Data Deletion URL field.

GitHub Pages quick setup:
1. Sign in to GitHub and create a public repository, e.g. instagram-automation-legal.
2. Upload privacy-policy.html, data-deletion.html, and optionally this README.md to the repository root.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch; choose the main branch and / (root), then Save.
5. Wait for GitHub Pages to publish the site. The URLs will resemble:
   https://YOUR-GITHUB-USERNAME.github.io/instagram-automation-legal/privacy-policy.html
   https://YOUR-GITHUB-USERNAME.github.io/instagram-automation-legal/data-deletion.html
6. Replace YOUR-GITHUB-USERNAME with your actual username and confirm the exact URLs work before entering them in Meta.

Important:
- Do not publish access tokens, app secrets, webhook verify tokens, or private user data.
- These pages are starter templates, not legal advice or a guarantee of Meta approval.
