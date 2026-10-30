# How to publish your GitHub profile

1. Sign into **github.com/Shwethabathina**.
2. Create a **public** repository named **Shwethabathina** (exact username, case preserved). If it already exists, open it instead.
3. Upload `README.md`, the complete `assets/` folder, and `.github/workflows/snake.yml` **preserving paths**. GitHub's website uploader may not preserve the hidden `.github` directory automatically; use VS Code / git when necessary.
4. Commit to the default branch. Your GitHub profile will automatically display the README.
5. In the repo, go to **Actions → Generate contribution snake → Run workflow**. Check that a branch named `output` appears. In **Settings → Actions → General → Workflow permissions**, allow read and write permissions if the workflow fails to push.
6. Wait until action finishes and refresh your profile. The snake should appear when you expand the disclosure.
7. You can leave pinned repositories as they are or customize them separately; the README does not include a featured-projects section.

## Notes and limitations

- Pastel banner is the custom illustration you approved, cropped to hero only. It is a **static PNG**; terminal, dividers, footer and typing line are animated SVG resources.
- README files can use HTML details toggles and click-through links, but cannot run custom JavaScript, hover-based React components or live 3D simulations.
- Some third-party stat/icon providers occasionally fail or impose rate limits. GitHub analytics show public activity and are not performance scores.
- The actual custom hero image has text baked into the artwork. Edit/replace `assets/pastel-hero.png` if you want different wording; no original PSD/layered design file is included.
- The generated illustration depicts a fictional character, not a photo or exact likeness.
- Do not upload the `SETUP.md` file unless you want it in your repository: it is just for your reference.
