git remote add origin <your-repo-url>
# Video Assignment Repository

This repository contains a simple web page demonstrating the HTML `video` tag.

- `index.html`: Simple page with a `video` element.

Video explanation (replace the placeholder with your uploaded video URL after uploading):

Video walkthrough: [VIDEO_LINK_PLACEHOLDER]

How to push to GitHub (replace <your-repo-url> with the remote URL):

```bash
cd video-assignment
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```

Suggested video steps:

1. Record a short (30–90s) screen or phone video explaining the Git commands used in this assignment and their purpose.
2. Upload the video to YouTube (set to Public or Unlisted) or Vimeo.
3. Replace the `VIDEO_LINK_PLACEHOLDER` above with the uploaded video URL and commit the change.

Git commands used in this assignment:

```bash
# initialize repo and commit
git init -b main
git add .
git commit -m "Initial commit: add README and index.html"

# create feature branch and commit changes
git checkout -b feature/video-update
git add index.html
git commit -m "Feature: add paragraph and change video source"

# merge back to main
git checkout main
git merge feature/video-update
```
