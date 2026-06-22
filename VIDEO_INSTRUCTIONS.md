Video Recording Script and Upload Instructions

Script (30–90 seconds):

1. Intro (5–10s): "Hi — this is a quick walkthrough of the Git commands I used for the Video Assignment."
2. Initialize & commit (10–20s): "I initialized the repository with `git init -b main`, added files with `git add .`, and saved the first snapshot with `git commit -m \"Initial commit: add README and index.html\"`."
3. Feature branch (10–20s): "I created a feature branch with `git checkout -b feature/video-update`, made changes to `index.html`, then committed them with `git add index.html` and `git commit -m \"Feature: add paragraph and change video source\"`."
4. Merge (10–15s): "I returned to `main` and merged the feature branch with `git checkout main` and `git merge feature/video-update`. This preserved the work and updated `main`."
5. Push (5–10s): "To share the repository, add a remote and push: `git remote add origin <your-repo-url>` and `git push -u origin main`."
6. Closing (5s): "Thanks — repository link is in the README."

Recording tips:
- Use your phone or screen recorder (OBS, QuickTime, Windows Game Bar).
- Hold the phone steady or capture the screen while running the commands in a terminal.
- Speak clearly and keep the video between 30 and 90 seconds.

Upload steps (YouTube):
1. Sign in to YouTube and click Create → Upload video.
2. Select the video file.
3. Set visibility to Unlisted or Public.
4. Add a short title like "Video Assignment — Git walkthrough" and a short description.
5. Copy the video URL after upload completes.
6. Edit `README.md` in the repo: replace `VIDEO_LINK_PLACEHOLDER` with the URL, commit, and push.

Commands to update README after uploading:

```bash
# replace VIDEO_LINK_PLACEHOLDER in README.md, then:
git add README.md
git commit -m "Add walkthrough video link"
git push
```
