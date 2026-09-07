# EgoNoiseSeparation Project Page

Static project page for RecurGraph and Transfer-DiT.

Directory roles:

- the private experiment repository: experiment data, page-builder code, and
  configuration source of truth
- the public `EgoNoiseSeparation` repository: source code on the `main` branch
  and generated publication assets on the `gh-pages` branch represented by
  this worktree

Code repository:

https://github.com/kokieto/EgoNoiseSeparation

Public page:

https://kokieto.github.io/EgoNoiseSeparation/

Model weights:

https://huggingface.co/kokieto/EgoNoiseSeparation

Open `index.html` through GitHub Pages or a local static server.

```bash
conda activate l2hww
python -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```
