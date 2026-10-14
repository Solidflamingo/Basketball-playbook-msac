# Black Team Playbook — GitHub Pages

This is a ready-built static website with 20 plays: 11 offensive plays and 9 defensive situations. No build commands or paid hosting are required for the upload.

## Publish

1. Sign in to GitHub as `Solidflamingo`.
2. Create a public repository named `basketball-playbook`. Tick **Add a README file**.
3. Extract the supplied ZIP on your computer.
4. In the repository choose **Add file → Upload files**. Upload the extracted contents, including `index.html`, `plays.json`, `favicon.svg` and the entire `assets` folder. Upload the contents, not the ZIP and not an enclosing folder.
5. Commit the files to `main`.
6. Open **Settings → Pages**. Under Source choose **Deploy from a branch**, choose **main** and **/(root)**, then Save.
7. Open `https://solidflamingo.github.io/basketball-playbook/` once GitHub reports the deployment is ready.

## Edit and publish play updates

1. Open the website and select **Local editor**. Edit or copy a play, move players, add arrows and steps, and edit notes.
2. Choose **Save on this device**. This stores your changes in your browser. It does not update the public website.
3. Choose **Download updates**. The downloaded file is named `plays.json`.
4. In the GitHub repository choose **Add file → Upload files**, upload this new `plays.json` to replace the existing file, and commit.
5. GitHub republishes the website. Teammates refresh to see the new plays.

The **Published version** button reloads the version on GitHub and removes your device's unpublished copy after confirmation. Download your updates first if you need to keep them.

## Access

Everyone with the website link can view the plays. Local editing only changes a copy on that person's device. Publishing requires write access to the GitHub repository. There is no edit password in these public files and no connection to the earlier ChatGPT-hosted website.

## Keep these files together

`index.html`, `plays.json`, `favicon.svg` and `assets/` must remain at the same repository level. The file paths are relative, so this works under a GitHub Pages project path such as `/basketball-playbook/`.
