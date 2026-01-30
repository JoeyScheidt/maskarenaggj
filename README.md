# Project Setup

## Prerequisites

1. Install Git LFS: <https://git-lfs.github.com/>
2. Run: `git lfs install`
3. Clone the repo: `git clone <repo-url>`
4. Run: `git lfs pull` (to download all LFS files)

## After Cloning

1. Right-click the `.uproject` file
2. Select "Generate Visual Studio project files"
3. Open the `.sln` file in Visual Studio/Rider

## Important Notes

- Always run `git lfs pull` after pulling changes
- Large assets (textures, models, audio) are tracked by Git LFS
- Don't commit personal IDE settings (already ignored)
