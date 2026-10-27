# Upload Pitwall to GitHub Pages — no terminal needed

These are the original manual-upload instructions for the prebuilt static copy. This repository was subsequently populated through Git push; the manual upload steps below are retained as an alternative for future copies. Use GitHub-Upload/, not Project-Source/, for this simple branch/root method.

1. Unzip Marcin_AI101_Midterm.zip by double-clicking it in Finder. Open GitHub-Upload. You should see index.html, assets, models, README.md and other files directly inside it. Do not try to run by double-clicking index.html; workers/models need an HTTP(S) website.
2. Sign in to https://github.com/ . Click + → New repository. Use a public repository, e.g. ai101-midterm. Add a README so main exists; create the repository yourself.
3. In the repository click Add file → Upload files. In Finder press Command+Shift+. to show hidden files, so .nojekyll is included. Select the CONTENTS of GitHub-Upload and drag them into the upload area. Do not drag the ZIP or the outer GitHub-Upload folder. Keep assets/, models/ and evidence/ as folders. If your browser rejects a folder, use GitHub Desktop or upload those folders in separate batches; do not flatten them.
4. Use a commit message such as “Add Pitwall midterm game”; commit to main (or merge a proposed branch into main). Confirm index.html appears on the repository's front page, alongside assets and models. If an existing README conflicts, replace it with this package's README.
5. Settings → Pages → Build and deployment: Source = Deploy from a branch; Branch = main; Folder = /(root); Save. This package is already compiled; do not select a new React/Actions build workflow for this method.
6. Wait for the Pages deployment to finish. Refresh Settings → Pages and use its Visit site link. The Actions tab shows deployment progress/failures. Your URL normally looks like https://YOUR-USERNAME.github.io/ai101-midterm/ . Keep the trailing slash. A custom repository name works too.
7. Open the site. Start a race and confirm the caption reaches “12 detailed cars loaded”; if not, check models/ was uploaded. Check About → notes/credits and Analysis reference data. If missing, make sure you uploaded ALL files, with spelling/case unchanged. Hard-refresh with Command+Shift+R if an old version appears.
8. Edit README.md on GitHub: replace the two PENDING/REPLACE link fields with the actual live URL and repository URL. Follow TEST_LOG.md and run all five tests on the live GitHub Pages site, including a private/incognito window and a real phone/narrow screen. Record actual results and one fix/retest; upload live evidence screenshots into evidence/. Review AI_USE.md so it accurately describes your contribution.
9. Submit BOTH the GitHub Pages URL and repository URL in Canvas. A ZIP is only the optional backup; it is not the live website. The screenshot lists an October 26 deadline: follow the instructor's late-work policy and permission requirements for your actual submission date.

## What is ready and what remains

The game, assets, credits, before/after development evidence and AI disclosure are included. README URL fields, live GitHub Pages tests and final live evidence require YOUR actual publication. This package does not claim the entire submission is already complete.

No .git history, .env files, node_modules, Sites configuration/credentials or raw Downloads models are in the upload folder. Car GLBs are adapted CC BY 4.0 display assets, with attribution retained. GitHub browser uploads allow up to 100 files per batch and 25 MiB per file; this ready folder is designed to fit those limits. If a large batch times out, upload the top-level files, then assets/, models/, evidence/ in separate batches before enabling Pages.

## Optional editable source

Pitwall_Editable_Source.zip is a separate developer backup. It is not necessary for branch/root publication. If you want source in the repository too, extract it and add its Project-Source folder separately, in batches or through GitHub Desktop, without node_modules or dist. Keep the prebuilt root files as the Pages entry point. Changing source alone does not update the prebuilt root game; rebuild and replace the static files after future changes.

## Official instructions checked October 27, 2026

- Upload files: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Set Pages publishing source: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Vite relative base: https://v6.vite.dev/guide/build#relative-base
