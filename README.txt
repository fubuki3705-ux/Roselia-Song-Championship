Roselia Song Championship - prototype

Required structure:

index.html
songs.json
images/
  songs/
    ... jacket files ...

How this prototype works:
- Loads songs.json
- Randomly chooses 64 songs
- 16 groups of 4
- Pick 2 songs from every group
- 32-song knockout tournament
- Every knockout round is reshuffled
- Saves progress in browser localStorage
- YouTube area is currently only a placeholder

GitHub Pages:
1. Upload index.html, songs.json, and images/ to the repository root.
2. Repository Settings -> Pages
3. Build and deployment -> Deploy from a branch
4. Branch: main / folder: /(root)

Important:
Image paths in songs.json should look like:
  images/songs/filename.png

Do not use Windows local paths in the web-facing songs.json.
