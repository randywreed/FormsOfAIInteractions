# Forms of AI Interactions

This repository is a small static site of interactive, browser-based visualizations that explain different AI concepts with HTML and D3.js.

## What’s in the repo

- `index.html` is the entry page and links to the available visualizations.
- `reinforcement_learning.html` shows a grid-world Q-learning demo.
- `image_diffusion.html` explains diffusion model noise and denoising.
- `diffusion_inference.html` walks through the Stable Diffusion inference pipeline.
- `Inside_the_model.html` visualizes what happens inside a neural network.
- `llm_pretraining.html` illustrates the pre-training flow for a language model.
- The `*_guide.txt` files provide companion notes for the visualizations.

## How to run it

Because this is a static site, you can open `index.html` directly in a browser. For the best experience, serve the folder locally:

```bash
cd /workspaces/FormsOfAIInteractions
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/` in your browser.

## Notes

- The site does not require a build step or external package install.
- All visualizations run entirely in the browser.