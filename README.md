# Luís Paulo Santos — Personal Website (Jekyll + GitHub Pages)

This site is configured for GitHub Pages using the **Minimal Mistakes** Jekyll theme.

## Publish on GitHub Pages

1. Create a repository.
   - If you want the site at `https://<username>.github.io`, name the repo `<username>.github.io`.
   - Otherwise, any repo name is fine.
2. Upload the contents of this folder to the repository root.
3. On GitHub: **Settings → Pages**
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/(root)`

## Edit content

Most content lives in `_data/*.yml`:
- `_data/profile.yml`
- `_data/publications.yml`
- `_data/projects.yml`
- `_data/teaching.yml`
- `_data/students.yml`

Pages:
- `index.md`
- `publications/index.md`
- `projects/index.md`
- `teaching/index.md`
- `students/index.md`

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```
