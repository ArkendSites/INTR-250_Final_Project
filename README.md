# Think vs. Feel

Final project site for INTR250P by Mateo Herrera and Dylan Young.

## Put it on GitHub Pages

1. Create a new public repository on GitHub (for example `think-vs-feel`).
2. Upload everything in this folder, keeping the structure:
   `index.html`, `assets/img/…`, and the `video/` folder.
3. In the repo, go to **Settings → Pages**. Under "Build and deployment," set the
   source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two, the site appears at
   `https://YOUR-USERNAME.github.io/think-vs-feel/`.

## Add the video

**Option A, the file:** export your Zoom recording as an MP4, name it
`think-vs-feel.mp4`, and put it in the `video/` folder.
GitHub's website uploader only takes files up to 25 MB, and GitHub rejects any
file over 100 MB. A 4-minute recording is often bigger than 25 MB, so either
compress it first (HandBrake's "Fast 720p30" preset works well) or upload it
with GitHub Desktop.

**Option B, YouTube:** upload the video as **Unlisted**, copy the ID from the
link (the part after `v=`), and paste it into `SITE.youtubeId` near the top of
the script in `index.html`. The site then plays it from YouTube instead.

## Things you can edit at the top of the script in index.html

- `SITE.videoFile`, `SITE.youtubeId`, `SITE.pollUrl`
