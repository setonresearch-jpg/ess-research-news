# ESS Research News — public display only

These pages load `news.json` and `events.json` (currently empty placeholders). They do not directly access Google Sheets, Google Drive, or Apps Script.

## Publish
Upload the contents of this folder to the **root** of the GitHub Pages repository (`main` branch). Visit `https://YOUR-USERNAME.github.io/ess-research-news/`, `/home-events.html`, and `/events.html`. Initially they will show empty states.

## Expected feeds
`news.json`: an array of objects with `date`, `title`, `summary`, `image`, `link`, `category`. `image` should be a public URL or relative path such as `images/photo.jpg`, not a Drive file ID or Base64 data.

`events.json`: an array of objects with `date`, `month`, `day`, `title`, `time`, `venue`, `link`.

**Security:** This is a public repository: never commit any private spreadsheet, Drive image, credential, access token, unpublished news, or personal information not cleared for publication. Future Apps Script synchronization should run under an authorized ESS account, write only approved data to the repository, and put credentials in private Script Properties.
