# VLM SSM Vision Encoders Project Page

This folder is a self-contained static GitHub Pages site for the paper:

`Do VLMs Need Vision Transformers? Evaluating State Space Models as Vision Encoders`

## Preview locally

From this folder:

```bash
cd /lustre/nvwulf/home/skuo/vlm-project/lab-spell.github.io/vlm-ssm-vision-encoders
python3 -m http.server 8000
```

Then open:

`http://localhost:8000`

If you want to preview it exactly as a subpath of the main Pages site, serve the parent `lab-spell.github.io` directory instead and open:

```bash
cd /lustre/nvwulf/home/skuo/vlm-project/lab-spell.github.io
python3 -m http.server 8000
```

`http://localhost:8000/vlm-ssm-vision-encoders/`

## Deploy to GitHub Pages

This site is fully static. There is no build step.

1. Commit the files in `lab-spell.github.io/vlm-ssm-vision-encoders`.
2. Push to the branch that GitHub Pages already publishes for the `lab-spell.github.io` site.
3. Visit `https://lab-spell.github.io/vlm-ssm-vision-encoders/`.

If GitHub Pages is not configured yet:

1. Open the GitHub repository settings.
2. Go to `Pages`.
3. Set the source to `Deploy from a branch`.
4. Choose the branch that contains `lab-spell.github.io/vlm-ssm-vision-encoders`.
5. Save, then wait for GitHub Pages to publish.

## Notes

- All paths are relative, so the site works both locally and on the deployed GitHub Pages subpath.
